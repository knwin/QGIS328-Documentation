.. Purpose: This chapter aims to describe how the user starts to use QGIS. It
.. should be kept short with only few steps to get QGIS working with two layers.

.. _`label.getstarted`:

**************
စတင်အသုံးပြုခြင်း
**************

.. only:: html

   .. contents::
      :local:

ဤအခန်းတွင် QGIS Software ထည့်သွင်းခြင်း၊ QGIS နမူနာဒေတာများ Downloading (ဒေါင်းလုဒ်ပြုလုပ်ခြင်း) နှင့် ရိုးရှင်းသော Raster နှင့် Vector ဒေတာများ ထည့်သွင်းကြည့်ရှုခြင်းအပိုင်းတို့ ပါဝင်ပါသည်။

.. index:: Installation
.. _`label_installation`:

QGIS Software ထည့်သွင်းခြင်း
========================

အသုံးပြုသူများ၏ Platform ပေါ်မူတည်၍ QGIS Software ထည့်သွင်းနည်း အမျိုးမျိုးရှိပါသည်။

Binary များမှတဆင့် Software ထည့်သွင်းခြင်း
------------------------------------

|win| Microsoft Windows OS နှင့် |osx| Mac OS တို့အတွက် စံသတ်မှတ်ထားသည့် Installers များရရှိနိုင်ပါသည်။
GNU/Linux |nix| OS များအတွက် Binary Packages (rpm နှင့် deb) များနှင့် Software Repositories (သိုလှောင်ခန်း) များ ထောက်ပံ့ပေးထားပါသည်။

အသုံးပြုသူများ၏ OS နှင့်ပတ်သက်၍ ပိုမိုသိရှိလိုသည်များနှင့် ညွှန်ကြားချက်များအတွက်  
https://download.qgis.org. တွင်ဝင်ရောက်ကြည့်ရှုနိုင်ပါသည်။

မူလအရင်းအမြစ်မှ Software ထည့်သွင်းခြင်း
----------------------------------

QGIS ကို မူလအရင်းအမြစ်မှ ထည့်သွင်းရန်လိုအပ်ပါက software ထည့်သွင်းခြင်းညွှန်ကြားချက်ကို ကိုးကားပါ။
:file:`INSTALL` ဟုခေါ်သော Source Code (အရင်းအမြစ်ကုဒ်) ဖိုင်ဖြင့် ဖြန့်ဝေထားပါသည်။ :source:`INSTALL.md`တွင်လည်း အွန်လိုင်းမှတဆင့် ရှာဖွေနိုင်ပါသည်။


ပြင်ဆင်ဆဲ version ကို အသုံးမပြုချင်ပဲ ဖြန့်ဝေပြီးသား version ကိုအသုံးပြုချင်ပါက အထက်တွင်ဖော်ပြထားသော လင့်ခ်မှ  ``master`` ဆိုသည့်နေရာတွင် Release Branch (များသောအားဖြင့် 
``release-X_Y`` ပုံစံ) ဖြင့် အစားထိုးသင့်သည်။ (Software ထည့်သွင်းခြင်း ညွန်ကြားချက် ကွာခြားမှုရှိနိုင်ပါသည်).

External media (ပြင်ပမီဒီယာ) ပေါ်တွင် Software ထည့်သွင်းခြင်း
-----------------------------------------------------

QGIS software (Plugins များနှင့် Settings(အပြင်အဆင်) အားလုံးအပါအဝင်) ကို Flash Drive (USB memory stick) ပေါ်တွင် ထည့်သွင်းအသုံးပြုနိုင်ပါသည်။ 
ပုံမှန် :ref:`user profile <user_profiles>` လမ်းကြောင်းကို ပြင်ဆင်မည့် :ref:`--profiles-path <profiles-path_option>` တခု သတ်မှတ်ပေးပြီး
**QSettings** အား ထိုပြင်ဆင်သတ်မှတ်ထားသော လမ်းကြောင်းကိုအသုံးပြုစေခြင်းဖြင့် ရရှိနိုင်ပါသည်။
ထပ်မံသိရှိလိုသည်များအတွက် :ref:`env_options` ဆိုသည့် အပိုင်းတွင် ကြည့်ရှုနိုင်ပါသည်။

.. Todo: Expand a bit on the process because the linked chapter does not tell
  more or find a more informative section.


.. index:: Data sample
.. _label_sampledata:

