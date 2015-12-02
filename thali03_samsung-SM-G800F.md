#### Test 50388019193a02f_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
I/SELinux ( 4935): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4935):  
I/SELinux ( 4935): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4935):  
I/SELinux ( 4935):  
I/SELinux ( 4935): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4935): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4935): >>>>> Normal User
E/dalvikvm( 4935): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
E/SELinux ( 4935): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4935): in addTimaSignatureService
D/TimaKeyStoreProvider( 4935): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4935): Added TimaKesytore provider
,D/dalvikvm( 4935): GC_CONCURRENT freed 3003K, 32% free 9570K/14060K, paused 3ms+5ms, total 29ms
D/dalvikvm( 4935): WAIT_FOR_CONCURRENT_GC blocked 23ms
D/BluetoothBDAdrressReceiver( 4935): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4935): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
--------- beginning of /dev/log/system
W/ContextImpl( 4935): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4951): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4951):  
D/BluetoothBDTestService( 2756): onCreate()
E/BluetoothBDTestService( 2756): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
E/BluetoothBDTestService( 2756): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 2756): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager( 2423): Killing 3916:com.android.externalstorage/u0a9 (adj 15): empty #43
I/SELinux ( 4951): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4951):  
I/SELinux ( 4951):  
I/SELinux ( 4951): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4951): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4951): >>>>> Normal User
E/dalvikvm( 4951): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
E/SELinux ( 4951): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4951): in addTimaSignatureService
D/TimaKeyStoreProvider( 4951): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4951): Added TimaKesytore provider
D/dalvikvm( 4951): GC_CONCURRENT freed 2987K, 32% free 9573K/14052K, paused 3ms+1ms, total 21ms
D/dalvikvm( 4951): WAIT_FOR_CONCURRENT_GC blocked 13ms
I/SELinux ( 4963): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4963):  
I/ActivityManager( 2423): Killing 3958:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 2 sec
I/SELinux ( 4963): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4963):  
I/SELinux ( 4963):  
I/SELinux ( 4963): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4963): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4963): >>>>> Normal User
E/dalvikvm( 4963): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 4963): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/TimaKeyStoreProvider( 4963): in addTimaSignatureService
D/TimaKeyStoreProvider( 4963): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4963): Added TimaKesytore provider
D/dalvikvm( 4963): GC_CONCURRENT freed 3004K, 32% free 9567K/14060K, paused 3ms+1ms, total 20ms
D/dalvikvm( 4963): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/AndroidRuntime( 4949): 
D/AndroidRuntime( 4949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4949): CheckJNI is OFF
D/AndroidRuntime( 4949): setted country_code = Poland
D/AndroidRuntime( 4949): setted countryiso_code = PL
D/AndroidRuntime( 4949): setted sales_code = PLS
D/AndroidRuntime( 4949): readGMSProperty: start
D/AndroidRuntime( 4949): readGMSProperty: already setted!!
D/AndroidRuntime( 4949): readGMSProperty: end
D/AndroidRuntime( 4949): addProductProperty: start
E/PersonaManagerService( 2423): returning null in  getPersonasForUser
D/dalvikvm( 4949): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4949): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4949): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4949): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4949): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/SELinux ( 4975): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4975):  
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/ActivityManager( 2423): Killing 3264:com.sec.android.app.mt/1000 (adj 15): empty #43
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4920): Resource data:2131165197
V/AlarmManager( 2423): waitForAlarm result :4
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
I/ActivityManager( 2423): Waited long enough for: ServiceRecord{42fd24a8 u0 com.samsung.android.providers.context/.ContextService}
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131165194
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/SELinux ( 4975): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4975):  
I/SELinux ( 4975):  
I/SELinux ( 4975): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4975): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4975): >>>>> Normal User
E/dalvikvm( 4975): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
E/SELinux ( 4975): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4975): in addTimaSignatureService
D/TimaKeyStoreProvider( 4975): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4975): Added TimaKesytore provider
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 312, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
E/memtrack( 4949): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4949): failed to load memtrack module: -2
D/dalvikvm( 4975): GC_CONCURRENT freed 3002K, 32% free 9569K/14056K, paused 5ms+2ms, total 26ms
D/dalvikvm( 4975): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/dalvikvm( 4920): GC_CONCURRENT freed 438K, 15% free 12088K/14060K, paused 4ms+2ms, total 44ms
D/dalvikvm( 4920): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/dalvikvm( 4949): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131165194
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
D/AndroidRuntime( 4949): Calling main entry com.android.commands.am.Am
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
W/BackupManagerService( 2423): dataChanged but no participant pkg='com.android.providers.settings' uid=10088
V/ApplicationPolicy( 2423): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@4
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
I/SurfaceFlinger( 1923): id=14 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1923): id=15 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2423): mDVFSHelper.acquire()
D/Launcher.HomeView( 2784): onPause
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2423): tr p:2423,o:f
D/AndroidRuntime( 4949): Shutting down VM
D/StatusBarManagerService( 2423): tr p:2784,o:f
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/dalvikvm( 4949): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1923): id=16 createSurf (1x1),1 flag=404, iello
I/SELinux ( 4998): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4998):  
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
I/SELinux ( 4998): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4998):  
I/SELinux ( 4998):  
I/SELinux ( 4998): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4998): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4998): >>>>> Normal User
E/dalvikvm( 4998): >>>>> com.example.hello [ userId:0 | appId:10495 ]
E/SELinux ( 4998): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4998): in addTimaSignatureService
D/TimaKeyStoreProvider( 4998): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4998): Added TimaKesytore provider
V/WindowOrientationListener( 2423): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2423): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2423): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/Launcher.HomeView( 2784): onStop
D/        ( 4920): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
D/STATUSBAR-StatusBarManagerService( 2423): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4920): Resource data:2131165195
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/device_filter
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4920): Resource data:2131165204
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4920): Resource data:2131165204
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4920): Resource data:2131165204
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
,D/Launcher( 2784): onTrimMemory. Level: 20
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4920): Resource data:2131099676
D/dalvikvm( 4998): GC_CONCURRENT freed 2999K, 32% free 9566K/14056K, paused 5ms+5ms, total 46ms
D/dalvikvm( 4998): WAIT_FOR_CONCURRENT_GC blocked 41ms
I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(34)
I/SELinux ( 5012): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5012):  
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/spellscroll
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131099648
I/ActivityManager( 2423): Killing 3981:com.sec.phone/1001 (adj 15): empty #43
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/SELinux ( 5012): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5012):  
I/SELinux ( 5012):  
I/SELinux ( 5012): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5012): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5012): >>>>> Normal User
E/dalvikvm( 5012): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
E/SELinux ( 5012): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/WebViewChromium( 4998): Binding Chromium to the background looper Looper (main, tid 1) {422c5428}
D/TimaKeyStoreProvider( 5012): in addTimaSignatureService
I/chromium( 4998): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4998): Initializing chromium process, renderers=0
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/TimaKeyStoreProvider( 5012): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5012): Added TimaKesytore provider
W/chromium( 4998): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 4998): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 4998): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 4998): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 4998): Mali API Version : 401
I/Mali    ( 4998): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 3 sec
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
I/dalvikvm( 4998): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4998): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4998): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4998): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x0008
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2423): tr p:4998,o:f
D/dalvikvm( 5012): GC_CONCURRENT freed 2991K, 32% free 9578K/14056K, paused 4ms+1ms, total 57ms
D/dalvikvm( 5012): WAIT_FOR_CONCURRENT_GC blocked 40ms
I/SurfaceFlinger( 1923): id=9 Removed Mauncher (7/10)
I/SurfaceFlinger( 1923): id=9 Removed Mauncher (-2/10)
W/dalvikvm( 4998): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4998): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4998): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4998): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4998): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4998): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4998): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4998): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4998): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4998): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4998): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4998): CordovaWebView is running on device made by: samsung
I/SELinux ( 5040): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5040):  
D/        ( 4920): PNG_doEncode true 106, 106
I/ActivityManager( 2423): Killing 4068:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/SELinux ( 5040): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5040):  
I/SELinux ( 5040):  
I/SELinux ( 5040): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5040): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5040): >>>>> Normal User
E/dalvikvm( 5040): >>>>> com.dropbox.android [ userId:0 | appId:10095 ]
E/SELinux ( 5040): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 5040): in addTimaSignatureService
D/TimaKeyStoreProvider( 5040): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5040): Added TimaKesytore provider
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2423): semi p:4998,o:f
I/SurfaceFlinger( 1923): id=17 createSurf (1x1),1 flag=404, NainActivit
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 4998): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 4998): Enabling debug mode 0
W/AwContents( 4998): nativeOnDraw failed; clearing to background color.
D/dalvikvm( 5040): GC_CONCURRENT freed 2989K, 32% free 9573K/14052K, paused 3ms+1ms, total 49ms
D/dalvikvm( 5040): WAIT_FOR_CONCURRENT_GC blocked 35ms
W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 4998): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2423): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131099648
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/SurfaceFlinger( 1923): id=16 Removed iello (9/10)
I/SurfaceFlinger( 1923): id=16 Removed iello (-2/10)
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/        ( 4920): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/com.dropbox.android.service.DropboxNetworkReceiver( 5040): Setting receiver enabled: false
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131099648
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,I/chromium( 4998): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,E/AndroidProtocolHandler( 4998): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/com.dropbox.sync.android.a( 5040): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/com.dropbox.sync.android.aa( 5040): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800F armeabi-v7a; en_US))
,D/JsMessageQueue( 4998): Set native->JS mode to OnlineEventsBridgeMode
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513,
,I/SELinux ( 5077): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5077):  
,I/ActivityManager( 2423): Killing 3943:com.google.android.apps.docs/u0a94 (adj 15): empty #43,
,I/SELinux ( 5077): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5077):  
I/SELinux ( 5077):  
,I/SELinux ( 5077): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5077): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 5077): >>>>> Normal User
,E/dalvikvm( 5077): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ],
E/SELinux ( 5077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4920): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514,
,D/TimaKeyStoreProvider( 5077): in addTimaSignatureService,
,I/chromium( 4998): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported,
,D/TimaKeyStoreProvider( 5077): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 5077): Added TimaKesytore provider,
,I/chromium( 4998): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported,
,D/dalvikvm( 4998): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x422bd568,
E/libGLESv2( 4998): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 4998): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader,
,D/        ( 4920): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517,
,D/dalvikvm( 4998): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x422bd568
,D/jxcore_app_log( 4998): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2025068936
,D/JX-Cordova( 4998): jxcore cordova android initializing
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 4 sec
D/dalvikvm( 5077): GC_CONCURRENT freed 2993K, 32% free 9577K/14056K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 5077): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131099648
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/elm:14132( 5077): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 5077): ELMEngine.ELMEngine( context ).
,D/elm:14132( 5077): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 5077): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/elm:14132( 5077): ElmAgentService : onCreate()
,I/SELinux ( 5092): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5092):  
,D/elm:14132( 5077): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 5077): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 5077): BootCompletedState : startBootCompleted() call
,D/elm:14132( 5077): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 5077): MDMBridge.getAllLicenseInfoFromSDK()
I/elm:14132( 5077): Get License : 0
,D/elm:14132( 5077): ElmAgentService : onDestroy().
I/ActivityManager( 2423): Killing 4131:com.n7mobile.muzodajnia:main/u0a184 (adj 15): empty #43
,I/SELinux ( 5092): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5092):  
I/SELinux ( 5092):  
,I/SELinux ( 5092): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5092): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5092): >>>>> Normal User
,E/dalvikvm( 5092): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 5092): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/TimaKeyStoreProvider( 5092): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5092): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5092): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/System.out( 5040): Thread-371(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5040): Thread-371(ApacheHTTPLog):isShipBuild true
,I/System.out( 5040): Thread-371(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5092): GC_CONCURRENT freed 3003K, 32% free 9566K/14060K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 5092): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 5107): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5107):  
I/ActivityManager( 2423): Killing 4126:com.google.android.configupdater/u0a3 (adj 15): empty #43
,W/jxcore-log( 4998): Initializing JXcore engine
,W/jxcore-log( 4998): JXcore engine is ready
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 5107): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5107):  
I/SELinux ( 5107):  
,I/SELinux ( 5107): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5107): >>>>> Normal User
,E/dalvikvm( 5107): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 5107): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/jxcore-log( 4998): Starting JXcore engine
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,D/TimaKeyStoreProvider( 5107): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5107): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5107): Added TimaKesytore provider
D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@8
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131099648
I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/dalvikvm( 5107): GC_CONCURRENT freed 3000K, 32% free 9566K/14056K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 5107): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/CameraApp( 5107): CameraApp.onCreate()... mFeature : null
I/testFeature( 5107): Feature.Feature(context)
I/testFeature( 5107): Feature.readInternalDefaultXml()
,I/testFeature( 5107): ResetFeatureValue
,I/CameraFirmware_broadcast( 5107): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 5107): CameraApp.getAppFeature()...
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,I/SELinux ( 5119): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5119):  
,I/ActivityManager( 2423): Killing 4198:com.sec.dsm.system/1000 (adj 15): empty #43,
,I/SELinux ( 5119): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5119):  
I/SELinux ( 5119):  
,I/SELinux ( 5119): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5119): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5119): >>>>> Normal User
,E/dalvikvm( 5119): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ],
,E/SELinux ( 5119): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1924): GC_EXPLICIT freed 44K, 14% free 9503K/11036K, paused 2ms+3ms, total 34ms
,D/TimaKeyStoreProvider( 5119): in addTimaSignatureService
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 5119): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5119): Added TimaKesytore provider
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 2ms+3ms, total 24ms
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/dalvikvm( 5119): GC_CONCURRENT freed 2999K, 32% free 9567K/14056K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 5119): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/PackageIntentReceiver( 5119): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 5119): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 2423): Killing 4210:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,D/        ( 4920): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513,
,I/SELinux ( 5132): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5132):  
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/SELinux ( 5132): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5132):  
I/SELinux ( 5132):  
,I/SELinux ( 5132): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5132): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5132): >>>>> Normal User
,E/dalvikvm( 5132): >>>>> com.google.android.gm [ userId:0 | appId:10106 ]
,E/SELinux ( 5132): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/jxcore-log( 4998): Platform android
W/jxcore-log( 4998): 
,W/jxcore-log( 4998): Process ARCH arm
W/jxcore-log( 4998): 
,D/TimaKeyStoreProvider( 5132): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5132): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5132): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131099648
,I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/HarmonyEASService( 2423): Updating for all 1
,I/jxcore-log( 4998): JXcore Cordova bridge is ready!
I/jxcore-log( 4998): 
,W/jxcore-log( 4998): JXcore engine is started
D/dalvikvm( 5132): GC_CONCURRENT freed 2983K, 32% free 9588K/14060K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 5132): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Choreographer( 4998): Skipped 52 frames!  The application may be doing too much work on its main thread.
E/libGLESv2( 4998): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 4998): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/SensorService( 2423):   0.3 0.0 9.9
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/jxcore-log( 4998): >> samsung-SM-G800F
E/jxcore-log( 4998): 
,I/jxcore-log( 4998): Total memory 1319530496
I/jxcore-log( 4998): 
,I/jxcore-log( 4998): Free memory 33996800
I/jxcore-log( 4998): 
,I/jxcore-log( 4998): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4998): 
,I/jxcore-log( 4998): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4998): 
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/jxcore-log( 4998): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4998): 
,I/jxcore-log( 4998): Size 720 1280
I/jxcore-log( 4998): 
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 5 sec
,I/jxcore-log( 4998): Screen Brightness 134
I/jxcore-log( 4998): 
,E/jxcore-log( 4998): Dummy Error Log.
E/jxcore-log( 4998): 
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,W/GAV2    ( 5132): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4920): Resource data:2131099671
,I/AMMetaDataParserService( 4920): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,D/PackageManager( 2423): [MSG] MCS_UNBIND
I/PackageManager( 2423): calling disconnectService()
,D/PackageManager( 2423): Trying to unbind to DefaultContainerService
,I/SELinux ( 5158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5158):  
I/ActivityManager( 2423): Killing 4223:com.sec.factory/1000 (adj 15): empty #43
,I/SELinux ( 5158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5158):  
I/SELinux ( 5158):  
I/SELinux ( 5158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5158): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5158): >>>>> Normal User
E/dalvikvm( 5158): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5158): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5158): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5158): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5158): Added TimaKesytore provider
D/dalvikvm( 4920): GC_CONCURRENT freed 1826K, 22% free 12310K/15620K, paused 12ms+5ms, total 101ms
,D/dalvikvm( 4920): WAIT_FOR_CONCURRENT_GC blocked 48ms
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.GridSettings
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131165216
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:xml/assistant,
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml,
,D/        ( 4920): PNG_doEncode true 80, 80,
,I/AMMetaDataParserService( 4920): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,D/dalvikvm( 5158): GC_CONCURRENT freed 3000K, 32% free 9571K/14056K, paused 4ms+2ms, total 48ms,
,D/dalvikvm( 5158): WAIT_FOR_CONCURRENT_GC blocked 35ms,
,D/        ( 4920): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4920): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581,
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SubSettings,
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Password
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086,
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695,
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429071
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings,
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429071
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity,
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks,
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,I/SELinux ( 5171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5171):  
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429071
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/ActivityManager( 2423): Killing 3140:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #43
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297114
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429073
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429073
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429095
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429071
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131297114
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wifi_settings
,I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
I/SELinux ( 5171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5171):  
I/SELinux ( 5171):  
,I/SELinux ( 5171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
E/SELinux ( 5171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4920): Resource data:2131296695
E/dalvikvm( 5171): >>>>> Normal User
,E/dalvikvm( 5171): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
,E/SELinux ( 5171): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429146
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,D/TimaKeyStoreProvider( 5171): in addTimaSignatureService
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429118
,D/TimaKeyStoreProvider( 5171): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,D/ActivityThread( 5171): Added TimaKesytore provider
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/Gmail   ( 5132): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/AMMetaDataParserService( 4920): Resource data:2131298419
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131298419
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131298419
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429103
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429103
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429099
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429099
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429109
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429113
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429113
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297804
I/jxcore-log( 4998): getBuffer is called!!!!
I/jxcore-log( 4998): 
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429155
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429054
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429054
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/Gmail   ( 5132): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
D/dalvikvm( 5171): GC_CONCURRENT freed 3014K, 33% free 9556K/14060K, paused 3ms+2ms, total 38ms
D/dalvikvm( 5171): WAIT_FOR_CONCURRENT_GC blocked 34ms
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
,D/SSRMv2:SIOP( 2423): SIOP:: AP = 390, Delta = 10
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429055
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429080
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/Gmail   ( 5132): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131296750
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/Gmail   ( 5132): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4920): Re,source data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429050
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 5171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131296750
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131296750
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429114
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429114
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131298587
I/knox    ( 5171): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4920): getResourceName:com.android.se,ttings:string/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429114
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131298587
,W/ContextImpl( 5171): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429107
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/driving_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429150
I/knox    ( 5171): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/A,MMetaDataParserService( 4920): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429152
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/development_settings
D/knox    ( 5171): KNOXAgentService : onCreate()
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131296695
D/knox    ( 5171): KNOXAgentService : set alarms for deniallog and usage data upload
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
D/knox    ( 5171): KNOXAgentService. startJobThread() start
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
D/knox    ( 5171): KNOXAgentService. JobThread()
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429092
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
D/knox    ( 5171): KNOXAgentService. JobThread. notifyAll().
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
D/knox    ( 5171): KNOXAgentService. startJobThread() wait
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429152
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429150
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297938
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429150
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297938
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity,
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/SELinux ( 5188): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5188):  
I/AMMetaDataParserService( 4920): Resource data:2131429088
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429090
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429094
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
D/knox    ( 5171): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 5171): KNOXAgentService : onDestroy().
D/knox    ( 5171): ModuleBase.cancelAllAlarmManageModule()
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131296695
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429148
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429148
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429046
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429144
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429135
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429213
I/SELinux ( 5188): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5188):  
I/SELinux ( 5188):  
I/SELinux ( 5188): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5188): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 5188): >>>>> Normal User
E/dalvikvm( 5188): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
E/SELinux ( 5188): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429151
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429128
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429112
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429112
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/power_saving_mode
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131299843
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429112
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429112
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ModePreview
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429149
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429113
,D/TimaKeyStoreProvider( 5188): in addTimaSignatureService
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4920): Resource data:1
W/ResourceType( 4920): No package identifier when getting name for resource number 0x00000001
W/System.err( 4920): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 4920): 	at android.content.res.Resources.getResourceName(Resources.java:2988)
,W/System.err( 4920): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 4920): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 4920): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4920): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4920): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4920): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
D/TimaKeyStoreProvider( 5188): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429126
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
D/ActivityThread( 5188): Added TimaKesytore provider
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131301070
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297804
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429130
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429120
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429121
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429133
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131300118
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429123
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429187
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429124
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429218
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429155
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429126
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429126
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429126
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/pen_settings_menu
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429126
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/pen_settings_menu
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$OneHandEditMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429100
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429212
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/customizable_key
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429099
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131301505
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429130
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429130
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131302906
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429106
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2130838226
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4920): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429143
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429136
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429136
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429104
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429139
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429140
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429080
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131302078
D/dalvikvm( 5040): GC_FOR_ALLOC freed 1939K, 26% free 10513K/14052K, paused 43ms, total 51ms
I/dalvikvm-heap( 5040): Grow heap (frag case) to 11.839MB for 131088-byte allocation
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429080
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131302078
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429080
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131302107
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429086
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429044
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429049
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429122
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4920): Resource data:2131297804
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/display_settings
,I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429078
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429131
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429131
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_toolbox
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429122
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/smart_screen
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2130838278
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:drawable/ic_settings_torchlight
,I/AMMetaDataParserService( 4920): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2130838278
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:drawable/ic_settings_torchlight
,I/AMMetaDataParserService( 4920): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429129
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429129
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4920): Resource data:2131165371
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429051
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429114
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4920): Resource data:2131298587
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4920): getResourceTypeNamestring
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429125
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429185
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429147
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429147
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429203
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429203
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429075
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429169
,I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4920): Resource data:2131429138
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/festival_effect_settings
,I/AMMetaDataParserService( 4920): getResourceTypeNameid
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2130838226
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
,I/AMMetaDataParserService( 4920): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4920): Resource data:2131429119
I/AMMetaDataParserService( 4920): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 4920): getResourceTypeNameid
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,D/dalvikvm( 5188): GC_CONCURRENT freed 3002K, 32% free 9574K/14060K, paused 3ms+1ms, total 69ms
,D/dalvikvm( 5188): WAIT_FOR_CONCURRENT_GC blocked 64ms
,D/dalvikvm( 5040): GC_FOR_ALLOC freed 9K, 26% free 10632K/14184K, paused 66ms, total 66ms
E/KnoxSetupWizardClient( 5188): isShipMode : 1
,I/KnoxSetupWizardClient( 5188): onReceive : android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4920): Resource data:2131034120
,I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131034113
I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,I/System.out( 5040): pool-4-thread-1 calls detatch()
,D/ShortcutReceiver2( 5188):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 5188): setDisableWidget>size:0
,W/System.err( 5188): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 5188): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5188): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5188): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5188): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5188): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 5188): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/dalvikvm( 4998): GC_CONCURRENT freed 2363K, 28% free 10216K/14064K, paused 2ms+3ms, total 27ms
,W/System.err( 5188): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 5188): 	at android.os.Parcel.readException(Parcel.java:1469)
,W/System.err( 5188): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5188): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5188): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 5188): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
W/System.err( 5188): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 5188): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 5202): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5202):  
I/ActivityManager( 2423): Killing 4278:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 6 sec
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
I/SELinux ( 5202): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5202):  
I/SELinux ( 5202):  
,I/SELinux ( 5202): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5202): >>>>> Normal User
,E/dalvikvm( 5202): >>>>> com.LocalFota [ userId:0 | appId:10113 ]
,E/SELinux ( 5202): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5202): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5202): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5202): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131034113
I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/dalvikvm( 2423): GC_EXPLICIT freed 4053K, 19% free 24445K/30076K, paused 6ms+18ms, total 185ms
,I/AMMetaDataParserService( 4920): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4920): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4920): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131034112
I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/assistant_detail
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528
,D/dalvikvm( 5202): GC_CONCURRENT freed 3000K, 32% free 9573K/14060K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 5202): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528
,I/DBG_WSS_LF( 5202): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 5202): [20.0040.140326][Line:27][<init>] First call
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527
,D/dalvikvm( 4920): GC_CONCURRENT freed 2004K, 23% free 12278K/15768K, paused 2ms+4ms, total 43ms
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526
,I/DBG_WSS_LF( 5202): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_WSS_LF( 5202): [20.0040.140326][Line:31][onReceive] *** boot complete ***
,I/DBG_WSS_LF( 5202): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/DBG_WSS_LF( 5202): [20.0040.140326][Line:41][onReceive] nStatus : -1
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4920): Resource data:Lo,op for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131034113
I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,I/SELinux ( 5218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5218):  
I/ActivityManager( 2423): Killing 4333:com.fmm.dm/1000 (adj 15): empty #43
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,I/SELinux ( 5218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5218):  
I/SELinux ( 5218):  
,I/SELinux ( 5218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5218): >>>>> Normal User
,E/dalvikvm( 5218): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ]
,E/SELinux ( 5218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,D/TimaKeyStoreProvider( 5218): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5218): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5218): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,D/dalvikvm( 5218): GC_CONCURRENT freed 2992K, 32% free 9578K/14060K, paused 4ms+2ms, total 27ms
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4920): Resource data:2131034116
,D/dalvikvm( 5218): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/AMMetaDataParserService( 4920): getResourceName:com.android.contacts:xml/findo_searchable
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
,I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4920): Resource data:2131099668
,I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,I/AMMetaDataParserService( 4920): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 4920): Resource data:2131099650
,D/StatusChecker( 5218): onReceive : android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,I/SELinux ( 5232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5232):  
,I/ActivityManager( 2423): Killing 4317:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,I/SELinux ( 5232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5232):  
I/SELinux ( 5232):  
,I/SELinux ( 5232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5232): >>>>> Normal User
,E/dalvikvm( 5232): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10135 ]
,E/SELinux ( 5232): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5232): in addTimaSignatureService
,D/dalvikvm( 4920): GC_FOR_ALLOC freed 819K, 24% free 12018K/15812K, paused 34ms, total 34ms
,D/TimaKeyStoreProvider( 5232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5232): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4920): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserSe,rvice( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4920): Resource data:2131099667
,I/AMMetaDataParserService( 4920): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
,D/dalvikvm( 5232): GC_CONCURRENT freed 3015K, 33% free 9554K/14056K, paused 2ms+2ms, total 36ms
,D/dalvikvm( 5232): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,D/QuickConnect( 5232): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 5232): Utils.setQCRunningSetting - set : 0
,W/BackupManagerService( 2423): dataChanged but no participant pkg='com.android.providers.settings' uid=10135
I/QuickConnect( 5232): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
V/QuickConnect( 5232): SconnectManager.getInstance - () return existing instance null
W/ContextImpl( 5232): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,I/QuickConnect( 5232): PeriphService.onCreate - [START]
,D/        ( 4920): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4920): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558,
,I/SELinux ( 5244): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5244):  
,I/QuickConnect( 5232): PeriphService.onCreate - [START] USER_OWNER
,D/QuickConnect( 5232): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19
,I/QuickConnect( 5232): PeriphService.setProcessForeground - true of JB_MR2 complete 
I/QuickConnect( 5232): PeriphService.setState - 0 >> 1
,V/QuickConnect( 5232): PeriphService.runService - 
,I/QuickConnect[1.1][2] ( 5232): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@422d2d78
,I/QuickConnect[1.1][2] ( 5232): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@422bf270
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.registerBroadcast - --
,D/AmoledAdjustTimer( 2423): prevTemp = 310, currTemp = 312, prevStep = 4, currStep = 4
D/QuickConnect[1.1][2] ( 5232): SconnectManager.SconnectManager - REQUEST_ID :  1
D/QuickConnect[1.1][2] ( 5232): ScanThread.ScanThread - created!
V/QuickConnect[1.1][2] ( 5232): BluetoothHelper.BluetoothHelper - 
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,I/SELinux ( 5244): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5244):  
I/SELinux ( 5244):  
,I/SELinux ( 5244): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5244): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5244): >>>>> Normal User
,E/dalvikvm( 5244): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 5244): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5232): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,V/QuickConnect[1.1][2] ( 5232): BleHelper.BleHelper - Constructor
,D/TimaKeyStoreProvider( 5244): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5244): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5244): Added TimaKesytore provider
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 7 sec
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
E/QuickConnect[1.1][2] ( 5232): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
D/BluetoothRadioManager( 5232): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@422e5608
D/BluetoothRadioManager( 5232):  addRadioReference enabled = false
D/BluetoothRadioManager( 5232):  BLE Radio count is : 1
D/BluetoothRadioManager( 5232): addRadioReference()  registerRadioClient mUUID = 3b7fb5b0-5418-4a93-ab25-c0c434626597
D/BluetoothManagerService( 2423): foregroundUser: 0
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
,E/BluetoothManagerService( 2423): Package is exist.
,D/BluetoothRadioManager( 5232): addLeRadioReference: isRadioEnabled() =  false
,V/QuickConnect[1.1][2] ( 5232): BleHelper.mSearchWearable - true
,I/bluedroid( 4000): update_radio_count
,D/BluetoothAdapterState( 4000): CURRENT_STATE=ON, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 4000): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
,D/BluetoothAdapterState( 4000): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 4000): enable
,E/bt-btif ( 4000): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 4000): btif_sock_init, radio_req:1, rfc_init:1, vhci_init:1
,D/BluetoothAdapterState( 4000): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
I/BluetoothAdapterState( 4000): Bluetooth adapter radio state changed: 14
,D/BluetoothAdapterService( 4000): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4000): updateAdapterState state is 14
,D/BluetoothAdapterService( 4000): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 4000): Autoconnection is available 
D/BluetoothManagerService( 2423): Broadcasting Radio() to 1 Radio Mgr receivers.
,D/BluetoothRadioManager( 5232): onBTRadioStateChange:  up = true
,D/BluetoothAdapterService( 4000): updateAdapterState prevState = 12newState = 14
,I/BluetoothAdapterState( 4000): Entering On State from state = 12
,D/dalvikvm( 5244): GC_CONCURRENT freed 3000K, 32% free 9567K/14052K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 5244): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/        ( 4920): PNG_doEncode true 106, 106
,E/QuickConnect[1.1][2] ( 5232): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@423386b8
,I/AMMetaDataParserService( 4920): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
D/BezelQuickConnect( 5244): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
D/BezelQuickConnect( 5244): BezelBroadcastReceiver - StartBezelInteractionService
,E/QuickConnect[1.1][2] ( 5232): BleHelper.onGattServiceStateChange - Radio turned on
,V/QuickConnect[1.1][2] ( 5232): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 5232): JmdnsHelper.JmdnsHelper - Constructor
,D/BezelQuickConnect( 5244): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,V/QuickConnect[1.1][2] ( 5232): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 5232): p2pHelperWorkThread.p2pHelperWorkThread - created!
,I/BezelQuickConnect( 5244): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
,D/BezelQuickConnect( 5244): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,W/ContextImpl( 5244): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
V/PhoneStatusBar( 2583): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
,E/NetworkSettingsReceiver( 3278): onReceive: android.intent.action.BOOT_COMPLETED
,D/STATUSBAR-PhoneStatusBar( 2583): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
D/QuickConnect[1.1][2] ( 5232): WifiHelper.WifiHelper -  -- 
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4920): Resource data:2131099689
I/AMMetaDataParserService( 4920): getResourceName:com.android.email:xml/spellscroll
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4920): Resource data:2131099685
I/AMMetaDataParserService( 4920): getResourceName:com.android.email:xml/searchable
I/AMMetaDataParserService( 4920): getResourceTypeNamexml
I/AMMetaDataParserService( 4920): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4920): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4920): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 4920): Resource data:2130903052
,D/WifiDisplayAdapter( 2423): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/QuickConnect[1.1][2] ( 5232): CentralActionManager.CentralActionManager - EXEC
V/QuickConnect[1.1][2] ( 5232): BluetoothOppActionHelper.BluetoothOppActionHelper - 
V/QuickConnect[1.1][2] ( 5232): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
V/QuickConnect[1.1][2] ( 5232): SmartHomeActionHelper.SmartHomeActionHelper - --
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
V/QuickConnect[1.1][2] ( 5232): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
I/AMMetaDataParserService( 4920): getResourceTypeNamelayout
I/AMMetaDataParserService( 4920): getResourcePackageName:assistant
I/AMMetaDataParserService( 4920): Resource data:2131034112
V/QuickConnect[1.1][2] ( 5232): BluetoothActionHelper.BluetoothActionHelper - 
I/AMMetaDataParserService( 4920): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 4920): getResourceTypeNamexml
W/BroadcastQueue( 2423): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/SELinux ( 5261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5261):  
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,E/BluetoothHeadset( 5232): BTStateChangeCB is registed
,E/BluetoothHeadset( 5232): BluetoothHeadset service is binded
,I/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@422d4a10
,V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
V/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.setVisibilityFromSystemDb - --
,D/QuickConnect[1.1][2] ( 5232): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 5232): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
D/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
D/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
,D/QuickConnect[1.1][2] ( 5232): WifiHelper.isEnableMobileAP - HOTSPOT Disabled
I/SELinux ( 5261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5261):  
I/SELinux ( 5261):  
,I/SELinux ( 5261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5261): >>>>> Normal User
E/dalvikvm( 5261): >>>>> com.sec.android.app.camera [ userId:0 | appId:10149 ]
,V/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.updateRespTarget - 
,E/SELinux ( 5261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.initializeAdvData - 
V/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.initializeAdvData - name: S5mini-1(8)
D/QuickConnect[1.1][2] ( 5232): PreDiscoveryHelper.initializeAdvData - name selected: S5mini-1(8)
,V/QuickConnect[1.1][2] ( 5232): CONTACT_Info.getMyMobileNumber - 
,D/        ( 4920): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4920): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,D/TimaKeyStoreProvider( 5261): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5261): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5261): Added TimaKesytore provider
D/QuickConnect[1.1][2] ( 5232): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5232): CONTACT_Info.getMyMobileNumber - null 
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 4920): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,D/QuickConnect[1.1][2] ( 5232): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
,I/ActivityManager( 2423): Killing 4368:com.samsung.klmsagent/u0a18 (adj 15): empty #43
W/QuickConnect[1.1][2] ( 5232): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
D/QuickConnect[1.1][2] ( 5232): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
D/QuickConnect[1.1][2] ( 5232): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5232): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
D/QuickConnect[1.1][2] ( 5232): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5232): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
D/QuickConnect[1.1][2] ( 5232): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
D/QuickConnect[1.1][2] ( 5232): PeriphService.registerUserReceiver - mIsUserReceiver == false
I/QuickConnect[1.1][2] ( 5232): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 5232): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
I/QuickConnect[1.1][2] ( 5232): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
D/QuickConnect[1.1][2] ( 5232): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/QuickConnect[1.1][2] ( 5232): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/BluetoothA2dp( 5232): Proxy object connected
,D/QuickConnect[1.1][2] ( 5232): A2dpProfile.onServiceConnected - Bluetooth service connected
D/WifiP2pService( 2423): InactiveState{ what=139287 }
D/WifiP2pService( 2423): P2pEnabledState{ what=139287 }
D/WifiP2pService( 2423): DefaultState{ what=139287 }
,D/QuickConnect[1.1][2] ( 5232): HeadsetProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothInputDevice( 5232): Proxy object connected
,D/QuickConnect[1.1][2] ( 5232): HidProfile.onServiceConnected - Bluetooth service connected
,D/QuickConnect[1.1][2] ( 5232): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/dalvikvm( 5261): GC_CONCURRENT freed 3009K, 32% free 9558K/14052K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 5261): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/dalvikvm( 5261): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,I/ActivityManager( 2423): Killing 4347:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5275):  
,I/QuickConnect[1.1][2] ( 5232): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 5232): registerCallback()
,D/BluetoothGattServer( 5232): registerCallback() - UUID=938042e7-bd73-4b67-8359-4bbcf337ca31
,D/BtGatt.GattService( 4000): registerServer() - UUID=938042e7-bd73-4b67-8359-4bbcf337ca31
D/BtGatt.btif( 4000): btif_gatts_register_app
,D/BtGatt.btif( 4000): btgatts_handle_event: Event 2000
E/bt-btif ( 4000): register application first_unuse rcb_idx = 0
D/BtGatt.btif( 4000): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 4000): onServerRegistered() - UUID=938042e7-bd73-4b67-8359-4bbcf337ca31, serverIf=5
,D/BluetoothGattServer( 5232): onServerRegistered() - status=0 serverIf=5
V/QuickConnect[1.1][2] ( 5232): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5232): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
,V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
V/QuickConnect[1.1][2] ( 5232): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
V/QuickConnect[1.1][2] ( 5232): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422d4a10
,D/QuickConnect[1.1][2] ( 5232): BleHelper.startScan - propDisableScan = 0
,D/QuickConnect[1.1][2] ( 5232): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5232): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5232): BleHelper.startScan - shouldScanBleFg = false
,I/SELinux ( 5275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5275):  
I/SELinux ( 5275):  
,I/SELinux ( 5275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5275): >>>>> Normal User
,E/dalvikvm( 5275): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 5275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5275): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5275): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5275): Added TimaKesytore provider
,D/dalvikvm( 5275): GC_CONCURRENT freed 2988K, 32% free 9572K/14052K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 5275): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,I/ActivityManager( 2423): Waited long enough for: ServiceRecord{42db1860 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/BadgeProvider( 4744): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2784): reloadBadges entered.
D/BadgeProvider( 4744): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4744): sendNotify, [notify] : null
D/BadgeProvider( 4744): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4744): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4744): update, [UpdateCount] : 1
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,W/ActivityManager( 2423): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5299): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5299):  
I/ActivityManager( 2423): Killing 4383:com.sec.android.app.mss/u0a21 (adj 15): empty #43
I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 8 sec
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,D/dalvikvm( 1924): GC_EXPLICIT freed 44K, 14% free 9503K/11036K, paused 3ms+5ms, total 43ms
W/ActivityManager( 2423): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5299): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5299):  
I/SELinux ( 5299):  
,I/SELinux ( 5299): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5299): >>>>> Normal User
,E/dalvikvm( 5299): >>>>> com.android.exchange [ userId:0 | appId:10158 ]
,E/SELinux ( 5299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 3ms+3ms, total 33ms
,D/TimaKeyStoreProvider( 5299): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5299): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5299): Added TimaKesytore provider
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 2ms+3ms, total 26ms
,I/Process ( 5275): Sending signal. PID: 5275 SIG: 9
,I/ActivityManager( 2423): Process com.android.email (pid 5275) (adj 9) has died.
,D/dalvikvm( 5299): GC_CONCURRENT freed 3006K, 32% free 9562K/14056K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 5299): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/SensorService( 2423):   0.3 0.0 9.9
V/AlarmManager( 2423): waitForAlarm result :4
V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2423): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 5315): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5315):  
,I/SELinux ( 5319): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5319):  
,I/SELinux ( 5315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5315):  
I/SELinux ( 5315):  
,I/SELinux ( 5315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5315): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5315): >>>>> Normal User
,E/dalvikvm( 5315): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 5315): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 5319): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5319):  
I/SELinux ( 5319):  
,I/SELinux ( 5319): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5319): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5319): >>>>> Normal User
,E/dalvikvm( 5319): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 5319): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5315): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5315): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5315): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 5319): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5319): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5319): Added TimaKesytore provider
,I/ActivityManager( 2423): Killing 4397:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,D/dalvikvm( 2725): GC_EXPLICIT freed 933K, 29% free 9983K/14044K, paused 7ms+7ms, total 78ms
,I/iu.UploadsManager( 3155): End new media; added: 0, uploading: 0, time: 234 ms
,D/dalvikvm( 5315): GC_CONCURRENT freed 2990K, 32% free 9580K/14060K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 5315): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 5319): GC_CONCURRENT freed 2987K, 32% free 9587K/14060K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 5319): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/SELinux ( 5341): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5341):  
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,I/ActivityManager( 2423): Killing 4411:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,I/SELinux ( 5341): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5341):  
I/SELinux ( 5341):  
,I/SELinux ( 5341): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5341): >>>>> Normal User
,E/dalvikvm( 5341): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5341): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5341): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5341): Added TimaKesytore provider
,I/Process ( 5299): Sending signal. PID: 5299 SIG: 9
,I/ActivityManager( 2423): Process com.android.exchange (pid 5299) (adj 9) has died.
,D/BadgeProvider( 4744): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2784): reloadBadges entered.
,D/BadgeProvider( 4744): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4744): sendNotify, [notify] : null
D/BadgeProvider( 4744): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4744): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4744): update, [UpdateCount] : 1
,D/dalvikvm( 5341): GC_CONCURRENT freed 2996K, 32% free 9573K/14060K, paused 13ms+2ms, total 40ms
,D/dalvikvm( 5341): WAIT_FOR_CONCURRENT_GC blocked 20ms,
,D/RCPManagerService( 2423): exchangeData() failure , invalid userId
,I/SELinux ( 5360): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5360):  
,W/ActivityManager( 2423): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5360): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5360):  
I/SELinux ( 5360):  
,I/SELinux ( 5360): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5360): >>>>> Normal User
,E/dalvikvm( 5360): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ],
,E/SELinux ( 5360): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5360): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5360): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5360): Added TimaKesytore provider,
,D/dalvikvm( 5360): GC_CONCURRENT freed 3002K, 32% free 9567K/14056K, paused 3ms+2ms, total 25ms,
,D/dalvikvm( 5360): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/NotiRemoteService( 5360): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 5360): connectToPeelService 0,
,W/ContextImpl( 5360): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:68 tv.peel.samsung.widget.NotiRemoteService.a:554 
,I/SELinux ( 5379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5379):  
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 9 sec,
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false,
,D/NotiRemoteService( 5360): onServiceOn() mServiceState = 1,
,D/NotiRemoteService( 5360): Send action to self com.peel.widget.notification.SERVICE_BINDED,
D/NotiRemoteService( 5360): action com.peel.widget.notification.SERVICE_BINDED,
D/NotiRemoteService( 5360): feature is Off. Stop service
,D/NotiRemoteService( 5360): Send action to self com.peel.widget.notification.STOP_PROCESS,
,D/NotiRemoteService( 5360): action com.peel.widget.notification.STOP_PROCESS,
,D/NotiRemoteService( 5360): onDestroy(),
,D/NotiRemoteService( 5360): mOrientationChangeReceier was not registered,
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5379):  
I/SELinux ( 5379):  
,I/SELinux ( 5379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5379): >>>>> Normal User
,E/dalvikvm( 5379): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 5379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5379): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5379): Added TimaKesytore provider
,D/dalvikvm( 5379): GC_CONCURRENT freed 3006K, 32% free 9568K/14060K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 5379): WAIT_FOR_CONCURRENT_GC blocked 20ms
,V/SmartcardService( 5379): main Received broadcast
,V/SmartcardService( 5379): Starting smartcard service after boot completed
I/ActivityManager( 2423): Killing 4299:com.android.chrome/u0a85 (adj 15): empty #43
,I/SELinux ( 5392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5392):  
,I/SELinux ( 5392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5392):  
I/SELinux ( 5392):  
,I/SELinux ( 5392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5392): >>>>> Normal User
,E/dalvikvm( 5392): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5392): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5392): Added TimaKesytore provider
,D/dalvikvm( 5392): GC_CONCURRENT freed 2998K, 32% free 9570K/14056K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 5392): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/ContextImpl( 5392): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5405):  
,I/SELinux ( 5405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5405):  
I/SELinux ( 5405):  
,I/SELinux ( 5405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5405): >>>>> Normal User
,E/dalvikvm( 5405): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
D/PowerManagerService( 2423): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 2423): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2423): [s] mDisplayPowerControllerCallbacks : onStateChanged()
E/SELinux ( 5405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/lights  ( 2423): lcd : 2 +
D/RampAnimator( 2423): Light Animator Finished currentValue=2
,D/TimaKeyStoreProvider( 5405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5405): Added TimaKesytore provider
,D/lights  ( 2423): lcd : 2 -
,D/dalvikvm( 5405): GC_CONCURRENT freed 2989K, 32% free 9578K/14056K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 5405): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/SELinux ( 5419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5419):  
I/ActivityManager( 2423): Killing 4427:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
,I/SELinux ( 5419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5419):  
I/SELinux ( 5419):  
,I/SELinux ( 5419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5419): >>>>> Normal User
,E/dalvikvm( 5419): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 5419): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5419): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5419): Added TimaKesytore provider
,D/dalvikvm( 2423): GC_EXPLICIT freed 1255K, 20% free 24323K/30076K, paused 7ms+15ms, total 192ms
,D/dalvikvm( 5419): GC_CONCURRENT freed 3000K, 32% free 9570K/14056K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 5419): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 10 sec
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/Intent to TravelDirActivity( 5419): inside TravelBroadcastReceiver
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 5432): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5432):  
I/ActivityManager( 2423): Killing 4442:com.sec.pcw.device/1000 (adj 15): empty #43
,D/BluetoothAdapterService(1110141104)( 4000): unRegister RemoteMessageListener
,D/HeadsetService( 4000): registerMessageListener
D/HeadsetStateMachine( 4000): Disconnected process message: 80
,D/HeadsetStateMachine( 4000): processUnRegisterMessageListener : 2
D/BluetoothAdapterState( 4000): CURRENT_STATE=ON, MSG = USER_TURN_OFF
I/BluetoothAdapterState( 4000): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 4000): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 4000): updateAdapterState state is 13
,I/WifiManager( 4998): packageName : com.example.hello
I/WifiManager( 4998): setWifiEnabled : false
,I/BluetoothPbapService( 4000): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterService( 4000): Broadcasting updateAdapterState() to 1 receivers.
,I/WifiService( 2423): setWifiEnabled: false pid=4998, uid=10495
D/BluetoothAdapterService( 4000): Autoconnection is available 
D/BluetoothAdapterService( 4000): updateAdapterState prevState = 12newState = 13
,D/BluetoothAdapterService( 4000): terminating service from this receiver
W/ContextImpl( 4000): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.stopService:511 com.android.bluetooth.btservice.AdapterService.updateAdapterState:657 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,E/bt-btif ( 4000): bta_jv_rfcomm_stop_server
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BluetoothAdapterState( 4000): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
W/InputMethodManagerService( 2423): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2423): [BT Setting State] State =13
I/GAV2    ( 5132): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 5432): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5432):  
I/SELinux ( 5432):  
,I/SELinux ( 5432): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/PhoneApp( 2756): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 13
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5432): >>>>> Normal User
E/dalvikvm( 5432): >>>>> com.sec.android.daemonapp [ userId:0 | appId:10173 ]
I/wpa_supplicant( 3974): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3974): wlan0: Setting scan request: 0 sec 0 usec
,I/SamsungIME( 3007): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
I/jxcore-log( 4998): ****TEST TOOK:  5187  ms ****
I/jxcore-log( 4998): 
,W/Settings( 2423): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2423): ignore requestNetworkTransitionWakelock airplane:true
,E/SELinux ( 5432): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/jxcore-log( 4998): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4998): 
,D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:2
I/wpa_supplicant( 3974): Scan requested (ret=0) - scan timeout 30 seconds
D/BluetoothAdapterState( 4000): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/QuickConnect[1.1][2] ( 5232): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_OFF
E/bt-btif ( 4000): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/WifiP2pService( 2423): InactiveState{ what=143375 }
,D/WifiP2pService( 2423): P2pEnabledState{ what=143375 }
E/bt-btif ( 4000): bta_jv_rfcomm_stop_server
E/bt-btif ( 4000): cmd socket is not created
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/CommandListener( 1917): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2423): evaluateTrafficStatsPolling
D/ConnectivityService( 2423): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2423): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2423): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2423): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2423): net.tcp.delack.default not found in system default properties
D/IOP_DB_BT( 4000): db_close: nbr users 0
,D/IOP_DB_BT( 4000): db_close: free database
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2423): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,D/TimaKeyStoreProvider( 5432): in addTimaSignatureService
D/ConnectivityService( 2423): Attempting to switch to mobile
,D/ConnectivityService( 2423): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService( 2423): InactiveState{ what=131204 }
D/WifiP2pService( 2423): P2pEnabledState{ what=131204 }
D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:2
,E/WifiStateMachine( 2423): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,D/WifiP2pService( 2423): sending p2p connection changed broadcast: FAILED
E/WifiStateMachine( 2423): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 5432): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5432): Added TimaKesytore provider
W/WifiP2pStateTracker( 2423): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2423): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiDisplayAdapter( 2423): onP2pDisconnected
D/IpRemoteDisplayController( 2423): disconnectWfdBridgeServer
,D/IpRemoteDisplayController( 2423): WfdBridgeServer is already null
D/QuickConnect[1.1][2] ( 5232): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,E/WifiStateMachine( 2423): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 2423): sending p2p connection changed broadcast: DISCONNECTED
,V/RouteController( 1917): /system/bin/ip -6 route del default table 2 2>&1
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.INetworkStateListener, onDisabled - mNetworkState : 0
D/WifiDisplayController( 2423): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 2423): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2423): disconnect
D/WifiDisplayController( 2423): updateConnection
D/WifiDisplayController( 2423): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2423): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/QuickConnect[1.1][2] ( 5232): P2pHelper.cancelConnectPeer -  mTargetList clear all 
D/QuickConnect[1.1][2] ( 5232): P2pHelper.removeP2pConfirm - skip: false
D/QuickConnect[1.1][2] ( 5232): CentralActionManager.removeHoldingIntentAll - all request done.
,D/WifiP2pService( 2423): P2pDisablingState
,D/WifiP2pService( 2423): P2pDisablingState{ what=147458 }
,V/RouteController( 1917): RTNETLINK answers: No such process
,V/RouteController( 1917): /system/bin/ip -6 rule del table 2 2>&1,
D/WifiP2pService( 2423): p2p socket connection lost
D/QuickConnect[1.1][2] ( 5232): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 5232): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null,
D/WifiDisplayAdapter( 2423): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/WifiP2pService( 2423): P2pDisabledState,
D/WifiP2pService( 2423): P2pDisabledState{ what=139287 }
D/WifiP2pService( 2423): DefaultState{ what=139287 }
D/WifiP2pService( 2423): P2pDisabledState{ what=139376 },
D/WifiP2pService( 2423): DefaultState{ what=139376 }
W/WifiP2pStateTracker( 2423): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2423): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false
,D/WifiDisplayAdapter( 2423): onP2pDisconnected
D/IpRemoteDisplayController( 2423): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 2423): WfdBridgeServer is already null
,E/WifiP2pService( 2423): Unhandled message { what=139376 },
V/RouteController( 1917): RTNETLINK answers: No such file or directory,
D/CommandListener( 1917): Clearing all IP addresses on wlan0
D/QuickConnect[1.1][2] ( 5232): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
D/WifiP2pService( 2423): P2pDisabledState{ what=139287 }
,D/WifiP2pService( 2423): DefaultState{ what=139287 },
D/QuickConnect[1.1][2] ( 5232): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
W/NetworkManagementService( 2423): route cmd failed: ,
W/NetworkManagementService( 2423): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '33 route del src v6 2' failed with '400 33 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2423): '
W/NetworkManagementService( 2423): 	,at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2423): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2423): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2423): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2423): ,	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2423): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2423): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2423): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
,W/NetworkManagementService( 2423): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2423): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2423): 	at android.os.Looper.loop(Looper.java:146),
W/NetworkManagementService( 2423): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/RouteController( 1917): /system/bin/ip -4 route del default table 2 2>&1
D/WifiNative( 2423): callSECApiBoolean - ID [13]
I/WifiTrafficPoller( 2423): evaluateTrafficStatsPolling
I/wpa_supplicant( 3974): USE_NETWORK : USE_NETWORK OFF
V/RouteController( 1917): RTNETLINK answers: No such process,
,V/RouteController( 1917): /system/bin/ip -4 rule del table 2 2>&1,
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
V/RouteController( 1917): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2423): android_net_utils_resetConnections in env=0x784f8600 clazz=0x4e700001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2423): resetConnections(wlan0, 3)
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false,
E/WifiStateMachine( 2423): Error! unhandled message{ when=-20ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2423): Error! unhandled message{ when=-20ms what=135191 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2423): Error! unhandled message{ when=-3ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2423): Error! unhandled message{ when=-2ms what=135191 target=com.android.internal.util.StateMachine$SmHandler },
,D/BluetoothAdapterState( 4000): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
D/BtConfig.SecureMode( 4000): isSecureModeOn:false
W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4000): Skipping to stop Quiet mode profile com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.hfp.HeadsetService,
W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,D/HeadsetService( 4000): Received stop request...Stopping profile...
,D/QuickConnect[1.1][2] ( 5232): HeadsetProfile.onServiceDisconnected - Bluetooth service disconnected
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 4000): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 4000): check For Quiet mode profile 10 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 4000): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterState( 4000): Stopping profile services that were post enabled
D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
D/dalvikvm( 5432): GC_CONCURRENT freed 2990K, 32% free 9579K/14060K, paused 5ms+2ms, total 47ms
,D/dalvikvm( 5432): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/BluetoothHeadsetServiceJni( 4000): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 4000): Cleaning up Bluetooth Handsfree callback object
,D/A2dpService( 4000): Received stop request...Stopping profile...
,D/MediaFocusControl( 2423): <<< unregisterRemoteControlDisplay
,D/A2dpStateMachine( 4000): Exit Disconnected: -1
,D/Avrcp   ( 4000): Unregistering previous receiver
D/BluetoothA2dp( 5232): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5232): A2dpProfile.onServiceConnected - Bluetooth service disconnected
I/wpa_supplicant( 3974): p2p0: CTRL-EVENT-TERMINATING 
,D/BluetoothA2dp( 2423): Proxy object disconnected
,D/Tethering( 2423): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2423): interfaceStatusChanged p2p0, true
,D/Tethering( 2423): interfaceLinkStateChanged p2p0, false
,D/Tethering( 2423): interfaceStatusChanged p2p0, false
,D/HidService( 4000): Received stop request...Stopping profile...
,D/HidService( 4000): Stopping Bluetooth HidService
D/BluetoothInputDevice( 5232): Proxy object disconnected
,D/QuickConnect[1.1][2] ( 5232): HidProfile.onServiceDisconnected - Bluetooth service disconnected
,D/HealthService( 4000): Received stop request...Stopping profile...
,D/PanService( 4000): Received stop request...Stopping profile...
,D/BluetoothPan( 2423): BluetoothPAN Proxy object disconnected
,I/wpa_supplicant( 3974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/BluetoothMapService( 4000): Received stop request...Stopping profile...
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2423): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2423): interfaceStatusChanged wlan0, true
,D/comsamsungapp( 5432): [MSC_Daemon]>>> KWCP:218 [0:0] KWeather Provider Created
,D/comsamsungapp( 5432): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/Tethering( 2423): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2423): interfaceStatusChanged wlan0, true
D/SapService( 4000): Received stop request...Stopping profile...
,D/SapService( 4000): Stopping Bluetooth SapService
,D/BluetoothA2dp( 4170): Proxy object disconnected
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
,I/GKI_LINUX( 4000): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 4000): GKI_exit_task: GKI_exit_task 2 done
,I/GKI_LINUX( 4000): GKI_destroy_task: GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
W/BluetoothHidServiceJni( 4000): Cleaning up Bluetooth HID Interface...
,W/BluetoothHidServiceJni( 4000): Cleaning up Bluetooth GID callback object
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
,W/BluetoothHealthServiceJni( 4000): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 4000): Cleaning up Bluetooth Health object
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 4000): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 4000): Cleaning up Bluetooth PAN callback object
,D/BtSettings.ProfileConfig( 4000): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Profile still running: com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 4000): Quiet mode profile com.android.bluetooth.gatt.GattService running since Radio Cnt > 0. 
D/BluetoothAdapterState( 4000): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,I/BluetoothAdapterState( 4000): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 4000): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 4000): updateAdapterState state is 10
,D/BluetoothAdapterService( 4000): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 4000): Autoconnection is available 
,D/BluetoothInputDevice( 5232): onBluetoothStateChange: up=false
D/BluetoothAdapterService( 4000): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 4000): Entering OffState
,W/BluetoothSAPServiceJni( 4000): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,W/BluetoothSAPServiceJni( 4000): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,D/BluetoothA2dp( 5232): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 2423): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 4170): onBluetoothStateChange: up=false
,W/InputMethodManagerService( 2423): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2423): [BT Setting State] State =10
,D/PhoneApp( 2756): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 10
,I/SamsungIME( 3007): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/InputMethodManagerService( 2423): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
I/QuickConnect[1.1][2] ( 5232): BluetoothHelper.ACTION_STATE_CHANGED - STATE_OFF
D/comsamsungapp( 5432): [MSC_Daemon]>>> WCP:1080 [0:0] Provider Created
,D/comsamsungapp( 5432): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5432): [MSC_Daemon]>>> CCP:223 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 5432): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5432): [MSC_Daemon]>>> WNCP:204 [0:0] WeatherNewsJP Provider Created
,D/comsamsungapp( 5432): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/BluetoothTethering( 2423): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering( 2423): attempted to stop reverse tether with nothing tethered
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
V/NetworkStats( 2423): updateIfacesLocked()
V/NetworkStats( 2423): performPollLocked(flags=0x1)
,V/NetworkStats( 2423): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/Tethering( 2423): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2423): interfaceStatusChanged wlan0, true
D/comsamsungapp( 5432): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/comsamsungapp( 5432): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
V/NetworkStats( 2423): performPollLocked() took 19ms
,D/comsamsungapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/AndroidRuntime( 5448): 
D/AndroidRuntime( 5448): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5448): CheckJNI is OFF
,D/AndroidRuntime( 5448): setted country_code = Poland
,D/AndroidRuntime( 5448): setted countryiso_code = PL
D/AndroidRuntime( 5448): setted sales_code = PLS
D/AndroidRuntime( 5448): readGMSProperty: start
,D/AndroidRuntime( 5448): readGMSProperty: already setted!!
D/AndroidRuntime( 5448): readGMSProperty: end
D/AndroidRuntime( 5448): addProductProperty: start
,D/comsamsungapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/comsamsungapp( 5432): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:false
D/comsamsunglog( 5432): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5432): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5432): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5432): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5432): [MSC_Daemon]>>> WDSM:48 [0:0] WeatherClockService start : 
,D/daemonapp( 5432): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5432): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,D/dalvikvm( 5448): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5448): Added shared lib libjavacore.so 0x0
,W/BackupManagerService( 2423): dataChanged but no participant pkg='com.android.providers.settings' uid=10173
D/daemonapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/dalvikvm( 5448): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5448): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5448): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/daemonapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
I/wpa_supplicant( 3974): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering( 2423): interfaceLinkStateChanged wlan0, false
D/Tethering( 2423): interfaceStatusChanged wlan0, false
,D/Tethering( 2423): InitialState.processMessage what=4
,I/ConnectivityService( 2423): defaultVal : 1, tetherEnabledInSettings : true
,E/Tethering( 2423): No numeric data
,V/NetworkStats( 2423): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
D/daemonapp( 5432): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1449078431891
D/Tethering( 2423): sendTetherStateChangedBroadcast 0, 0, 0
D/daemonapp( 5432): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1449078060000
D/daemonapp( 5432): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 5432): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :false
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1567 [0:0] CnclAtRftAl
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1633 [0:0] [setARfAam]now :1449078431916
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1635 [0:0] [setARfAam]LUT :144907843191621600000
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1637 [0:0] [setARfAam]interval       :3
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1639 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1422 [0:0] util getnext by config 1449100020000
,V/NetworkStats( 2423): performPollLocked() took 18ms
D/daemonapp( 5432): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1449100020000
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
D/NtpTrustedTime( 2423): currentTimeMillis() cache hit
,D/daemonapp( 5432): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 9
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:1644 [0:0] [dbset]NT       :1449100020000
,D/daemonapp( 5432): [MSC_Daemon]>>> WCS:40 [0:0] onStartcommand()
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5432): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5432): [MSC_Daemon]>>> WCS:63 [0:0] CP Name cp_eng
,D/daemonapp( 5432): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5432): [MSC_Daemon]>>> WCS:82 [0:0] td null
,D/comdaemonstockapp( 5432): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 5432): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 5470): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5470):  
,D/WifiStateMachine( 2423): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/Settings( 2738): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/memtrack( 5448): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5448): failed to load memtrack module: -2
,I/SELinux ( 5470): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5470):  
I/SELinux ( 5470):  
,I/SELinux ( 5470): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5470): >>>>> Normal User
,E/dalvikvm( 5470): >>>>> com.gameloft.android.GloftGF2H [ userId:0 | appId:10179 ]
,E/SELinux ( 5470): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/dalvikvm( 5448): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/TimaKeyStoreProvider( 5470): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5470): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5470): Added TimaKesytore provider
,D/AndroidRuntime( 5448): Calling main entry com.android.commands.pm.Pm
,D/dalvikvm( 5470): GC_CONCURRENT freed 3011K, 33% free 9557K/14056K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 5470): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/PackageManager( 2423): START PACKAGE DELETE: observer{1124151424}
D/PackageManager( 2423): pkg{<packageName>}
D/PackageManager( 2423): user{0}
,D/PackageManager( 2423): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 2423): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2423): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2423): deletePackageX- pkg:com.example.hello, userId:0
D/PackageManager( 2423): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2423): !@killApplicatoin: 10495, uninstall pkg
,I/SELinux ( 5485): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5485):  
I/ActivityManager( 2423): Killing 4998:com.example.hello/u0a495 (adj 0): stop com.example.hello
,D/WifiStateMachine( 2423): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,I/SurfaceFlinger( 1923): id=17 Removed NainActivit (8/9)
,D/dalvikvm( 1924): GC_EXPLICIT freed 43K, 14% free 9503K/11036K, paused 3ms+3ms, total 32ms
I/SurfaceFlinger( 1923): id=17 Removed NainActivit (-2/9)
,I/SurfaceFlinger( 1923): id=17 Removed NainActivit (-2/9)
,I/WindowState( 2423): WIN DEATH: Window{43321d00 u0 com.example.hello/com.example.hello.MainActivity}
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 5485): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5485):  
I/SELinux ( 5485):  
I/SELinux ( 5485): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5485): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5485): >>>>> Normal User
E/dalvikvm( 5485): >>>>> com.gameloft.android.GloftKLMF [ userId:0 | appId:10180 ]
E/SELinux ( 5485): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 5485): in addTimaSignatureService
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 3ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 5485): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5485): Added TimaKesytore provider
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 11 sec
,D/dalvikvm( 1924): GC_EXPLICIT freed <1K, 14% free 9503K/11036K, paused 2ms+3ms, total 24ms
,W/PackageSettings( 2423): Skipping PackageSetting{42b39b30 com.test.thalitest/10494} due to missing metadata
,D/PackageManager( 2423): queryIntentReceivers - Execution time: 142 ms
,I/SurfaceFlinger( 1923): id=15 Removed EimLayer (6/8)
I/SurfaceFlinger( 1923): id=14 Removed EimLayer (5/7)
I/SurfaceFlinger( 1923): id=15 Removed EimLayer (-2/7)
,I/SurfaceFlinger( 1923): id=14 Removed EimLayer (-2/7)
W/ActivityManager( 2423): Force removing ActivityRecord{4317e498 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,D/PackageManager( 2423): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10495, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/SQLiteSecureOpenHelper( 4170): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4170): getDatabaseLocked(b,b,pwd)...
,I/ActivityManager( 2423): Killing 4468:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2423): mDVFSHelper.acquire()
,V/WindowOrientationListener( 2423): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 2423): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2423): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/PackageManager( 2423): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10495, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Launcher( 2784): onRestart, Launcher: 1110394456
D/Launcher( 2784): onStart, Launcher: 1110394456
,D/Launcher.HomeView( 2784): onStart
,I/ApplicationPolicy( 2423): updateDataUsageMap
,D/Launcher( 2784): onResume, Launcher: 1110394456
,D/Tethering( 2423): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2423): MasterInitialState.processMessage what=3
,D/StatusBarManagerService( 2423): semi p:2784,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/CaptivePortalTracker( 2423): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2423): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/Launcher.HomeView( 2784): onResume
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
D/StatusBarManagerService( 2423): tr p:2784,o:f
D/StatusBarManagerService( 2423): semi p:2784,o:f
,I/DBG_DM  ( 4778): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 2957): GC_EXPLICIT freed 1047K, 29% free 10012K/14048K, paused 4ms+6ms, total 68ms
,E/SamsungIME( 3007): mOCRHelper is null
,I/InputReader( 2423): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 5232): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 5485): GC_CONCURRENT freed 3005K, 32% free 9569K/14060K, paused 2ms+19ms, total 82ms
,D/dalvikvm( 5485): WAIT_FOR_CONCURRENT_GC blocked 79ms
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "sms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2423): PackageReceiver onReceive()
,I/HarmonyEASService( 2423): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2423):   Scheme: "smsto"
,D/MenuAppsGridFragment( 2784): onResume
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "mms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SurfaceFlinger( 1923): id=18 createSurf (720x1280),1 flag=4, Mauncher
,D/libgps  ( 2423): agps_ril_update_network_state: Waiting for IPC connection...
D/STATUSBAR-StatusBarManagerService( 2423): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/STATUSBAR-StatusBarManagerService( 2423): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
,D/RegisteredServicesCache( 2760): empty dynamic service
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2423):   Scheme: "mmsto"
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2423): tr p:2784,o:f
,D/StatusBarManagerService( 2423): semi p:2784,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2423): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2423): Got RemoteException sending setActive(false) notification to pid 4998 uid 10495
,I/SELinux ( 5501): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5501):  
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "sms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2423): Killing 4513:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 5501): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5501):  
I/SELinux ( 5501):  
,I/SELinux ( 5501): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5501): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5501): >>>>> Normal User
,E/dalvikvm( 5501): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
,E/SELinux ( 5501): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "smsto"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/CustomFrequencyManagerService( 2423): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2423): mDVFSHelper.release()
,D/SensorService( 2423):   0.3 0.0 9.8
,D/TimaKeyStoreProvider( 5501): in addTimaSignatureService
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "mms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 5501): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5501): Added TimaKesytore provider
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "mmsto"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2760): GC_CONCURRENT freed 2305K, 27% free 10254K/14044K, paused 3ms+2ms, total 54ms
,I/display ( 1923): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4)
D/dalvikvm( 5501): GC_CONCURRENT freed 2997K, 32% free 9573K/14056K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 5501): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 2423): GC_EXPLICIT freed 2451K, 19% free 24543K/30076K, paused 20ms+21ms, total 397ms
D/PackageManager( 2423): delete sourFile : 
,D/BackupManagerService( 2423): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 2423): removePackageParticipantsLocked: uid=10495 #1
,I/SELinux ( 5514): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5514):  
I/ActivityManager( 2423): Killing 4674:com.policydm/1000 (adj 15): empty #43
,D/PackageManager( 2423): delete native library directory: 
,D/PackageManager( 2423): return delete result to caller: 1124151424
,D/PackageManager( 2423): returnCode: 1
,D/AndroidRuntime( 5448): Shutting down VM
,D/dalvikvm( 5448): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 3ms
I/SELinux ( 5514): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5514):  
I/SELinux ( 5514):  
,I/SELinux ( 5514): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5514): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5514): >>>>> Normal User
E/dalvikvm( 5514): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "sms"
,I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 5514): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5514): in addTimaSignatureService
I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "smsto"
,D/TimaKeyStoreProvider( 5514): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5514): Added TimaKesytore provider
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "mms"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2423):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2423):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2423):   Scheme: "mmsto"
I/PackageManager( 2423): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5514): GC_CONCURRENT freed 2987K, 32% free 9584K/14056K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 5514): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/dalvikvm( 5514): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 5514): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 5514): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0000
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 12 sec
,D/WallpaperManager( 2784): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 2784): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 2784): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,E/dalvikvm( 5514): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5514): Link of class 'Ldqp;' failed
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5514): Link of class 'Ldqp;' failed
I/dalvikvm( 5514): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 5514): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5514): Link of class 'Ldqp;' failed
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5514): Link of class 'Ldqp;' failed
I/dalvikvm( 5514): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 5514): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5514): Link of class 'Ldqp;' failed
W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 5514): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5514): Link of class 'Ldqp;' failed
I/dalvikvm( 5514): Could not find method dqp.d, referenced from method g.a
,W/dalvikvm( 5514): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 5514): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5514): Link of class 'Lax;' failed
E/dalvikvm( 5514): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 5514): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5514): Link of class 'Laz;' failed
E/dalvikvm( 5514): Could not find class 'az', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 5514): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0008
,I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(32)
,I/dalvikvm( 5514): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5514): Could not find method android.view.View.getTransitionName, referenced from method g.a
,W/dalvikvm( 5514): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 5514): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 5514): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 5514): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5514): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 5514): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5514): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5514): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 5514): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5514): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 5514): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 5514): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
,W/dalvikvm( 5514): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 5514): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 5514): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 5514): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 5514): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 5514): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 5514): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 5514): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 5514): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5514): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5514): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 5514): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 5514): Link of class 'Lax;' failed
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 5514): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 5514): Link of class 'Laz;' failed
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,I/display ( 1923): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/dalvikvm( 5514): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422bf558,
,D/dalvikvm( 5514): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422bf558,
,W/ApplicationsProvider( 2957): Could not fetch usage stats,
W/ApplicationsProvider( 2957): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2957): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2957): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2957): ,	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2957): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/BatteryService( 2423): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 313, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2423): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2423): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2583): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dalvikvm( 5514): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 5514): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0076
I/Babel_SMS( 5514): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5514): MmsConfig.loadMmsSettings
I/Babel_SMS( 5514): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 5514): MmsConfig.loadFromDatabase
,D/libgps  ( 2423): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2423): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2423): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2423): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SQLiteDatabase( 5514): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 5514): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5514): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5514): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5514): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5514): 	at alg.<init>(SourceFile:161)
E/SQLiteDatabase( 5514): 	at alj.a(SourceFile:1015)
E/SQLiteDatabase( 5514): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/SQLiteDatabase( 5514): 	at gvf.d(SourceFile:408)
E/SQLiteDatabase( 5514): 	at gvf.b(SourceFile:238)
E/SQLiteDatabase( 5514): 	at gvf.a(SourceFile:204)
E/SQLiteDatabase( 5514): 	at gvf.a(SourceFile:485)
E/SQLiteDatabase( 5514): 	at alg.a(SourceFile:167)
E/SQLiteDatabase( 5514): 	at dnm.c(SourceFile:606)
E/SQLiteDatabase( 5514): 	at dnm.b(SourceFile:570)
E/SQLiteDatabase( 5514): 	at dnn.run(SourceFile:221)
,W/dalvikvm( 5514): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5514): FATAL EXCEPTION: Thread-453
E/AndroidRuntime( 5514): Process: com.google.android.talk, PID: 5514
E/AndroidRuntime( 5514): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5514): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5514): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5514): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5514): 	at alg.<init>(SourceFile:161)
E/AndroidRuntime( 5514): 	at alj.a(SourceFile:1015)
E/AndroidRuntime( 5514): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/AndroidRuntime( 5514): 	at gvf.d(SourceFile:408)
E/AndroidRuntime( 5514): 	at gvf.b(SourceFile:238)
E/AndroidRuntime( 5514): 	at gvf.a(SourceFile:204)
E/AndroidRuntime( 5514): 	at gvf.a(SourceFile:485)
E/AndroidRuntime( 5514): 	at alg.a(SourceFile:167)
E/AndroidRuntime( 5514): 	at dnm.c(SourceFile:606)
E/AndroidRuntime( 5514): 	at dnm.b(SourceFile:570)
E/AndroidRuntime( 5514): 	at dnn.run(SourceFile:221)
,E/DropBoxManagerService( 2423): Can't write: system_app_crash
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop214.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 5 more
,W/dalvikvm( 5514): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 5514): Link of class 'Lfzc;' failed
E/dalvikvm( 5514): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 5514): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 5514): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
,W/dalvikvm( 5514): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 5514): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 5514): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 5514): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 5514): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 5514): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 5514): Link of class 'Lfzc;' failed
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
W/ServiceManager( 2423): Permission failure: com.samsung.permission.SSENSOR from uid=10109 pid=5514
D/PermissionCache( 2423): checking com.samsung.permission.SSENSOR for uid=10109 => denied (192 us)
E/SensorService( 2423): Permission Denial : SEC Private Sensor 
,E/SensorService( 2423): Permission Denial : SEC Private Sensor 
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2423): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/ExynosCameraInterface( 1927): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1927): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1927): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1927): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,I/SurfaceFlinger( 1923): id=19 createSurf (1x1),1 flag=4, ualk
,D/dalvikvm( 5514): GC_CONCURRENT freed 1788K, 24% free 10844K/14116K, paused 5ms+5ms, total 39ms
,D/CustomFrequencyManagerService( 2423): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2423  tag : ACTIVITY_RESUME_BOOSTER@8
W/Settings( 5514): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5514): startup - clean
,I/Babel   ( 5514): deleted: false for 0
,I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(16)
,I/dalvikvm( 5514): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 5514): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x000d
,D/PackageManager( 2423): [MSG] WRITE_PACKAGE_RESTRICTIONS
,F/PackageManager( 2423): Unable to backup user packages state file, current changes will be lost at reboot
,E/DropBoxManagerService( 2423): Can't write: system_server_wtf
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2423): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2423): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2423): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2423): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2423): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2423): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1223)
E/DropBoxManagerService( 2423): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:815)
E/DropBoxManagerService( 2423): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DropBoxManagerService( 2423): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2423): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 17 more
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 5514): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 5514): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5514): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 5514): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 5514): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;),
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;),
E/dalvikvm( 5514): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 5514): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 5514): VFY: replacing opcode 0x1f at 0x0021,
,W/dalvikvm( 5514): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 5514): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f,
,I/SELinux ( 5540): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5540):  
,E/dalvikvm( 5514): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 5514): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 5514): VFY: replacing opcode 0x1f at 0x0014,
,I/dalvikvm( 5514): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a,
W/dalvikvm( 5514): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 5514): VFY: replacing opcode 0x6e at 0x0074,
,I/ActivityManager( 2423): Killing 4690:com.osp.app.signin/u0a44 (adj 15): empty #43,
I/SELinux ( 5540): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5540):  
I/SELinux ( 5540):  
I/SELinux ( 5540): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5540): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
E/dalvikvm( 5540): >>>>> Normal User
E/dalvikvm( 5540): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 5540): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5540): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5540): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 5540): Added TimaKesytore provider,
,I/vclib   ( 5514): onServiceConnected
,W/Babel   ( 5514): Attempted to change video mute state without an active call.,
,D/dalvikvm( 5514): GC_CONCURRENT freed 982K, 17% free 11957K/14376K, paused 2ms+5ms, total 63ms,
,E/SQLiteDatabase( 2850): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.,
E/SQLiteDatabase( 2850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2850): ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.playlog.store.r.b(SourceFile:406)
,E/SQLiteDatabase( 2850): 	at com.google.android.gms.playlog.store.r.a(SourceFile:301)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.playlog.service.d.a(SourceFile:126)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 2850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2850): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17),
E/SQLiteDatabase( 2850): 	at java.lang.Thread.run(Thread.java:841)
,E/PlayLogIntentService( 2850): not an error (code 0): Could not open the database in read/write mode.,
E/PlayLogIntentService( 2850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178),
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PlayLogIntentService( 2850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PlayLogIntentService( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2850): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PlayLogIntentService( 2850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PlayLogIntentService( 2850): 	at com.google.android.gms.playlog.store.r.b(SourceFile:406)
E/PlayLogIntentService( 2850): 	at com.google.android.gms.playlog.store.r.a(SourceFile:301)
E/PlayLogIntentService( 2850): 	at com.google.android.gms.playlog.service.d.a(SourceFile:126)
E/PlayLogIntentService( 2850): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/PlayLogIntentService( 2850): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,E/PlayLogIntentService( 2850): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 2850): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/PlayLogIntentService( 2850): 	at java.lang.Thread.run(Thread.java:841)
,D/dalvikvm( 5514): GC_FOR_ALLOC freed 563K, 19% free 12403K/15272K, paused 26ms, total 26ms,
D/dalvikvm( 5540): GC_CONCURRENT freed 2998K, 32% free 9571K/14060K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 5540): WAIT_FOR_CONCURRENT_GC blocked 13ms,
,D/dalvikvm( 5514): GC_FOR_ALLOC freed 1759K, 24% free 12773K/16800K, paused 23ms, total 24ms
,E/dalvikvm( 5540): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a,
W/dalvikvm( 5540): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 5540): VFY: replacing opcode 0x22 at 0x0000,
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 13 sec,
W/System.err( 4778): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4778): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4778): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4778): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4778): ,	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4778): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4778): 	,at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
W/System.err( 4778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4778): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4778): 	at java.lang.Thread.run(Thread.java:841),
W/System.err( 4778): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4778): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4778): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4778): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4778): ,	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4778): ,	... 11 more
,W/dalvikvm( 5540): Unable to resolve superclass of Lal; (749),
W/dalvikvm( 5540): Link of class 'Lal;' failed
E/dalvikvm( 5540): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5540): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 5540): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5540): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5540): Link of class 'Lan;' failed
E/dalvikvm( 5540): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5540): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 5540): VFY: replacing opcode 0x22 at 0x002a,
I/dalvikvm( 5540): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5540): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5540): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 5540): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0006
,I/display ( 1923): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4),
W/dalvikvm( 5540): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5540): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5540): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 5540): VFY: replacing opcode 0x23 at 0x0005,
,D/dalvikvm( 5540): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a,
W/dalvikvm( 5540): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5540): Link of class 'Lal;' failed
D/dalvikvm( 5540): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5540): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5540): Link of class 'Lan;' failed
D/dalvikvm( 5540): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a,
,D/dalvikvm( 5540): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a,
,I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a,
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x000d,
,D/dalvikvm( 5540): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 5540): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5540): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5540): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs,
W/dalvikvm( 5540): VFY: unable to resolve instance field 46
,D/dalvikvm( 5540): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 5540): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5540): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5540): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5540): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5540): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5540): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42384fa0
,D/dalvikvm( 5540): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42384fa0
,D/dalvikvm( 5540): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42384fa0, skipping init
,E/SQLiteLog( 3155): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3155): threadid=42: thread exiting with uncaught exception (group=0x4180ac08)
,D/dalvikvm( 5540): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42384fa0
D/dalvikvm( 5540): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42384fa0
,V/JNIHelp ( 5540): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
E/AndroidRuntime( 3155): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 3155): Process: com.google.android.gms, PID: 3155
E/AndroidRuntime( 3155): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3155): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 3155): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$ImageCleaner.performCleanup(PlayGamesContentProvider.java:1865)
E/AndroidRuntime( 3155): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1671)
E/AndroidRuntime( 3155): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1586)
E/AndroidRuntime( 3155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3155): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3155): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2423): Can't write: system_app_crash
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 5 more
,D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1923): id=20 createSurf (1x1),1 flag=4, hms
,E/android.os.Debug( 2423): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,I/dumpstate( 5565): begin
,I/dalvikvm( 5540): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 5540): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5540): VFY: replacing opcode 0x71 at 0x0046
,D/dalvikvm( 5540): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42384fa0
,D/dalvikvm( 5540): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42384fa0
D/dalvikvm( 5540): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42384fa0
,D/dalvikvm( 5540): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42384fa0
,I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5540): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5540): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5540): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0220
,I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(24)
,I/ProviderInstaller( 5540): Installed default security provider GmsCore_OpenSSL
,D/libgps  ( 2423): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2423): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2423): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/YouTube MDX( 5540): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5540): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/EnterpriseDeviceManagerService( 2423): Package has changed for user 0
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 5540): GC_CONCURRENT freed 1895K, 24% free 10749K/14128K, paused 5ms+3ms, total 32ms
,D/dalvikvm( 5540): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5540): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 5540): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5540): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5540): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5540): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/SQLiteDatabase( 5540): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5540): 	at ghq.a(SourceFile:1037)
E/SQLiteDatabase( 5540): 	at ghq.a(SourceFile:1060)
E/SQLiteDatabase( 5540): 	at glm.b(SourceFile:152)
E/SQLiteDatabase( 5540): 	at glp.run(SourceFile:128)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5540): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5540): 	at java.lang.Thread.run(Thread.java:841)
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5540): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/SQLiteDatabase( 5540): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5540): 	at ghq.b(SourceFile:1110)
E/SQLiteDatabase( 5540): 	at glm.a(SourceFile:139)
E/SQLiteDatabase( 5540): 	at glo.run(SourceFile:116)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5540): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5540): 	at java.lang.Thread.run(Thread.java:841)
,W/InstanceID/Rpc( 5540): Found 10012
,E/SQLiteOpenHelper( 5540): Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):,
E/SQLiteOpenHelper( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5540): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5540): 	,at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5540): 	at ghq.b(SourceFile:1110)
E/SQLiteOpenHelper( 5540): 	at glm.a(SourceFile:139)
E/SQLiteOpenHelper( 5540): 	at glo.run(SourceFile:116)
E/SQLiteOpenHelper( 5540): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5540): 	,at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteOpenHelper( 5540): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteOpenHelper( 5540): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5540): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5540): 	at goz.run(SourceFile:40)
E/SQLiteOpenHelper( 5540): 	at java.lang.Thread.run(Thread.java:841)
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/SQLiteOpenHelper( 5540): Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 5540): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,E/SQLiteLog( 3155): (3850) statement aborts at 168: [DELETE FROM FileContent154 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
,E/DocListDatabase( 3155): Failed to delete from FileContent154 table
E/DocListDatabase( 3155): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 3155): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 3155): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/DocListDatabase( 3155): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 3155): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 3155): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/DocListDatabase( 3155): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 3155): 	at com.google.android.gms.drive.database.f.a(SourceFile:984)
E/DocListDatabase( 3155): 	,at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 3155): 	at com.google.android.gms.drive.j.ag.run(SourceFile:51)
E/DocListDatabase( 3155): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 3155): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 3155): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 3155): threadid=34: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 3155): Sending signal. PID: 3155 SIG: 9,
W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2423): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 2423): Process com.google.android.gms (pid 3155) (adj 1) has died.
,I/CrashAnrDetector( 2423): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 2423): clearDefaults: com.example.hello
,E/SQLiteDatabase( 5540): Failed to open database '/data/data/com.google.android.youtube/databases/youtube_upload_service'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5540): 	at lax.a(SourceFile:1057)
E/SQLiteDatabase( 5540): 	at lax.call(SourceFile:41)
E/SQLiteDatabase( 5540): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5540): 	at lay.run(SourceFile:336)
E/SQLiteDatabase( 5540): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5540): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5540): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5540): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
,W/AtomicFile( 2423): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2423): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/ViewRootImpl( 2423): sendUserActionEvent() mView == null
,E/SQLiteDatabase( 5540): Failed to open database '/data/data/com.google.android.youtube/databases/google_conversion_tracking.db'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5540): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5540): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5540): 	at ahe.a(SourceFile:102)
E/SQLiteDatabase( 5540): 	at aha.a(SourceFile:2161)
E/SQLiteDatabase( 5540): 	at ags.run(SourceFile:34)
E/SQLiteDatabase( 5540): 	at java.lang.Thread.run(Thread.java:841)
,W/GoogleConversionReporter( 5540): Error opening writable conversion tracking database,
,I/SELinux ( 5621): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5621):  
,E/SQLiteDatabase( 5540): Failed to open database '/data/data/com.google.android.youtube/databases/preload_videos_tasks.db'.
E/SQLiteDatabase( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5540): 	at jqg.a(SourceFile:65)
E/SQLiteDatabase( 5540): 	at jqj.handleMessage(SourceFile:1309)
E/SQLiteDatabase( 5540): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5540): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5540): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 5540): threadid=40: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5540): FATAL EXCEPTION: jqi
E/AndroidRuntime( 5540): Process: com.google.android.youtube, PID: 5540
E/AndroidRuntime( 5540): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5540): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5540): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5540): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5540): 	at jqg.a(SourceFile:65)
E/AndroidRuntime( 5540): 	at jqj.handleMessage(SourceFile:1309)
E/AndroidRuntime( 5540): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5540): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5540): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 5621): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5621):  
I/SELinux ( 5621):  
,I/SELinux ( 5621): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5621): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5621): >>>>> Normal User
,E/dalvikvm( 5621): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/DropBoxManagerService( 2423): Can't write: system_app_crash
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 5 more
E/SELinux ( 5621): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 5621): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5621): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5621): Added TimaKesytore provider
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1923): id=21 createSurf (1x1),1 flag=4, zoutube
,E/android.os.Debug( 2423): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
D/dalvikvm( 5621): GC_CONCURRENT freed 2953K, 32% free 9621K/14060K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 5621): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/dalvikvm( 5621): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 5621): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 5621): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5621): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 5621): VFY: replacing opcode 0x6e at 0x00ca
,I/dumpstate( 5636): begin
,I/MultiDex( 5621): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 5621): install,
I/MultiDex( 5621): MultiDexExtractor.load(/data/app/com.google.android.gms-4.apk, false)
I/MultiDex( 5621): loading existing secondary dex files
I/MultiDex( 5621): load found 3 secondary dex files
,I/MultiDex( 5621): install done
,I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 14 sec
,W/System.err( 4778): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4778): 	at libcore.io.IoBridge.write(IoBridge.java:455)
,W/System.err( 4778): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4778): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
,W/System.err( 4778): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4778): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4778): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4778): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4778): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4778): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4778): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4778): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4778): 	... 11 more
,I/SurfaceFlinger( 1923): id=20 Removed hms (7/10)
,I/SurfaceFlinger( 1923): id=20 Removed hms (-2/10)
,D/dalvikvm( 5621): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5621): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5621): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5621): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5621): VFY: unable to resolve instance field 46
,D/dalvikvm( 5621): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5621): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5621): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5621): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5621): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5621): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5621): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c0b28
D/dalvikvm( 5621): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c0b28
,D/dalvikvm( 5621): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c0b28, skipping init
,D/dalvikvm( 5621): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c0b28
D/dalvikvm( 5621): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c0b28
,V/JNIHelp ( 5621): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 5621): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c0b28
,D/dalvikvm( 5621): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x422c0b28
D/dalvikvm( 5621): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c0b28
,D/dalvikvm( 5621): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422c0b28
,I/ProviderInstaller( 5621): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm( 2850): GC_EXPLICIT freed 476K, 25% free 10866K/14388K, paused 4ms+5ms, total 42ms,
,W/NativeLibraryUtils( 5621): Failed to open lock file,
W/NativeLibraryUtils( 5621): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5621): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 5621): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 5621): 	at com.google.android.gms.common.util.bc.b(SourceFile:325)
W/NativeLibraryUtils( 5621): 	at com.google.android.gms.common.app.a.run(SourceFile:205)
W/NativeLibraryUtils( 5621): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5621): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5621): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/NativeLibraryUtils( 5621): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 5621): 	... 3 more
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak,
,I/GAv4-SVC( 5621): Google Analytics 8.3.01 is starting up.,
,E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak,
,E/SQLiteDatabase( 5621): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.,
E/SQLiteDatabase( 5621): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5621): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.v.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.l(SourceFile:812)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.a(SourceFile:630)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.e(SourceFile:264)
,E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.x.d(SourceFile:885)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.x.b(SourceFile:242)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.aa.run(SourceFile:152)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,E/SQLiteDatabase( 5621): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.measurement.n.run(SourceFile:388)
E/GAv4-SVC( 5621): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5621): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 5621): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SQLiteDatabase( 5621): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5621): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.v.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.l(SourceFile:812)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.a(SourceFile:630)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.u.e(SourceFile:264)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.x.d(SourceFile:885)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.x.b(SourceFile:242)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.analytics.internal.aa.run(SourceFile:152)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5621): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.measurement.n.run(SourceFile:388)
E/GAv4-SVC( 5621): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/GAv4-SVC( 5621): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5621): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 5621): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5621): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5621): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5621): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 5621): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 5621): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5621): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5621): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 5621): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/SQLiteDatabase( 5621): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 5621): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteDatabase( 5621): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 5621): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 5621): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 5621): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteDatabase( 5621): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 5621): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5621): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5621): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5621): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 5621): Process: com.google.android.gms, PID: 5621
E/AndroidRuntime( 5621): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 5621): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 5621): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5621): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5621): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5621): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5621): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5621): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 5621): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 5621): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5621): 	... 4 more
E/SQLiteOpenHelper( 5621): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 5621): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5621): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5621): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5621): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5621): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteOpenHelper( 5621): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteOpenHelper( 5621): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteOpenHelper( 5621): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteOpenHelper( 5621): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteOpenHelper( 5621): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteOpenHelper( 5621): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 5621): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5621): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5621): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5621): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5621): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5621): 	at java.lang.Thread.run(Thread.java:841)
W/ActivityManager( 2423): Process com.google.android.gms has crashed too many times: killing!
E/DropBoxManagerService( 2423): Can't write: system_app_crash
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 5 more
I/ActivityManager( 2423): Killing 5621:com.google.android.gms/u0a12 (adj 0): crash
W/BroadcastQueue( 2423): Unable to launch app com.google.android.gms/10012 for broadcast Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) }: process is bad
I/SELinux ( 5655): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5655):  
I/SELinux ( 5655): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5655):  
I/SELinux ( 5655):  
I/SELinux ( 5655): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5655): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5655): >>>>> Normal User
E/dalvikvm( 5655): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
E/SELinux ( 5655): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/display ( 1923): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
D/TimaKeyStoreProvider( 5655): in addTimaSignatureService
D/TimaKeyStoreProvider( 5655): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5655): Added TimaKesytore provider
D/dalvikvm( 5655): GC_CONCURRENT freed 2967K, 32% free 9601K/14056K, paused 2ms+1ms, total 19ms
D/dalvikvm( 5655): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/dalvikvm( 5655): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 5655): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5655): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5655): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 5655): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 5655): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5655): install
I/MultiDex( 5655): MultiDexExtractor.load(/data/app/com.google.android.gms-4.apk, false)
I/MultiDex( 5655): loading existing secondary dex files
I/MultiDex( 5655): load found 3 secondary dex files
I/MultiDex( 5655): install done
E/android.os.Debug( 2423): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
I/dumpstate( 5668): begin
D/dalvikvm( 5655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5655): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5655): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5655): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5655): VFY: unable to resolve instance field 46
D/dalvikvm( 5655): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5655): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5655): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5655): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5655): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 5655): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c1c38
D/dalvikvm( 5655): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c1c38
D/dalvikvm( 5655): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c1c38, skipping init
D/dalvikvm( 5655): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c1c38
D/dalvikvm( 5655): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c1c38
V/JNIHelp ( 5655): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/SensorService( 2423):   0.3 0.0 9.9
D/dalvikvm( 5655): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x422c1c38
D/dalvikvm( 5655): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x422c1c38
D/dalvikvm( 5655): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x422c1c38
D/dalvikvm( 5655): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422c1c38
I/ProviderInstaller( 5655): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 5655): Failed to open lock file
W/NativeLibraryUtils( 5655): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5655): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 5655): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 5655): 	at com.google.android.gms.common.util.bc.b(SourceFile:325)
W/NativeLibraryUtils( 5655): 	at com.google.android.gms.common.app.a.run(SourceFile:205)
W/NativeLibraryUtils( 5655): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5655): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5655): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 5655): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 5655): 	... 3 more
I/dalvikvm( 5655): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5655): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 5655): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5655): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5655): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
D/dalvikvm( 5655): VFY: replacing opcode 0x6e at 0x0220
E/dalvikvm( 5655): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 5655): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/dalvikvm( 5655): VFY: replacing opcode 0x1f at 0x000e
E/SQLiteDatabase( 5655): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 5655): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5655): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 5655): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 5655): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5655): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5655): 	at java.lang.Thread.run(Thread.java:841)
W/dalvikvm( 5655): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5655): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 5655): Process: com.google.android.gms, PID: 5655
E/AndroidRuntime( 5655): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 5655): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 5655): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5655): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5655): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5655): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 5655): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5655): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5655): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5655): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5655): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 5655): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 5655): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 5655): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5655): 	... 4 more
E/SQLiteDatabase( 5655): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 5655): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5655): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteDatabase( 5655): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 5655): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 5655): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 5655): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 5655): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteDatabase( 5655): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 5655): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5655): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5655): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5655): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5655): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 5655): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5655): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5655): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5655): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5655): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteOpenHelper( 5655): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteOpenHelper( 5655): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteOpenHelper( 5655): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteOpenHelper( 5655): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteOpenHelper( 5655): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteOpenHelper( 5655): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 5655): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5655): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5655): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5655): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5655): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5655): 	at java.lang.Thread.run(Thread.java:841)
E/DropBoxManagerService( 2423): Can't write: system_app_crash
E/DropBoxManagerService( 2423): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2423): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2423): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2423): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2423): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2423): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2423): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2423): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2423): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2423): 	... 5 more
W/SQLiteOpenHelper( 5655): Opened reminders.db in read-only mode
D/PointerIcon( 2423): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2423): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2423): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2423): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1923): id=22 createSurf (1x1),1 flag=4, hms
I/DBG_DM  ( 4778): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 15 sec
W/System.err( 4778): java.io.IOException: write failed: EBADF (Bad file number)
W/Auth    ( 2850): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
W/System.err( 4778): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4778): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4778): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4778): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
W/System.err( 4778): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4778): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4778): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4778): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 4778): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4778): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4778): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4778): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4778): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/System.err( 4778): 	... 11 more
V/GLSActivity( 2850): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/dalvikvm( 5655): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 5655): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
D/dalvikvm( 5655): VFY: replacing opcode 0x1f at 0x00ef
D/LockPatternUtils( 2583): isPcwEnable = 10
W/dalvikvm( 5655): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
I/dalvikvm( 5655): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 5655): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
D/dalvikvm( 5655): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 5655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5655): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5655): VFY: replacing opcode 0x62 at 0x0008
D/dalvikvm( 5655): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
I/dalvikvm( 5655): DexOpt: unable to optimize static field ref 0x00a2 at 0x0c in Lcom/google/android/gms/checkin/d;.a
D/GCM     ( 5655): COMPAT: Multi user not supported
D/GCM     ( 2850): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/CheckinService( 5655): Checkin interval check for package: unspecified last checkin: 1449001650308 min interval config: 0 actual interval: 76786093
I/GCoreUlr( 5655): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/CheckinService( 5655): Disabling old GoogleServicesFramework version
I/display ( 1923): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(32)
I/GCoreUlr( 2738): DispatchingService.onCreate()
E/SharedPreferencesImpl( 2738): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
W/dalvikvm( 5655): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 5655): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/GCoreUlr( 2738): Error opening datastore
E/GCoreUlr( 2738): com.google.android.gms.leveldb.LevelDbIoErrorException: IO error: /data/data/com.google.android.gms/app_ulr_db/LOCK: Read-only file system
E/GCoreUlr( 2738): 	at com.google.android.gms.leveldb.LevelDb.nativeOpen(Native Method)
E/GCoreUlr( 2738): 	at com.google.android.gms.leveldb.LevelDb.a(SourceFile:137)
E/GCoreUlr( 2738): 	at com.google.android.location.reporting.b.a.a(SourceFile:82)
E/GCoreUlr( 2738): 	at com.google.android.location.reporting.service.DispatchingService.onCreate(SourceFile:379)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/GCoreUlr( 2738): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/GCoreUlr( 2738): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GCoreUlr( 2738): 	at android.os.Looper.loop(Looper.java:146)
E/GCoreUlr( 2738): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/GCoreUlr( 2738): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/GCoreUlr( 2738): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/GCoreUlr( 2738): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/GCoreUlr( 2738): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/GCoreUlr( 2738): 	at dalvik.system.NativeStart.main(Native Method)
V/GmsCoreStatsServiceLauncher( 5655): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
I/GCoreUlr( 2738): DispatchingService.onDestroy()
D/SystemUpdateService( 5655): onCreate
D/PersistentNotificationBroadcastReceiver( 2850): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/CheckinService( 5655): Checking schedule, now: 1449078436500 next: 1449559993214
F/PackageManager( 2423): Unable to backup user packages state file, current changes will be lost at reboot
I/CheckinService( 5655): active receiver: disabled

```