နမူနာဒေတာများ Download ပြုလုပ်ခြင်း
------------------------------

ဤအသုံးပြုသူလမ်းညွှန်တွင် QGIS နမူနာ Dataset (ဒေတာအစု)များကို အခြေခံထားသော ဥပမာများ ပါဝင်ပါသည်။  ( ``Alaska dataset`` ဟုလည်း ခေါ်ဆိုပါသည်။)  
နမူနာဒေတာများကို  https://github.com/qgis/QGIS-Sample-Data/archive/master.zip မှတဆင့် Download ပြုလုပ်ပြီးသင့်ကွန်ပျူတာပေါ်ရှိ အဆင်ပြေသည့်နေရာတွင် Zip ဖိုင်ကို ဖြည်ထားပါ။

ဤလမ်းညွှန်တွင် ပါဝင်သော ဥပမာများနှင့် screenshots အတွက် အသုံးပြုထားသော GIS ဒေတာများအားလုံး Alaska Dataset တွင် ပါဝင်ပါသည်။
GRASS GIS database (စနစ်တကျဖွဲ့စည်းထားသော အချက်အလက်အစုအစည်း) အသေးလေးတခုလည်း ပါဝင်ပါသည်။ 
QGIS နမူနာ datasets များအတွက် projection (ပုံရိပ်ချစနစ်) သည် Alaska Albers Equal Area ဖြစ်ပြီး ယူနစ်မှာ ‘ပေ’ ဖြစ်ပါသည်။ 
EPSG (European Petroleum Survey Group) ကုဒ်နံပါတ်မှာ 2964 ဖြစ်ပါသည်။

::

  PROJCS["Albers Equal Area",
  GEOGCS["NAD27",
  DATUM["North_American_Datum_1927",
  SPHEROID["Clarke 1866",6378206.4,294.978698213898,
  AUTHORITY["EPSG","7008"]],
  TOWGS84[-3,142,183,0,0,0,0],
  AUTHORITY["EPSG","6267"]],
  PRIMEM["Greenwich",0,
  AUTHORITY["EPSG","8901"]],
  UNIT["degree",0.0174532925199433,
  AUTHORITY["EPSG","9108"]],
  AUTHORITY["EPSG","4267"]],
  PROJECTION["Albers_Conic_Equal_Area"],
  PARAMETER["standard_parallel_1",55],
  PARAMETER["standard_parallel_2",65],
  PARAMETER["latitude_of_center",50],
  PARAMETER["longitude_of_center",-154],
  PARAMETER["false_easting",0],
  PARAMETER["false_northing",0],
  UNIT["us_survey_feet",0.3048006096012192]]

QGIS ကို GRASS အတွက် Graphical front end (ဂရပ်ဖစ် မျက်နှာပြင်) အနေဖြင့်အသုံးပြုလိုပါက GRASS GIS ၏ တရားဝင်ဝက်ဘ်ဆိုဒ် ဖြစ်သော 
https://grass.osgeo.org/download/data/ တွင် နမူနာတည်နေရာများ (ဥပမာ- Spearfish သို့မဟုတ် South Dakota) ကို ရွေးချယ်ရှာဖွေနိုင်ပါသည်။

.. index:: Start QGIS, Stop QGIS
.. _`label_startingqgis`:

QGIS အဖွင့်အပိတ်ပြုလုပ်ခြင်း
======================

QGIS ကို သင့်ကွန်ပျူတာရှိ အခြား Application များကဲ့သို့ စတင်ဖွင့်နိုင်ပါသည်။
QGIS ကို အောက်ပါနည်းများဖြင့် စတင်ဖွင့်နိုင်ပါသည်-

* Applications menu |nix| အသုံးပြုခြင်း၊ Start menu |win| အသုံးပြုခြင်း၊ Dock |osx| ကို အသုံးပြုခြင်း
* သင့် Application folder ထဲရှိ QGIS icon သို့မဟုတ် Desktop shortcut icon အား double click (ကလစ် ၂ ချက်နှိပ်ခြင်း) ပြုလုပ်ခြင်း
* ရှိပြီးသား QGIS project ဖိုင် (:file:`.qgz` သို့မဟုတ် :file:`.qgs`
  extension ဖြင့်အဆုံးသတ်သောဖိုင်). ထိုသို့ဖွင့်ပါက ပရောဂျက် ပါပွင့်လာမည်ဖြစ်သည်။
* Command prompt တွင် ``qgis`` ဟုရိုက်၍ ဖွင့်ခြင်း (QGIS ထည့်သွင်းထားသော folder လမ်းကြောင်းပေါ်တွင် တည်ရှိနေသည်ဟုယူဆလျက်)

QGIS ကိုပိတ်ရန်အတွက်

* |nix| |win| Menu မှတဆင့် :menuselection:`Project --> Exit QGIS` ကိုနှိပ်ပါ၊
  သို့မဟုတ် :kbd:`Ctrl+Q` shortcut ကိုအသုံးပြုပါ။
* |osx| :menuselection:`QGIS --> Quit QGIS` ကိုနှိပ်ပါ၊ သို့မဟုတ် :kbd:`Cmd+Q` shortcut ကိုအသုံးပြုပါ။
* သို့မဟုတ် QGIS application မျက်နှာပြင် ညာဘက်အပေါ်ထောင့်ရှိ အနီရောင်ကြက်ခြေခတ်ကို အသုံးပြုပါ။


.. _samplesession:

နမူနာအပိုင်း- Raster အလွှာများနှင့် Vector အလွှာများအား ထည့်သွင်းခြင်း
=========================================================

ယခု :ref:`QGIS installed <label_installation>` လုပ်ဆောင်ပြီးစီးပြီး :ref:`sample
dataset <label_sampledata>` တခုရှိနေပြီဖြစ်သည်။ ပထမဦးဆုံးနမူနာအပိုင်းကို သရုပ်ပြသွားပါမည်။
ဒီဥပမာမှာတော့ Raster အလွှာ ၁ ခုနှင့် Vector အလွှာ ၁ ခုကို ပုံဖော်ကြည့်ရှုပါမည်။ အသုံးပြုမည့် အလွှာတွေကတော့-

* :file:`landcover` (မြေဖုံးလွှမ်းမှု) raster အလွှာ (:file:`qgis_sample_data/raster/landcover.img`) နှင့်
* :file:`lakes` (ရေကန်များကိုဖော်ပြသော) vector အလွှာ (:file:`qgis_sample_data/gml/lakes.gml`) တို့ဖြစ်ပါသည်။

:file:`qgis_sample_data` ဆိုသည်မှာ Dataset ဖိုင်များကို Zip ဖြည်ထားသော Folder လမ်းကြောင်းကို ကိုယ်စားပြုခြင်းဖြစ်ပါသည်။

#. :ref:`label_startingqgis`အပိုင်းတွင် မြင်တွေ့ခဲ့ရသည့်အတိုင်း QGIS ကို စတင်ဖွင့်ပါ။
#. အသုံးပြုမည့် ဒေတာများသည် ``Albers Equal Area`` Projection ဖြစ်သည့်အတွက် 
   project ၏ CRS (ကိုဩဒိနိတ်စနစ်) ကို အောက်ပါအတိုင်း သတ်မှတ်ပါမည်-
   
   #. QGIS မျက်နှာပြင်၏ ညာဘက်အောက်ခြေရှိ |setProjection| :sup:`Select projection` ကိုနှိပ်ပါ။
      Project properties ထဲမှ :guilabel:`CRS` ဆိုသည့် Tab ပွင့်လာမည်ဖြစ်သည်။
   #. |search| :guilabel:`Filter` ဆိုသည့်အကွက်ထဲတွင် '2964' ဟု ရိုက်ထည့်ပါ။
   #. ``NAD27 / Alaska Albers`` ဆိုသည့် CRS အမည်ဖြင့် Row ကိုရွေးချယ်ပါ။.

      .. _figure_selectCRS:

      .. figure:: img/selectCRS.png
         :align: center

         ဒေတာ၏ Coordinate Reference System (CRS) ရွေးချယ်ခြင်း

   #. :guilabel:`OK` ကိုနှိပ်ပါ။

   .. note:: "ballpark transform" ဆိုသည့် စာသားပေါ်လာပါက ထိုစာသားကို ပိတ်ထားလိုက်လို့ရပါသည်။


#. QGIS ထဲသို့ ဖိုင်များထည့်သွင်းခြင်း

   #. |dataSourceManager| :sup:`Open Data Source Manager` ကိုနှိပ်ပါ။ 
      Data Source Manager သည် Browser ပုံစံဖြင့် ပွင့်လာမည်ဖြစ်သည်။
   #. :file:`qgis_sample_data/raster/` ဆိုသည့် Folder ကိုဖွင့်ပါ။
   #. |rasterLayer| :guilabel:`landcover.img` ဖိုင်ကို ကလစ် ၂ ချက်နှိပ်ပါ။
      Landcover အလွှာသည် QGIS ထဲသို့ ရောက်ရှိသွားမည်ဖြစ်ပြီး Data Source Manager window သည် ပွင့်လျက် ရှိနေဦးမည်ဖြစ်သည်။

      .. _figure_addstartraster:

      .. figure:: img/add_raster.png
         :align: center

         QGIS ၏ Project အသစ်တခုထဲသို့ ဒေတာများ ထည့်သွင်းခြင်း

   #. Lakes ဆိုသည့် Vector ဒေတာကို ထည့်သွင်းရန်အတွက် :file:`qgis_sample_data/gml/` ဆိုသည့် Folder ကိုဖွင့်ပြီး
      |dbSchema| :guilabel:`lakes.gml` ဖိုင်ကို QGIS main window ထဲသို့ Drag and Drop (ကလစ်ဖိထားပြီးဆွဲထည့်ခြင်း) ပြုလုပ်ပါ။
      (သို့မဟုတ် အပေါ်တွင် ဖော်ပြထားသည့်အတိုင်း ကလစ် ၂ ချက် နှိပ်ပါ။)
   #. :guilabel:`Select Items to Add` ဆိုသည့် Dialog ပွင့်လာပြီး ပါဝင်သောဖိုင်များကို Scan ပြုလုပ်ပါလိမ့်မည်။
      အကြောင်းမှာ:file:`.gml` ဖိုင်အမျိုးအစားသည် တခုထက်ပိုသော အလွှာများကို သိမ်းဆည်းထားနိုင်သောကြောင့် ဖြစ်သည်။

      .. _figure_selectitems:

      .. figure:: img/addLayerItems.png
         :align: center

         ဖိုင်တခုအတွင်းရှိ အလွှာများအား ရွေးချယ်ခြင်း

   #. ယခုဥပမာတွင် |polygonLayer| :guilabel:`lakes` အလွှာတခုသာရှိပါသည်။
      ထိုအလွှာကိုရွေးချယ်ပြီး :guilabel:`Add Layers`ကိုနှိပ်ပါ။
   #. ထိုအလွှာသည် QGIS ၏ :guilabel:`Layers` panel အတွင်းသို့ ရောက်ရှိသွားပါမည်။
#. Data Source Manager window ကိုပိတ်လိုက်ပါ။

:guilabel:`Layers` panel ရှိ :guilabel:`lakes` အလွှာဘေးတွင် 
|indicatorNoCRS| :sup:`Layer has no coordinate reference system set` (အလွှာတွင် CRS မသတ်မှတ်ရသေးပါ) ဆိုပြီး ပြသနေသည်ကို တွေ့ရလိမ့်မည်။
ထိုအရာကို သတ်မှတ်ပြင်ဆင်ကြရအောင်။

#. |indicatorNoCRS| ပုံကိုနှိပ်ပါ။
   :guilabel:`Coordinate Reference System Selector` dialog ပွင့်လာပါမည်။
#. အစောပိုင်းက ပြုလုပ်ခဲ့သလိုမျိုး :guilabel:`NAD27 / Alaska Albers` CRS ကိုရှာပြီး ရွေးချယ်ပေးပါ။
#. :guilabel:`OK` ကိုနှိပ်ပါ။

ယခု project ဖိုင်ထဲတွင် random colours (ကျပန်း အရောင်) များဖြင့် အလွှာ ၂ ခု ရှိနေပြီဖြစ်သည်။ 
Lakes ဆိုသည့် အလွှာကို ပြင်ဆင်မှုတချို့လုပ်ကြည့်ရအောင်။

#. :guilabel:`Navigation` toolbar ပေါ်ရှိ |zoomIn| 
:sup:`Zoom In` tool ကိုရွေးပါ။ 
#. ရေကန်တချို့ရှိနေသော ဧရိယာတခုကို Zoom (အကျယ်ချဲ့) လုပ်ကြည့်ပါ။
#. :file:`lakes` အလွှာကို ကလစ် ၂ ချက်နှိပ်ပါ။
:guilabel:`Properties` dialog ဖွင့်ရန်အတွက် 
   
#. ရေကန်အလွှာ၏ အရောင်ပြောင်းလဲရန်အတွက်-

   #. |symbology| :guilabel:`Symbology` ကိုနှိပ်ပါ။
   #. အပြာရောင်ကို Fill (အရောင်အပြည့်ဖြည့်) အနေဖြင့် ရွေးချယ်ပါ။

      .. _figure_selectColor:

      .. figure:: img/selectFillColor.png
         :align: center

         ရေကန်အလွှာ၏ အရောင်ရွေးချယ်ခြင်း

   #. :guilabel:`OK` ကိုနှိပ်ပါ။ Map Canvas (မြေပုံကိုပြသသည့်နေရာ) ထဲတွင် ရေကန်များကို အပြာရောင်ဖြင့် ပြသနေသည်ကိုတွေ့ရပါမည်။
#. ရေကန်များ၏နာမည်များကို ပြသရန်အတွက်-

   #. :file:`lakes` အလွှာ၏ :guilabel:`Properties` dialog ကိုပြန်ဖွင့်ပါ။
   #. |labelingSingle| :guilabel:`Labels` ကိုနှိပ်ပါ။
   #. Labeling (နာမည်များပြသခြင်း) ကိုဖွင့်ပေးရန်အတွက် Drop-down menu တွင် :guilabel:`Single labels` ကိုရွေးချယ်ပါ။
   #. :guilabel:`Label with` list ထဲမှ ``NAMES`` ဆိုသည့် field ကိုရွေးပါ။

      .. _figure_showLabels:

      .. figure:: img/showLabels.png
         :align: center

         ရေကန်နာမည်များအား ပြသခြင်း

   #. :guilabel:`Apply` ကိုနှိပ်ပါ။ နာမည်များသည် ရေကန်များ၏ နယ်နိမိတ်အပေါ်တွင် ပေါ်နေမည်ဖြစ်သည်။
#. Labels များကို ဖတ်ရှုရာတွင် ပိုမိုကောင်းမွန်စေရန် Labels စာလုံးများ၏အနားသတ်များကို အဖြူရောင် Buffer (အနားကွပ်) ထည့်ပေးခြင်းပြုလုပ်နိုင်ပါသည်-

   #. List ၏ဘယ်ဘက်ရှိ :guilabel:`Buffer` ကိုနှိပ်ပါ။
   #. :guilabel:`Draw text buffer` ၏ဘေးတွင် |checkbox| အမှန်ခြစ်ပေးပါ။
   #. Buffer size နေရာတွင် ``3`` ကိုရွေးချယ်ပါ။
   #. :guilabel:`Apply` ကိုနှိပ်ပါ။
   #. ရရှိလာသည့် ရလာဒ်ပုံစံ ကြည့်ကောင်းမကောင်း စစ်ဆေး၍ လိုအပ်လျှင် တန်ဖိုးကို ပြောင်းလဲသတ်မှတ်ပါ။
   #. နောက်ဆုံးတွင် :guilabel:`Layer Properties` dialog ကိုပိတ်ရန်နှင့် ပြောင်းလဲမှုများကို Apply (အသုံးပြု) လုပ်ရန် :guilabel:`OK` ကိုနှိပ်ပါ။

      .. _figure_buffer_around_labels:

      .. figure:: img/buffer_around_labels.png
         :align: center

         Labels များ၏အနားသတ်များအား Buffer ထည့်ပေးခြင်း

မြေပုံပြင်ဆင်ရန်နှင့် QGIS မှ မြေပုံ Export (ထုတ်လုပ်ရန်) ပြုလုပ်ရန်အတွက် တချို့ပြင်ဆင်မှုများ လုပ်ကြည့်ရအောင်-

#. :menuselection:`View --> Decorations --> Scale Bar` menu ရွေးချယ်ပါ။
#. Dialog ပွင့်လာလျှင် :guilabel:`Enable Scale Bar` ဆိုသည်ကို |checkbox| အမှန်ခြစ်ပေးပါ။
#. Dialog ထဲမှ Options (ရွေးချယ်စရာများ) များကို လိုအပ်သလိုပြင်ဆင်သတ်မှတ်ပါ။
#. :guilabel:`Apply` ကိုနှိပ်ပါ။
#. အထက်ပါအတိုင်း Decorations menu မှ တခြားထည့်သွင်းချင်သည့်အရာများ (မြောက်အရပ်ပြမြှား၊ မူပိုင်ခွင့်၊ အစရှိသည်တို့....) ကို နှစ်သက်ရာပုံစံဖြင့် Map Canvas ထဲသို့ ထည့်သွင်းပါ။
#. :menuselection:`Project --> Import/Export -->` ကိုနှိပ်ပြီး |saveMapAsImage|
   :menuselection:`Export Map to Image...` ကိုနှိပ်ပါ။
#. ပွင့်လာသော Dialog တွင် :guilabel:`Save` ကိုနှိပ်ပါ။
#. ဖိုင်သိမ်းဆည်းမည့်နေရာ၊ ဖိုင်အမျိုးအစားတို့ကို ရွေးချယ်ပြီး သိမ်းဆည်းဖို့အတည်ပြုရန် :guilabel:`Save` ကိုထပ်နှိပ်ပါ။
#. ပြင်ဆင်ပြောင်းလဲမှုများကို :file:`.qgz` project ဖိုင်အနေဖြင့် သိမ်းဆည်းရန်အတွက် :menuselection:`Project -->` |fileSave| :menuselection:`Save...` ကိုနှိပ်ပါ။

      .. _figure_map_with_decorations:

      .. figure:: img/map_with_decorations.png
         :align: center

         ပြင်ဆင်မှုများပြုလုပ်ထားပြီး Export ထုတ်ထားသော မြေပုံအား ပြသခြင်း

ဒီလောက်ပါပဲ။ Raster နှင့် Vector အလွှာများကို QGIS တွင် ပြသခြင်း၊ ပြင်ဆင်မှုများပြုလုပ်ခြင်းနှင့် 
တခြား software များတွင်အသုံးပြုနိုင်ရန် မြေပုံအမျိုးအစား ဖန်တီးခြင်းများကို လွယ်ကူစွာပြုလုပ်နိုင်သည်ကို မြင်တွေ့ရပြီးဖြစ်ပါသည်။ 
ယခုထက်ပိုမို ရရှိနိုင်သည့် functionality (လုပ်နိုင်စွမ်းများ)၊ features (အသွင်အပြင်များ)၊ settings (အပြင်အဆင်များ) များအကြောင်းနှင့် 
ထိုအရာများကို ဘယ်လိုအသုံးချနိုင်မလဲဆိုတာ ဆက်လက်လေ့လာကြည့်ရအောင်။

.. note::
 QGIS လေ့ကျင့်ခန်းများကို တဆင့်ချင်းဆက်လက်လေ့လာနိုင်ရန်အတွက် :ref:`Training manual <QGIS-training-manual-index-reference>` (သင်တန်းလက်စွဲ) ကို ကြည့်ရှုပါ။
 


.. Substitutions definitions - AVOID EDITING PAST THIS LINE
   This will be automatically updated by the find_set_subst.py script.
   If you need to create a new substitution manually,
   please add it also to the substitutions.txt file in the
   source folder.

.. |checkbox| image:: /static/common/checkbox.png
   :width: 1.3em
.. |dataSourceManager| image:: /static/common/mActionDataSourceManager.png
   :width: 1.5em
.. |dbSchema| image:: /static/common/mIconDbSchema.png
   :width: 1.5em
.. |fileSave| image:: /static/common/mActionFileSave.png
   :width: 1.5em
.. |indicatorNoCRS| image:: /static/common/mIndicatorNoCRS.png
   :width: 1.5em
.. |labelingSingle| image:: /static/common/labelingSingle.png
   :width: 1.5em
.. |nix| image:: /static/common/nix.png
   :width: 1em
.. |osx| image:: /static/common/osx.png
   :width: 1em
.. |polygonLayer| image:: /static/common/mIconPolygonLayer.png
   :width: 1.5em
.. |rasterLayer| image:: /static/common/mIconRasterLayer.png
   :width: 1.5em
.. |saveMapAsImage| image:: /static/common/mActionSaveMapAsImage.png
   :width: 1.5em
.. |search| image:: /static/common/search.png
   :width: 1.5em
.. |setProjection| image:: /static/common/mActionSetProjection.png
   :width: 1.5em
.. |symbology| image:: /static/common/symbology.png
   :width: 2em
.. |win| image:: /static/common/win.png
   :width: 1em
.. |zoomIn| image:: /static/common/mActionZoomIn.png
   :width: 1.5em
