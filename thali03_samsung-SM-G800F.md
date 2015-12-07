#### Test 502422852e23b2c_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/TimaKeyStoreProvider( 4782): in addTimaSignatureService
D/TimaKeyStoreProvider( 4782): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4782): Added TimaKesytore provider
--------- beginning of /dev/log/system
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/dalvikvm( 4782): GC_CONCURRENT freed 2995K, 31% free 9566K/13760K, paused 3ms+1ms, total 20ms
D/dalvikvm( 4782): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/ContextImpl( 4782): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:61 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 4799): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4799):  
,I/SELinux ( 4799): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4799):  
I/SELinux ( 4799):  
I/SELinux ( 4799): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4799): >>>>> Normal User
E/dalvikvm( 4799): >>>>> com.sec.android.app.bluetoothtest [ userId:0 | appId:1000 ]
E/SELinux ( 4799): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 4799): in addTimaSignatureService
D/TimaKeyStoreProvider( 4799): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4799): Added TimaKesytore provider
D/dalvikvm( 4799): GC_CONCURRENT freed 2999K, 31% free 9566K/13764K, paused 4ms+1ms, total 21ms
D/dalvikvm( 4799): WAIT_FOR_CONCURRENT_GC blocked 10ms
D/BluetoothBDAdrressReceiver( 4799): onReceive(), action: android.intent.action.BOOT_COMPLETED
W/ContextImpl( 4799): Implicit intents with startService are not safe: Intent { act=com.bluetoothtestapp.BtBDstartservice.BootComplete } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 
W/ContextImpl( 4799): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:19 android.app.ActivityThread.handleReceiver:2698 
D/BluetoothBDTestService( 2751): onCreate()
E/BluetoothBDTestService( 2751): onStart(), action: com.bluetoothtestapp.BtBDstartservice.BootComplete
I/SELinux ( 4813): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4813):  
E/BluetoothBDTestService( 2751): bd_address_path: /efs/bluetooth/bt_addr
E/BluetoothBDTestService( 2751): already exist!( /efs/bluetooth/bt_addr ), file length: 17
I/ActivityManager( 2419): Killing 3883:com.sec.android.omc/1000 (adj 15): empty #43
I/SELinux ( 4813): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4813):  
I/SELinux ( 4813):  
I/SELinux ( 4813): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4813): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4813): >>>>> Normal User
E/dalvikvm( 4813): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
E/SELinux ( 4813): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 4813): in addTimaSignatureService
I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 2 sec
D/TimaKeyStoreProvider( 4813): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4813): Added TimaKesytore provider
D/dalvikvm( 4813): GC_CONCURRENT freed 2997K, 31% free 9565K/13760K, paused 3ms+2ms, total 41ms
D/dalvikvm( 4813): WAIT_FOR_CONCURRENT_GC blocked 31ms
I/SELinux ( 4825): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4825):  
D/AndroidRuntime( 4811): 
D/AndroidRuntime( 4811): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4811): CheckJNI is OFF
D/AndroidRuntime( 4811): setted country_code = Poland
D/AndroidRuntime( 4811): setted countryiso_code = PL
D/AndroidRuntime( 4811): setted sales_code = PLS
D/AndroidRuntime( 4811): readGMSProperty: start
D/AndroidRuntime( 4811): readGMSProperty: already setted!!
D/AndroidRuntime( 4811): readGMSProperty: end
D/AndroidRuntime( 4811): addProductProperty: start
I/ActivityManager( 2419): Killing 3927:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #43
I/SELinux ( 4825): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4825):  
I/SELinux ( 4825):  
I/SELinux ( 4825): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4825): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4825): >>>>> Normal User
E/dalvikvm( 4825): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
E/SELinux ( 4825): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 4811): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4811): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4811): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4811): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4811): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/TimaKeyStoreProvider( 4825): in addTimaSignatureService
D/TimaKeyStoreProvider( 4825): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4825): Added TimaKesytore provider
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4782): Resource data:2131165197
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/gallery_searchable
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131165194
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
D/dalvikvm( 4825): GC_CONCURRENT freed 3007K, 31% free 9558K/13764K, paused 2ms+2ms, total 20ms
D/dalvikvm( 4825): WAIT_FOR_CONCURRENT_GC blocked 12ms
D/        ( 4782): PNG_doEncode true 159, 159
E/PersonaManagerService( 2419): returning null in  getPersonasForUser
I/AMMetaDataParserService( 4782): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
I/SELinux ( 4844): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4844):  
I/ActivityManager( 2419): Killing 3940:com.sec.modem.settings/1000 (adj 15): empty #43
D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 12% free 9502K/10744K, paused 2ms+3ms, total 32ms
I/SELinux ( 4844): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4844):  
I/SELinux ( 4844):  
I/SELinux ( 4844): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4844): >>>>> Normal User
E/dalvikvm( 4844): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
E/SELinux ( 4844): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 3ms+3ms, total 28ms
D/TimaKeyStoreProvider( 4844): in addTimaSignatureService
E/memtrack( 4811): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4811): failed to load memtrack module: -2
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 3ms+3ms, total 27ms
D/TimaKeyStoreProvider( 4844): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4844): Added TimaKesytore provider
D/dalvikvm( 4782): GC_CONCURRENT freed 433K, 13% free 12086K/13760K, paused 3ms+2ms, total 33ms
D/dalvikvm( 4782): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 4811): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
V/AlarmManager( 2419): waitForAlarm result :4
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/AndroidRuntime( 4811): Calling main entry com.android.commands.am.Am
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
D/dalvikvm( 4844): GC_CONCURRENT freed 2999K, 31% free 9575K/13768K, paused 10ms+1ms, total 64ms
D/dalvikvm( 4844): WAIT_FOR_CONCURRENT_GC blocked 47ms
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131165194
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceDrawer2131624995android.intent.action.drawer2130837586
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1921): id=14 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=15 createSurf (16x16),-1 flag=20004, EimLayer
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2419,o:f
I/SurfaceFlinger( 1921): id=16 createSurf (1x1),1 flag=404, iello
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceSlideshow2131624009android.intent.action.slideshow2130837584
D/Launcher.HomeView( 2773): onPause
D/AndroidRuntime( 4811): Shutting down VM
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2773,o:f
D/dalvikvm( 4811): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 4858): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4858):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 4858): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4858):  
I/SELinux ( 4858):  
I/SELinux ( 4858): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4858): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4858): >>>>> Normal User
E/dalvikvm( 4858): >>>>> com.example.hello [ userId:0 | appId:10509 ]
E/SELinux ( 4858): [DEBUG] seapp_context_lookup: seinfoCategory = default
W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10088
D/TimaKeyStoreProvider( 4858): in addTimaSignatureService
D/TimaKeyStoreProvider( 4858): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4858): Added TimaKesytore provider
V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 2773): onStop
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceCamera2131624012android.intent.action.camera2130837583
D/Launcher( 2773): onTrimMemory. Level: 20
D/dalvikvm( 4858): GC_CONCURRENT freed 2997K, 31% free 9569K/13764K, paused 2ms+1ms, total 23ms
D/dalvikvm( 4858): WAIT_FOR_CONCURRENT_GC blocked 19ms
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(39)
D/        ( 4782): PNG_doEncode true 159, 159
I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131624000android.intent.action.delete2130837585
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 4782): Resource data:2131165195
D/SensorService( 2419):   0.3 0.0 9.9
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/device_filter
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4782): Resource data:2131165204
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4782): Resource data:2131165204
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 4782): Resource data:2131165204
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.gallery3d:xml/wallpaper_picker_preview
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.TrimVideo
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
V/WebViewChromium( 4858): Binding Chromium to the background looper Looper (main, tid 1) {42278308}
I/chromium( 4858): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4858): Initializing chromium process, renderers=0
W/chromium( 4858): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 4858): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 4858): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 4858): loaded /system/lib/egl/libGLESv2_mali.so
I/SELinux ( 4884): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4884):  
I/Mali    ( 4858): Mali API Version : 401
I/Mali    ( 4858): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/ActivityManager( 2419): Killing 3952:com.sec.tcpdumpservice/1000 (adj 15): empty #43
I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 3 sec
I/SELinux ( 4884): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4884):  
I/SELinux ( 4884):  
I/SELinux ( 4884): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4884): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4884): >>>>> Normal User
E/dalvikvm( 4884): >>>>> com.samsung.android.app.colorblind [ userId:0 | appId:1000 ]
E/SELinux ( 4884): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 4782): Resource data:2131099676
I/dalvikvm( 4858): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4858): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4858): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4858): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4858): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4858): VFY: replacing opcode 0x6e at 0x0008
I/ActivityManager( 2419): Waited long enough for: ServiceRecord{432244d8 u0 com.samsung.android.providers.context/.ContextService}
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/spellscroll
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.default_searchable
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/TimaKeyStoreProvider( 4884): in addTimaSignatureService
D/StatusBarManagerService( 2419): tr p:4858,o:f
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131099648
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
W/dalvikvm( 4858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4858): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4858): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4858): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4858): VFY: replacing opcode 0x6f at 0x001a
D/TimaKeyStoreProvider( 4884): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4884): Added TimaKesytore provider
W/dalvikvm( 4858): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4858): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4858): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4858): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4858): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4858): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4858): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4858): CordovaWebView is running on device made by: samsung
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (7/10)
D/        ( 4782): PNG_doEncode true 106, 106
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:4858,o:f
D/dalvikvm( 4884): GC_CONCURRENT freed 3000K, 31% free 9566K/13764K, paused 3ms+1ms, total 30ms
D/dalvikvm( 4884): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/SurfaceFlinger( 1921): id=17 createSurf (1x1),1 flag=404, NainActivit
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SELinux ( 4906): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4906):  
I/HWUI    ( 4858): EGLImpl-HWUI Protected EGL context created
I/ActivityManager( 2419): Killing 3900:com.sec.android.app.mt/1000 (adj 15): empty #43
D/        ( 4782): PNG_doEncode true 106, 106
D/OpenGLRenderer( 4858): Enabling debug mode 0
W/AwContents( 4858): nativeOnDraw failed; clearing to background color.
I/SELinux ( 4906): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4906):  
I/SELinux ( 4906):  
I/SELinux ( 4906): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4906): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 4906): >>>>> Normal User
E/dalvikvm( 4906): >>>>> com.dropbox.android [ userId:0 | appId:10095 ]
E/SELinux ( 4906): [DEBUG] seapp_context_lookup: seinfoCategory = default
I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.release()
W/AwContents( 4858): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/TimaKeyStoreProvider( 4906): in addTimaSignatureService
D/TimaKeyStoreProvider( 4906): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 4906): Added TimaKesytore provider
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131099648
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
D/dalvikvm( 4906): GC_CONCURRENT freed 2998K, 31% free 9572K/13764K, paused 13ms+1ms, total 95ms
D/dalvikvm( 4906): WAIT_FOR_CONCURRENT_GC blocked 82ms
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
I/SurfaceFlinger( 1921): id=16 Removed iello (9/10)
I/SurfaceFlinger( 1921): id=16 Removed iello (-2/10)
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
I/chromium( 4858): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 4858): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:2
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/com.dropbox.android.service.DropboxNetworkReceiver( 4906): Setting receiver enabled: false
D/JsMessageQueue( 4858): Set native->JS mode to OnlineEventsBridgeMode
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
D/Finsky  ( 3678): [184] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 3678): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/com.dropbox.sync.android.a( 4906): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131099648
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/com.dropbox.sync.android.aa( 4906): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 4.4.2; samsung SM-G800F armeabi-v7a; en_US))
D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 4940): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4940):  
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
I/ActivityManager( 2419): Killing 3973:com.sec.phone/1001 (adj 15): empty #43
,I/chromium( 4858): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
I/GAV2    ( 3441): Thread[GAThread,5,main]: No campaign data found.
I/SELinux ( 4940): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4940):  
I/SELinux ( 4940):  
I/SELinux ( 4940): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4940): >>>>> Normal User
,E/dalvikvm( 4940): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 4940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4940): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4940): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4940): Added TimaKesytore provider
,I/chromium( 4858): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
E/libGLESv2( 4858): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 4858): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 4858): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42270438
,E/libGLESv2( 4858): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 4858): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 4858): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42270438
,D/jxcore_app_log( 4858): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2024175296
,D/JX-Cordova( 4858): jxcore cordova android initializing
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 4 sec
,D/dalvikvm( 4940): GC_CONCURRENT freed 3001K, 31% free 9565K/13760K, paused 3ms+1ms, total 31ms
,D/dalvikvm( 4940): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/elm:14132( 4940): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 4940): ELMEngine.ELMEngine( context ).
D/elm:14132( 4940): MDMBridge.setEnterpriseBridge()
D/elm:14132( 4940): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 4940): ElmAgentService : onCreate()
D/elm:14132( 4940): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/SELinux ( 4957): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4957):  
,D/elm:14132( 4940): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
,D/elm:14132( 4940): BootCompletedState : startBootCompleted() call
,D/elm:14132( 4940): ModuleBase.resetCalllogAPIAlarm()
,D/elm:14132( 4940): MDMBridge.getAllLicenseInfoFromSDK()
,I/elm:14132( 4940): Get License : 0
,D/elm:14132( 4940): ElmAgentService : onDestroy().
I/ActivityManager( 2419): Killing 4035:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
,I/SELinux ( 4957): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4957):  
I/SELinux ( 4957):  
,I/SELinux ( 4957): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4957): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4957): >>>>> Normal User
,E/dalvikvm( 4957): >>>>> com.sec.android.fwupgrade [ userId:0 | appId:1000 ]
,E/SELinux ( 4957): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4957): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4957): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4957): Added TimaKesytore provider
,W/jxcore-log( 4858): Initializing JXcore engine
,W/jxcore-log( 4858): JXcore engine is ready
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/jxcore-log( 4858): Starting JXcore engine
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
D/        ( 4782): PNG_doEncode true 106, 106
I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/System.out( 4906): Thread-359(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4906): Thread-359(ApacheHTTPLog):isShipBuild true
,I/System.out( 4906): Thread-359(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131099648
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/dalvikvm( 4957): GC_CONCURRENT freed 3004K, 31% free 9565K/13768K, paused 12ms+1ms, total 49ms
,D/dalvikvm( 4957): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/System.out( 4906): pool-4-thread-1 calls detatch()
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/SELinux ( 4971): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4971):  
,I/ActivityManager( 2419): Killing 4065:com.n7mobile.muzodajnia:main/u0a184 (adj 15): empty #43
,I/SELinux ( 4971): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4971):  
I/SELinux ( 4971):  
,I/SELinux ( 4971): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 4971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4971): >>>>> Normal User
,E/dalvikvm( 4971): >>>>> com.sec.factory.camera [ userId:0 | appId:1000 ]
,E/SELinux ( 4971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4971): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4971): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4971): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,D/dalvikvm( 4971): GC_CONCURRENT freed 2991K, 31% free 9576K/13764K, paused 3ms+1ms, total 52ms
,D/dalvikvm( 4971): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,I/CameraApp( 4971): CameraApp.onCreate()... mFeature : null
I/testFeature( 4971): Feature.Feature(context)
I/testFeature( 4971): Feature.readInternalDefaultXml()
,I/testFeature( 4971): ResetFeatureValue
,I/CameraFirmware_broadcast( 4971): CameraFirmwareBroadCastReceiver...
,I/CameraApp( 4971): CameraApp.getAppFeature()...
,I/SELinux ( 4983): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4983):  
I/ActivityManager( 2419): Killing 4082:com.google.android.configupdater/u0a3 (adj 15): empty #43
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,W/jxcore-log( 4858): Platform android
W/jxcore-log( 4858): 
,W/jxcore-log( 4858): Process ARCH arm
W/jxcore-log( 4858): 
I/SELinux ( 4983): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4983):  
I/SELinux ( 4983):  
,I/SELinux ( 4983): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 4983): >>>>> Normal User
,E/dalvikvm( 4983): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 4983): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 4983): in addTimaSignatureService
,D/TimaKeyStoreProvider( 4983): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 4983): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131099648
I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,I/jxcore-log( 4858): JXcore Cordova bridge is ready!
I/jxcore-log( 4858): 
,W/jxcore-log( 4858): JXcore engine is started
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/dalvikvm( 4983): GC_CONCURRENT freed 3007K, 31% free 9566K/13768K, paused 7ms+2ms, total 37ms
,D/dalvikvm( 4983): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/HarmonyEASService( 2419): Updating for all 1
,D/PackageIntentReceiver( 4983): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 4983): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
I/ActivityManager( 2419): Killing 4145:com.sec.dsm.system/1000 (adj 15): empty #43
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/SELinux ( 4996): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 4996):  
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,E/jxcore-log( 4858): >> samsung-SM-G800F
E/jxcore-log( 4858): 
,I/jxcore-log( 4858): Total memory 1319530496
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): Free memory 34476032
I/jxcore-log( 4858): 
I/jxcore-log( 4858): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4858): 
I/SELinux ( 4996): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 4996):  
I/SELinux ( 4996):  
,I/SELinux ( 4996): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 4996): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 4996): >>>>> Normal User
,E/dalvikvm( 4996): >>>>> com.google.android.gm [ userId:0 | appId:10106 ]
E/SELinux ( 4996): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,I/jxcore-log( 4858): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 4858): 
,D/TimaKeyStoreProvider( 4996): in addTimaSignatureService
,I/jxcore-log( 4858): Size 720 1280
I/jxcore-log( 4858): 
,D/TimaKeyStoreProvider( 4996): Cannot add TimaSignature Service, License check Failed
,I/jxcore-log( 4858): Screen Brightness 134
I/jxcore-log( 4858): 
,E/jxcore-log( 4858): Dummy Error Log.
E/jxcore-log( 4858): 
,D/ActivityThread( 4996): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131099648
,I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131493233com.android.mms.ui.conversationlistfragment.searchmessages2130837516
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837515
,D/dalvikvm( 4996): GC_CONCURRENT freed 2993K, 31% free 9573K/13764K, paused 2ms+1ms, total 20ms
D/dalvikvm( 4996): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceAdd from contacts2131493281com.android.mms.ui.composemessagefragment.attachcontacts2130837512
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 5 sec
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceCall2131493971com.android.mms.ui.composemessagefragment.calltocontact2130837513
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131492988com.android.mms.ui.composemessagefragment.delete2130837514
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSend2131492905com.android.mms.ui.composemessagefragment.send2130837517
,W/GAV2    ( 4996): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.DeliveryReportActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.PreviewsMessagesSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.QuickReplySettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.ui.SaveThreadActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.ui.SavedMsgsList
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.ui.RestorePreviewActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.ui.ConversationListRestore
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4782): Resource data:2131099671
,I/AMMetaDataParserService( 4782): getResourceName:com.android.mms:xml/searchable
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.VMessageViewerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.spam.HelpActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.content.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 4782): Resource data:,Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.mms.ui.AutoSendingTestActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.help.PrioritySenderHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.help.AddGlanceListHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
,I/SELinux ( 5022): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5022):  
,D/dalvikvm( 4782): GC_CONCURRENT freed 1822K, 20% free 12312K/15328K, paused 5ms+4ms, total 90ms
,D/dalvikvm( 4782): WAIT_FOR_CONCURRENT_GC blocked 66ms
I/SELinux ( 5022): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5022):  
I/SELinux ( 5022):  
,I/SELinux ( 5022): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5022): >>>>> Normal User
,E/dalvikvm( 5022): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 5022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5022): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5022): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5022): Added TimaKesytore provider
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131165216
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/        ( 4782): PNG_doEncode true 80, 80
,I/AMMetaDataParserService( 4782): Icon data: ResourceSearch2131297802com.android.settings.Search2130837582
,I/jxcore-log( 4858): getBuffer is called!!!!
I/jxcore-log( 4858): 
,D/dalvikvm( 5022): GC_CONCURRENT freed 2996K, 31% free 9576K/13768K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 5022): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceEdit quick settings2131296308com.android.settings.Favorite2130837581
,I/SELinux ( 5035): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5035):  
I/ActivityManager( 2419): Killing 4170:com.sec.android.app.factorykeystring/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SubSettings
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.TetherHelp
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetEnabler
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ethernet.EthernetConfigure
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429071
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429071
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiDummyPickerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.hs20.Hs20PickerDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedVzwSetupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiManageNetworks
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429071
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wifi_settings
I/SELinux ( 5035): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5035):  
I/SELinux ( 5035):  
I/SELinux ( 5035): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 4782): getResourceTypeNameid
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131297114
E/SELinux ( 5035): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5035): >>>>> Normal User
,E/dalvikvm( 5035): >>>>> com.sec.knox.seandroid [ userId:0 | appId:1000 ]
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
,E/SELinux ( 5035): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectionSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ApnSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429073
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429073
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/bluetooth_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429095
,D/TimaKeyStoreProvider( 5035): in addTimaSignatureService
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/mirror_link_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.TetherSettings
D/TimaKeyStoreProvider( 5035): Cannot add TimaSignature Service, License check Failed
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
D/ActivityThread( 5035): Added TimaKesytore provider
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429071
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wifi_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131297114
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wifi_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
,I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429146
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/date_time_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LanguageSettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131298419
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
D/PackageManager( 2419): [MSG] MCS_UNBIND
I/PackageManager( 2419): calling disconnectService()
D/PackageManager( 2419): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2419): Killing 4185:com.sec.factory/1000 (adj 15): empty #43
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131298419
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131298419
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/language_keyboard_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
D/dalvikvm( 5035): GC_CONCURRENT freed 3007K, 31% free 9565K/13768K, paused 2ms+2ms, total 34ms
,D/dalvikvm( 5035): WAIT_FOR_CONCURRENT_GC blocked 18ms
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429103
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SoundSettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429103
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/sound_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429100
,I/Gmail   ( 4996): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429099
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LockscreenMenuSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429099
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429109
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/block_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/Gmail   ( 4996): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429113
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429113
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
W/ContextImpl( 5035): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.service.MainReceiver.onReceive:47 android.app.ActivityThread.handleReceiver:2698 
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131297804
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429155
I/Gmail   ( 4996): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/about_settings
I/Gmail   ( 4996): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.TermsAndConditionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.users.UserOptions
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
I/knox    ( 5035): MainReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
,W/ContextImpl( 5035): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.CommomReceiver.listeningToBootCompleted:59 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:162 
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429054
I/knox    ( 5035): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/home_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429054
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/home_settings
D/knox    ( 5035): KNOXAgentService : onCreate()
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.users.AppRestrictionsFragment$Activity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataPar,serService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/knox    ( 5035): KNOXAgentService : set alarms for deniallog and usage data upload
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429055
D/knox    ( 5035): KNOXAgentService. startJobThread() start
D/knox    ( 5035): KNOXAgentService. JobThread()
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/application_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/knox    ( 5035): KNOXAgentService. JobThread. notifyAll().
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
D/knox    ( 5035): KNOXAgentService. startJobThread() wait
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/SELinux ( 5052): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5052):  
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429080
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
D/knox    ( 5035): mKnoxAgentEngine.ELMEngine( context , reStart:true).
D/knox    ( 5035): KNOXAgentService : onDestroy().
D/knox    ( 5035): ModuleBase.cancelAllAlarmManageModule()
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131296750
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429050
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/privacy_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131296750
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131296750
D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 12% free 9502K/10744K, paused 2ms+3ms, total 31ms
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/security_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429114
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429114
,I/SELinux ( 5052): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5052):  
I/SELinux ( 5052):  
I/SELinux ( 5052): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/accessibility_settings
E/SELinux ( 5052): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
E/dalvikvm( 5052): >>>>> Normal User
E/dalvikvm( 5052): >>>>> com.sec.knox.knoxsetupwizardclient [ userId:0 | appId:1000 ]
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131298587
E/SELinux ( 5052): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429114
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 2ms+4ms, total 26ms
,I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131298587
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429118
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/language_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429107
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/driving_mode
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
D/TimaKeyStoreProvider( 5052): in addTimaSignatureService
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429150
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/storage_settings
,I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.quicklaunch.QuickLaunchSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429152
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 5052): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5052): Added TimaKesytore provider
D/dalvikvm( 4858): GC_CONCURRENT freed 2374K, 26% free 10235K/13804K, paused 2ms+13ms, total 47ms
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
,D/dalvikvm( 2845): GC_EXPLICIT freed 1121K, 22% free 11036K/14132K, paused 5ms+22ms, total 133ms
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131296695
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429092
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/print_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429152
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/development_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429150
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131297938
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429150
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/storage_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131297938
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/storage_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429088
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/nfc_setting
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429090
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/sbeam_setting
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429094
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/screen_mirroring_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131296695
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/wireless_networks_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.KeyguardAppWidgetPickActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.UsageStats
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429148
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429148
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/battery_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429046
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/account_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.accounts.SyncSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AccountMenu
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429144
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_general_account_and_backup
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AppEncryption
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429135
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/user_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429213
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/nfc_payment_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429151
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/security_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.RegulatoryInfoDisplayActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429128
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_wallpaper
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.InformationTicker
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ASensorSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429112
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429112
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131299843
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/power_saving_mode_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429112
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429112
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/power_saving_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.AskUSBMode
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429149
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/power_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429113
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/dock_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 4782): Resource data:1
W/ResourceType( 4782): No package identifier when getting name for resource number 0x00000001
W/System.err( 4782): android.content.res.Resources$NotFoundException: Unable to find resource ID #0x1
W/System.err( 4782): 	at android.content.res.Resources.getResourceName(Resources.java:2988)
W/System.err( 4782): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:159)
W/System.err( 4782): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:86)
W/System.err( 4782): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 4782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4782): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429126
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131301070
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/pen_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131297804
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429130
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429120
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/motion_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.motion.ShakeTutorial
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429121
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/s_motion_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429133
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_input_motion_and_gesture_2014
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131300118
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/motions_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429123
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/finger_air_view_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429187
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/finger_air_view_settings_k
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429124
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/air_view_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429218
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/mouse_hovering_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429155
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/about_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PenHovering
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429126
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429126
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429126
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429126
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/pen_settings_menu
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PenHelpPopup
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.EnableScreenHelp
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$OneHandEditMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.InputControlHelp
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429100
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ReadingModeSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429212
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/customizable_key
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429099
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/lock_screen_menu_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131301505
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/lock_screen_options
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429130
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429130
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_notification_panel
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131302906
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/recommended_apps
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.bst.airmessage.setting.AirMsgSetting
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DormantmodeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429106
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/dormant_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantmodeSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2130838226
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
I/AMMetaDataParserService( 4782): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.dormantmode.DormantModeCustomListDel
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$GlanceSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429143
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/glance_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429136
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429136
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_personal_page
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429104
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/home_screen_mode_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429139
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/easy_mode_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429140
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/easy_mode_app_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.LocationAlert
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429080
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131302078
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429080
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 4782): Resource data:2131302078
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/myplace_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429080
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/location_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131302107
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/place_settings_title
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429086
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/wireless_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429044
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/bua_plus
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CloudPictureSyncSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CloudVideoSyncSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429049
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/scloud_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429122
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131297804
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/display_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429078
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/smart_bonding_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429131
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429131
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_toolbox
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429122
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/smart_screen
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$TorchlightSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2130838278
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 4782): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.torchlight.TorchlightSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2130838278
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:drawable/ic_settings_torchlight
I/AMMetaDataParserService( 4782): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429129
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429129
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/header_display_multi_window
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.search.SearchMain
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 4782): Resource data:2131165371
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:xml/searchable
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$HomeSyncBackupAndRestoreActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429051
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/homesync_backup_and_restore_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429114
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 4782): Resource data:2131298587
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:string/accessibility_settings
I/AMMetaDataParserService( 4782): getResourceTypeNamestring
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429125
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/voice_input_control_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429185
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/active_key_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429147
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429147
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/safetycare_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429203
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429203
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/safetycare_help
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429075
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/airplane_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429169
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/toddler_mode
I/AMMetaDataParserService( 4782): getResourceTypeNameid
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.favorite.MySettnigsRemoveActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 4782): Resource data:2131429138
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/festival_effect_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.wifi.WifiConnectDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$FingerprintSettingsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2130838226
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:drawable/ic_settings_dormant_mode
,I/AMMetaDataParserService( 4782): getResourceTypeNamedrawable
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintDisclaimer
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.Settings$FingerPrintManagerUIActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 4782): Resource data:2131429119
I/AMMetaDataParserService( 4782): getResourceName:com.android.settings:id/fingerprint_settings
I/AMMetaDataParserService( 4782): getResourceTypeNameid
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.RegisterFingerprint
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintPassword
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirmPassword
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintConfirm
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintSupportingFeatures
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerprintWebsignin
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsSetupWizard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.FingerPrintSettingsUseFingerprint
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.settings.fingerprint.PaypalPayment
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4782): Resource data:2131034120
,D/dalvikvm( 2419): GC_EXPLICIT freed 3159K, 19% free 24191K/29708K, paused 8ms+15ms, total 218ms,
I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/searchable
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131034113
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 6 sec
,I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/dalvikvm( 5052): GC_CONCURRENT freed 3005K, 31% free 9566K/13764K, paused 6ms+2ms, total 31ms
,D/dalvikvm( 5052): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,E/KnoxSetupWizardClient( 5052): isShipMode : 1
,I/KnoxSetupWizardClient( 5052): onReceive : android.intent.action.BOOT_COMPLETED
,W/System.err( 5052): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
W/System.err( 5052): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5052): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5052): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5052): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
W/System.err( 5052): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:83)
,W/System.err( 5052): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,W/System.err( 5052): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.containeragent
W/System.err( 5052): 	at android.os.Parcel.readException(Parcel.java:1469)
W/System.err( 5052): 	at android.os.Parcel.readException(Parcel.java:1419)
W/System.err( 5052): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:3458)
W/System.err( 5052): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1519)
,W/System.err( 5052): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.disablePackage(StubPackageThread.java:132)
,W/System.err( 5052): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:103)
,W/System.err( 5052): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ShortcutReceiver2( 5052):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/yash    ( 5052): setDisableWidget>size:0
,D/SensorService( 2419):   0.3 0.0 9.9
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 5067): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5067):  
I/ActivityManager( 2419): Killing 4207:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530,
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity,
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/SELinux ( 5067): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5067):  
I/SELinux ( 5067):  
,I/SELinux ( 5067): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/AMMetaDataParserService( 4782): Resource data:2131034113
,E/SELinux ( 5067): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5067): >>>>> Normal User
,E/dalvikvm( 5067): >>>>> com.LocalFota [ userId:0 | appId:10113 ],
I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml,
,E/SELinux ( 5067): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 5067): in addTimaSignatureService
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
,D/TimaKeyStoreProvider( 5067): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5067): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,D/dalvikvm( 5067): GC_CONCURRENT freed 3014K, 31% free 9558K/13768K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 5067): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/DBG_WSS_LF( 5067): [Not Defined][Line:75][onCreate] LocalFOTA Application Start !
,I/DBG_WSS_LF( 5067): [20.0040.140326][Line:27][<init>] First call,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.dialpad.VVM
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 4782): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 4782): Resource data:Loop for running activityalias.MessageShortcut,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailAllCallsActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131034112
I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/assistant_detail,
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceAdd to favourites2131623990android.intent.assistant.detail.favorite2130837528,
,I/DBG_WSS_LF( 5067): [20.0040.140326][Line:27][onReceive] android.intent.action.BOOT_COMPLETED,
,I/DBG_WSS_LF( 5067): [20.0040.140326][Line:31][onReceive] *** boot complete ***,
I/DBG_WSS_LF( 5067): [20.0040.140326][Line:441][xLFGetLFStatus] !!! Status -1 !!!
,I/DBG_WSS_LF( 5067): [20.0040.140326][Line:41][onReceive] nStatus : -1,
D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceRemove from favourites2131623991android.intent.assistant.detail.favorite2130837528,
,I/SELinux ( 5082): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5082):  
I/ActivityManager( 2419): Killing 3134:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #43,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceEdit2131623992android.intent.assistant.detail.edit2130837527,
,I/SELinux ( 5082): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5082):  
I/SELinux ( 5082):  
,I/SELinux ( 5082): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5082): >>>>> Normal User
,E/dalvikvm( 5082): >>>>> com.sec.android.app.mt [ userId:0 | appId:1000 ],
,E/SELinux ( 5082): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 4782): GC_CONCURRENT freed 2006K, 21% free 12276K/15476K, paused 2ms+3ms, total 49ms,
,D/TimaKeyStoreProvider( 5082): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5082): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5082): Added TimaKesytore provider,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceDelete2131623993android.intent.assistant.detail.delete2130837526,
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.test.FragmentTestActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity,
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.SubscriberInfoCheckerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.ATTAB
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.AABReadyToUseActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.SimCopy
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.AccessingSimCardInfo
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.WelcomeDecline
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.ContactsReadyToUseActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdateLater
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.PhoneUpdatePrompt
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.ActivationStatusActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.StartSyncInitialActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.FeaturesActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.RegistrationFailure
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.SyncResponseActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.ActivateLater
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.ZeroSimCardInfo
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.aab.activity.NewURLActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
I/AMMetaDataParserService( 4782): Resource data:2131034113
I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/assistant_main
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml,
,D/        ( 4782): PNG_doEncode true 106, 106,
,I/AMMetaDataParserService( 4782): Icon data: ResourceLogs2131624573android.intent.assistant.main.log2130837531
D/dalvikvm( 5082): GC_CONCURRENT freed 3010K, 31% free 9557K/13764K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 5082): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/StatusChecker( 5082): onReceive : android.intent.action.BOOT_COMPLETED
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceContacts2131623966android.intent.assistant.main.contact2130837529
,I/SELinux ( 5096): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5096):  
I/ActivityManager( 2419): Killing 3871:com.fmm.dm/1000 (adj 15): empty #43
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceFavourites2131624366android.intent.assistant.main.favorite2130837528
,I/SELinux ( 5096): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5096):  
I/SELinux ( 5096):  
,I/SELinux ( 5096): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5096): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5096): >>>>> Normal User
,E/dalvikvm( 5096): >>>>> com.samsung.android.sconnect [ userId:0 | appId:10135 ]
,E/SELinux ( 5096): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5096): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5096): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5096): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceKeypad2131624567android.intent.assistant.main.keypad2130837530
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4782): Resource data:2131034116
I/AMMetaDataParserService( 4782): getResourceName:com.android.contacts:xml/findo_searchable
I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.activities.ContactResolverActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4782): Resource data:2131099668
,I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.app.sbrowser:xml/searchable
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): getResourcePackageName:assistantlist
,I/AMMetaDataParserService( 4782): Resource data:2131099650
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/dalvikvm( 5096): GC_CONCURRENT freed 2998K, 31% free 9566K/13760K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 5096): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceEnter URL2131558515android.intent.action.doInputURL2130837507
,D/QuickConnect( 5096): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 5096): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 5096): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10135
,V/QuickConnect( 5096): SconnectManager.getInstance - () return existing instance null
,W/ContextImpl( 5096): Implicit intents with startService are not safe: Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } android.content.ContextWrapper.startServiceAsUser:517 android.content.ContextWrapper.startServiceAsUser:517 com.samsung.android.sconnect.periph.PeriphStartReceiver.onReceive:30 
,I/QuickConnect( 5096): PeriphService.onCreate - [START]
,I/SELinux ( 5108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5108):  
,I/QuickConnect( 5096): PeriphService.onCreate - [START] USER_OWNER,
,D/QuickConnect( 5096): PeriphService.setProcessForeground - Build.VERSION.SDK_INT = 19,
,D/dalvikvm( 4782): GC_FOR_ALLOC freed 762K, 23% free 12013K/15476K, paused 45ms, total 51ms
,I/QuickConnect( 5096): PeriphService.setProcessForeground - true of JB_MR2 complete 
,I/QuickConnect( 5096): PeriphService.setState - 0 >> 1
,V/QuickConnect( 5096): PeriphService.runService - 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 370, Delta = 10
I/QuickConnect[1.1][2] ( 5096): SconnectManager.SconnectManager - initiate from com.samsung.android.sconnect.periph.PeriphService@42286510
,I/QuickConnect[1.1][2] ( 5096): SconnectManager.SconnectManager - set getApplicationContext android.app.Application@422c3238
D/QuickConnect[1.1][2] ( 5096): SconnectManager.registerBroadcast - --
,D/        ( 4782): PNG_doEncode true 106, 106
,D/QuickConnect[1.1][2] ( 5096): SconnectManager.SconnectManager - REQUEST_ID :  1
,I/AMMetaDataParserService( 4782): Icon data: ResourceWindow manager2131558482android.intent.action.doWindowManager2130837509
,D/QuickConnect[1.1][2] ( 5096): ScanThread.ScanThread - created!
,V/QuickConnect[1.1][2] ( 5096): BluetoothHelper.BluetoothHelper - 
,I/SELinux ( 5108): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5108):  
I/SELinux ( 5108):  
,I/SELinux ( 5108): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5108): >>>>> Normal User
,E/dalvikvm( 5108): >>>>> com.sec.android.service.bezel [ userId:0 | appId:1000 ]
,E/SELinux ( 5108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/        ( 4782): PNG_doEncode true 106, 106
,D/QuickConnect[1.1][2] ( 5096): BluetoothHelper.registerBluetoothAdapterReceiver - mIsBluetoothAdapterReceiver = false
,I/AMMetaDataParserService( 4782): Icon data: ResourceNew window2131558765android.intent.action.doNewWindow2130837508
,V/QuickConnect[1.1][2] ( 5096): BleHelper.BleHelper - Constructor
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.mainactivity.controller.SecPowerControl
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.quickaccess.ui.AddQuickAccessActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.multiwindow.MultiTabActivity
,D/TimaKeyStoreProvider( 5108): in addTimaSignatureService
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.extractmode.ExtracterActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.DeleteBookmarksActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.MoveToFolderActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormDelete
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ReOrderBookmarksActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 4782): Resource data:Loop for running activityorg.samsung.content.sbrowser.pipette.SbrPipetteAnimationGLActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.widget.BookmarkWidgetConfigure
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.SBrowserProfileEditorContainerActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
,D/TimaKeyStoreProvider( 5108): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5108): Added TimaKesytore provider
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.DataConnection
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.cba.ImportCertificate
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.cba.InstalledCertificatesList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAutoDiscover
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 7 sec
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupDisclaimerWeb
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SaveasActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.Debug
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessMainActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.TestHarnessManualSettingsScreen
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131099667
E/QuickConnect[1.1][2] ( 5096): BleHelper.startScan - not isGattServiceReady. Try to BLE On calling addLeRadioReference()
D/BluetoothRadioManager( 5096): addLeRadioReference: Add CB  com.samsung.android.sconnect.common.net.BleHelper$GattServiceStateChangeCallback@4229a820
D/BluetoothRadioManager( 5096):  addRadioReference enabled = false
,D/BluetoothRadioManager( 5096):  BLE Radio count is : 1
D/BluetoothRadioManager( 5096): addLeRadioReference: isRadioEnabled() =  false
V/QuickConnect[1.1][2] ( 5096): BleHelper.mSearchWearable - true
,D/BluetoothManagerService( 2419): foregroundUser: 0
,I/AMMetaDataParserService( 4782): getResourceName:com.android.email:xml/email_assistant_menu
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,V/QuickConnect[1.1][2] ( 5096): UpnpHelper.UpnpHelper - 
,V/QuickConnect[1.1][2] ( 5096): JmdnsHelper.JmdnsHelper - Constructor
,V/QuickConnect[1.1][2] ( 5096): P2pHelper.P2pHelper - EXEC
,D/QuickConnect[1.1][2] ( 5096): p2pHelperWorkThread.p2pHelperWorkThread - created!
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceDrawer menu2131297956com.android.email.intent.messagelistfragment.drawer2130837559
,E/BluetoothManagerService( 2419): Package is exist.
,I/SELinux ( 5122): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5122):  
,D/QuickConnect[1.1][2] ( 5096): WifiHelper.WifiHelper -  -- 
,D/WifiDisplayAdapter( 2419): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/QuickConnect[1.1][2] ( 5096): CentralActionManager.CentralActionManager - EXEC
,V/QuickConnect[1.1][2] ( 5096): BluetoothOppActionHelper.BluetoothOppActionHelper - 
,D/        ( 4782): PNG_doEncode true 106, 106
V/QuickConnect[1.1][2] ( 5096): GroupVoiceTalkActionHelper.GroupVoiceTalkActionHelper -  --
,V/QuickConnect[1.1][2] ( 5096): SmartHomeActionHelper.SmartHomeActionHelper - --
,V/QuickConnect[1.1][2] ( 5096): ScreenMirrorActionHelper.ScreenMirrorActionHelper - 
,I/AMMetaDataParserService( 4782): Icon data: ResourceMessage marked as complete2131296812com.android.email.intent.messageviewfragment.favorite2130837558
V/QuickConnect[1.1][2] ( 5096): BluetoothActionHelper.BluetoothActionHelper - 
,D/BluetoothAdapter( 5096): 1110009656: getState() :  mService = null. Returning STATE_OFF
,I/SELinux ( 5122): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5122):  
I/SELinux ( 5122):  
,I/SELinux ( 5122): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5122): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5122): >>>>> Normal User
,E/dalvikvm( 5122): >>>>> com.android.bluetooth [ userId:0 | appId:1002 ]
,E/SELinux ( 5122): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/BluetoothHeadset( 5096): BTStateChangeCB is registed
,E/BluetoothHeadset( 5096): BluetoothHeadset service is binded
D/dalvikvm( 5108): GC_CONCURRENT freed 3001K, 31% free 9565K/13764K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 5108): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - make new instance com.samsung.android.sconnect.SconnectManager@422b16a0
,V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
V/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.PreDiscoveryHelper -  -- 
,D/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.setVisibilityFromSystemDb - --
D/        ( 4782): PNG_doEncode true 106, 106
D/BezelQuickConnect( 5108): BezelBroadcastReceiver - onReceive : android.intent.action.BOOT_COMPLETED
,D/BezelQuickConnect( 5108): BezelBroadcastReceiver - StartBezelInteractionService
,I/AMMetaDataParserService( 4782): Icon data: ResourceFlagged message2131296810com.android.email.intent.messageviewfragment.favorite2130837558
,D/QuickConnect[1.1][2] ( 5096): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,D/BezelQuickConnect( 5108): BezelManagerService - setProcessForeground, Build.VERSION.SDK_INT = 19
,D/QuickConnect[1.1][2] ( 5096): Utils.getFromDb -  Key[quick_connect_contact_only], isEnabled [1] /   <0 : Disable, 1 : Enable>
,D/TimaKeyStoreProvider( 5122): in addTimaSignatureService
D/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.setVisibilityFromSystemDb - isAllowToConnect : false, isContactOnly : true, visibilitySetting : 2
,D/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.changeResponseSetting - changed: 2
V/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.updateAdvData - 
,V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
,I/BezelQuickConnect( 5108): BezelManagerService - setProcessForeground, true of JB_MR2 complete 
D/BezelQuickConnect( 5108): BezelBroadcastReceiver - onReceive : Send to quickpanel - service.ENABLED
,V/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.updateRespTarget - 
,D/TimaKeyStoreProvider( 5122): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5122): Added TimaKesytore provider
,W/ContextImpl( 5108): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 android.content.ContextWrapper.sendBroadcast:377 com.sec.android.service.bezel.BezelBroadcastReceiver.onReceive:40 android.app.ActivityThread.handleReceiver:2698 
D/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.initializeAdvData - 
V/PhoneStatusBar( 2578): onReceive: Intent { act=com.sec.android.sconnect.service.ENABLED flg=0x10 }mQconnectEnable = true
V/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.initializeAdvData - name: S5mini-1(8)
D/QuickConnect[1.1][2] ( 5096): PreDiscoveryHelper.initializeAdvData - name selected: S5mini-1(8)
V/QuickConnect[1.1][2] ( 5096): CONTACT_Info.getMyMobileNumber - 
E/NetworkSettingsReceiver( 3914): onReceive: android.intent.action.BOOT_COMPLETED
,D/STATUSBAR-PhoneStatusBar( 2578): showHideQConnectLayout userID : 0 emMode:false mQconnectEnable:true QconnectService:true
D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceUnflagged message2131296811com.android.email.intent.messageviewfragment.favorite2130837558
W/BroadcastQueue( 2419): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.android.calendar/.magazine.CalendarUpdateRelatedDataReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/SELinux ( 5137): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5137):  
,D/QuickConnect[1.1][2] ( 5096): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5096): CONTACT_Info.getMyMobileNumber - null 
,D/QuickConnect[1.1][2] ( 5096): NetUtil.getP2pMacFromWifiMac - ($)
,V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceStarred message2131296815com.android.email.intent.messageviewfragment.favorite2130837560
I/SELinux ( 5137): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5137):  
I/SELinux ( 5137):  
,I/SELinux ( 5137): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5137): >>>>> Normal User
E/dalvikvm( 5137): >>>>> com.sec.android.app.camera [ userId:0 | appId:10149 ]
W/QuickConnect[1.1][2] ( 5096): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.emeeting.b2c.hancom
D/QuickConnect[1.1][2] ( 5096): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.emeeting
,E/SELinux ( 5137): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 5122): GC_CONCURRENT freed 3006K, 31% free 9562K/13764K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 5122): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/QuickConnect[1.1][2] ( 5096): AppPackageUtil.isStubApk - but Stub version[2.7.025] of com.samsung.groupcast
W/QuickConnect[1.1][2] ( 5096): AppPackageUtil.isAppInstalled - this is Stub - com.samsung.groupcast
,D/QuickConnect[1.1][2] ( 5096): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.samsung.groupcast
,W/QuickConnect[1.1][2] ( 5096): AppPackageUtil.isAppInstalled - Not installed - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5096): SconnectManager.setServiceCapability - [Downloaded App] Not installed!! - com.sec.android.sidesync30
,D/QuickConnect[1.1][2] ( 5096): PeriphService.registerUserReceiver - mIsUserReceiver == false
,I/QuickConnect[1.1][2] ( 5096): PeriphService.onStartCommand - USER_OWNER
I/QuickConnect[1.1][2] ( 5096): PeriphService.onStartCommand - Intent { act=com.samsung.android.sconnect.periph.START_SERVICE } flags[0] startId[1]
,I/QuickConnect[1.1][2] ( 5096): PeriphService.onStartCommand - Action: com.samsung.android.sconnect.periph.START_SERVICE
,D/TimaKeyStoreProvider( 5137): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5137): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5137): Added TimaKesytore provider
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceUnstarred message2131296816com.android.email.intent.messageviewfragment.favorite2130837560
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.UNCSearchResultsList
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.EmailDocSearchQuery
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.MessageViewDisplayModePopup
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SelectGroup
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SavedEmail
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.MessageFileView
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.pgp.CreateKeySettingsActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.spellscroll
,I/AMMetaDataParserService( 4782): Resource data:2131099689
,I/AMMetaDataParserService( 4782): getResourceName:com.android.email:xml/spellscroll
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.OoOSetMessage
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
,I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.searchable
,I/AMMetaDataParserService( 4782): Resource data:2131099685
,I/AMMetaDataParserService( 4782): getResourceName:com.android.email:xml/searchable
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
D/BtSettings.ProfileConfig( 5122): Adding GattService
D/BtSettings.ProfileConfig( 5122): Adding HeadsetService
D/BtSettings.ProfileConfig( 5122): Adding A2dpService
I/AMMetaDataParserService( 4782): getResourcePackageName:android.app.default_searchable
D/BtSettings.ProfileConfig( 5122): Adding HidService
,D/BtSettings.ProfileConfig( 5122): Adding HealthService
D/BtSettings.ProfileConfig( 5122): Adding PanService
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
D/BtSettings.ProfileConfig( 5122): Adding BluetoothMapService
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
,D/BtSettings.ProfileConfig( 5122): Adding SapService
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 4782): Resource data:Inside bundle  check
I/AMMetaDataParserService( 4782): getResourcePackageName:com.android.keyguard.layout
,I/AMMetaDataParserService( 4782): Resource data:2130903052
I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.app.camera:layout/keyguard_widget
,I/AMMetaDataParserService( 4782): getResourceTypeNamelayout
I/AMMetaDataParserService( 4782): getResourcePackageName:assistant
,I/AMMetaDataParserService( 4782): Resource data:2131034112
,I/AMMetaDataParserService( 4782): getResourceName:com.sec.android.app.camera:xml/assistant
,I/AMMetaDataParserService( 4782): getResourceTypeNamexml
,D/BluetoothAdapterService( 5122): REFCOUNT: CREATED. INSTANCE_COUNT1
D/dalvikvm( 5137): GC_CONCURRENT freed 3004K, 31% free 9567K/13764K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 5137): WAIT_FOR_CONCURRENT_GC blocked 15ms
W/dalvikvm( 5137): Refusing to reopen boot DEX '/system/framework/seccamera.jar'
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceSwitch camera2131428066android.intent.action.switchcamera2130837508
,D/BluetoothAdapterState( 5122): make
,I/bluedroid( 5122): init
,I/BluetoothAdapterState( 5122): Entering OffState
,D/        ( 4782): PNG_doEncode true 106, 106
,I/AMMetaDataParserService( 4782): Icon data: ResourceGallery2131427734android.intent.action.switchgallery2130837507
,I/ActivityManager( 2419): Killing 4222:com.sec.android.fotaclient/u0a11 (adj 15): empty #43
I/bte_conf( 5122): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
I/bluedroid( 5122): get_profile_interface socket
D/BluetoothAdapterService( 5122):  checkAddrForIOP: Loading from conf
I/GKI_LINUX( 5122): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
E/BluetoothServiceJni( 5122): populateRssiValuesNative
I/bluedroid( 5122): getModelRssiValues
E/BluetoothServiceJni( 5122): model_rssi_values_callback: low = -75, mid = -65, high = 127
I/SELinux ( 5154): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5154):  
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.camera.QuickShot
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,I/AMMetaDataParserService( 4782): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,I/ActivityManager( 2419): Killing 3462:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 5154): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5154):  
I/SELinux ( 5154):  
,I/SELinux ( 5154): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5154): >>>>> Normal User
,E/dalvikvm( 5154): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 5154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/bluedroid( 5122): config_hci_snoop_log
,D/BluetoothManagerService( 2419): Broadcasting onBluetoothServiceUp() to 11 receivers.
,D/TimaKeyStoreProvider( 5154): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5154): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5154): Added TimaKesytore provider
,D/BluetoothRadioManager( 5096): onBluetoothServiceUp: android.bluetooth.IBluetooth$Stub$Proxy@4230be28
,D/BluetoothRadioManager( 5096): onBluetoothServiceUp()  registerRadioClient mUUID = 541dbd5f-4daa-4b18-9b01-523ea5a865ea
,I/bluedroid( 5122): update_radio_count
,D/BluetoothAdapterState( 5122): CURRENT_STATE=OFF, MSG = USER_TURN_ON_RADIO
I/BluetoothAdapterState( 5122): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=false
D/BluetoothAdapterState( 5122): CURRENT_STATE=PENDING, MSG = BEGIN_ENABLE_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
,I/bluedroid( 5122): enable
,I/bt_hci_bdroid( 5122): init
I/bt_vendor( 5122): init
I/bt_vnd_conf( 5122): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 5122): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,I/bt_hci_bdroid( 5122): bt_hc_worker_thread started
,D/dalvikvm( 5154): GC_CONCURRENT freed 3000K, 31% free 9564K/13764K, paused 5ms+2ms, total 31ms
,D/dalvikvm( 5154): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/GKI_LINUX( 5122): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/bt_userial_vendor( 5122): userial vendor open: opening /dev/ttySAC0
I/bt_userial_vendor( 5122): userial_vendor_open():UART is setup
I/bt_userial_vendor( 5122): device fd = 56 open
,E/bt_hwcfg( 5122): Start CFG HW, HCI reset
,E/bt_hwcfg( 5122): Read Local Name after HCI reset
,D/bt_hwcfg( 5122): Chipset BCM4334B0
D/bt_hwcfg( 5122): Target name = [BCM4334B0]
,I/bt_hwcfg( 5122): module conf file not found; use default file extension .hcd
D/bt_hwcfg( 5122): Target name = [BCM4334]
I/bt_hwcfg( 5122): module conf file not found; use default file extension .hcd
I/bt_hwcfg( 5122): Found patchfile: BT_FW_VER_BCM4334B0_002.001.013.1792.1803_K_Mini.hcd
,I/bt_hwcfg( 5122): Axi patch failure or not include AXI patching
,I/bt_hwcfg( 5122): bt vendor lib: set UART baud 3000000
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{431c6818 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,D/BadgeProvider( 4158): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 4158): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4158): sendNotify, [notify] : null
D/BadgeProvider( 4158): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4158): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4158): update, [UpdateCount] : 1
,D/Launcher.Model( 2773): reloadBadges entered.
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5186): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5186):  
,I/ActivityManager( 2419): Killing 4242:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 8 sec
V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 5186): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5186):  
I/SELinux ( 5186):  
,I/SELinux ( 5186): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5186): >>>>> Normal User
E/dalvikvm( 5186): >>>>> com.android.exchange [ userId:0 | appId:10158 ]
E/SELinux ( 5186): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5186): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5186): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5186): Added TimaKesytore provider
,I/bt_hwcfg( 5122): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 5122): Settlement delay -- 100 ms
,I/Process ( 5154): Sending signal. PID: 5154 SIG: 9
,I/ActivityManager( 2419): Process com.android.email (pid 5154) (adj 9) has died.
,D/dalvikvm( 5186): GC_CONCURRENT freed 3011K, 31% free 9561K/13768K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 5186): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2718): GC_EXPLICIT freed 933K, 28% free 9982K/13752K, paused 3ms+8ms, total 46ms
,I/iu.UploadsManager( 3149): End new media; added: 0, uploading: 0, time: 163 ms
,I/bt_hwcfg( 5122): bt vendor lib: set UART baud 3000000
,I/SELinux ( 5201): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5201):  
,I/bt_hwcfg( 5122): vendor lib fwcfg completed
,D/GKI_LINUX( 5122): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
I/        ( 5122): BTE_InitTraceLevels -- TRC_HCI
I/        ( 5122): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5122): BTE_InitTraceLevels -- TRC_RFCOMM
,I/        ( 5122): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 5122): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5122): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5122): BTE_InitTraceLevels -- TRC_BNEP
,I/        ( 5122): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5122): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5122): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5122): BTE_InitTraceLevels -- TRC_SAP
,I/        ( 5122): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5122): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5122): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5122): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5122): BTE_InitTraceLevels -- TRC_BTIF
,I/        ( 5122): BTE_InitTraceLevels -- TRC_PROTOCOL
,I/SELinux ( 5206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5206):  
,I/SELinux ( 5201): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5201):  
I/SELinux ( 5201):  
,I/SELinux ( 5201): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5201): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5201): >>>>> Normal User
,E/dalvikvm( 5201): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 5201): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5201): in addTimaSignatureService
I/SELinux ( 5206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5206):  
I/SELinux ( 5206):  
,I/SELinux ( 5206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5206): >>>>> Normal User
E/dalvikvm( 5206): >>>>> com.android.email [ userId:0 | appId:10157 ]
,D/TimaKeyStoreProvider( 5201): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5201): Added TimaKesytore provider
,E/SELinux ( 5206): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5206): in addTimaSignatureService
,E/bt-btm  ( 5122): BTM_SecRegister:p_cb_info->p_le_callback == 0x77c0aaf9 
,E/bt-btm  ( 5122): BTM_SecRegister: btm_cb.api.p_le_callback = 0x77c0aaf9 
D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,E/bt-btif ( 5122): btif_storage_get_adapter_property service_mask:0x0
E/BluetoothServiceJni( 5122): populateRssiValuesNative
I/bluedroid( 5122): getModelRssiValues
,E/BluetoothServiceJni( 5122): model_rssi_values_callback: low = -75, mid = -65, high = 127
,D/TimaKeyStoreProvider( 5206): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5206): Added TimaKesytore provider
,E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager( 2419): Killing 4256:com.sec.android.app.mss/u0a21 (adj 15): empty #43
E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothAdapterProperties( 5122): Exception in onBondStateChanged : 
E/BluetoothAdapterProperties( 5122): java.lang.NullPointerException
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.onBondStateChanged(AdapterProperties.java:269)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.AdapterProperties.adapterPropertyChangedCallback(AdapterProperties.java:571)
E/BluetoothAdapterProperties( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.adapterPropertyChangedCallback(JniCallbacks.java:87)
E/BluetoothAdapterProperties( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): An exception was thrown by callback 'remote_device_properties_callback'.
E/BluetoothServiceJni( 5122): java.lang.NullPointerException
E/BluetoothServiceJni( 5122): 	at com.android.bluetooth.btservice.JniCallbacks.devicePropertyChangedCallback(JniCallbacks.java:53)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothServiceJni( 5122): 	at dalvik.system.NativeStart.run(Native Method)
E/bt-btif ( 5122): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
I/bt_hwcfg( 5122): hw_sco_disable_i2s_setting {0, 0, 0, 0}
I/bt_hwcfg( 5122): SCO PCM configure {0, 4, 0, 0, 0}
E/bt-btif ( 5122): btif_sock_init, radio_req:1, rfc_init:0, vhci_init:0
E/bt-btif ( 5122): btif_sock_init: !vhci_init
D/BluetoothAdapterState( 5122): CURRENT_STATE=PENDING, MSG = ENABLED_RADIO, isTurningOnRadio=true, isTurningOffRadio=false
D/BluetoothAdapterService(1109878392)( 5122): startQuietModeServices:bStart =true QModeRCnt=1
D/BluetoothBondStateMachine( 5122): make
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 5122): StableState(): Entering Off State
D/BluetoothAdapterService(1109878392)( 5122): startQuietModeServices:Starting  com.android.bluetooth.gatt.GattService
D/BluetoothSecureManager( 5122): getInstant: null
D/BluetoothSecureManager( 5122): calling getMethod for getService
D/BluetoothSecureManager( 5122): calling getService
D/BluetoothSecureManager( 5122): getService return binder: android.os.BinderProxy@422f0250
D/BluetoothSecureManagerService( 2419): isSecureModeEnabled
D/BluetoothSecureManagerService( 2419): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 5122): isSecureModeOn:false
D/BluetoothAdapterService( 5122): setProfileState(): setting profile com.android.bluetooth.gatt.GattService to state = 10
I/BtGatt.JNI( 5122): classInitNative(L703): classInitNative: Success!
E/bt_h4   ( 5122): vendor lib postload completed
E/bt_h4   ( 5122): vendor lib postload completed
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 5122): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
I/BluetoothAdapterState( 5122): Bluetooth adapter radio state changed: 14
D/BluetoothAdapterService( 5122): Bluetooth PBAP supproted is true
D/dalvikvm( 5201): GC_CONCURRENT freed 2998K, 31% free 9569K/13764K, paused 4ms+3ms, total 41ms
D/dalvikvm( 5201): WAIT_FOR_CONCURRENT_GC blocked 34ms
D/BluetoothAdapterService( 5122): updateAdapterState state is 14
D/BluetoothAdapterService( 5122): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService( 2419): Broadcasting Radio() to 1 Radio Mgr receivers.
D/BluetoothRadioManager( 5096): onBTRadioStateChange:  up = true
D/BluetoothAdapterService( 5122): Autoconnection is available 
D/BluetoothAdapterService( 5122): updateAdapterState prevState = 10newState = 14
I/BluetoothAdapterState( 5122): Entering OffState
D/BtGatt.GattService( 5122): BluetoothAdapter state is = 10
D/BtGatt.DebugUtils( 5122): handleDebugAction() action=null
D/BtGatt.GattService( 5122): Received start request. Starting profile...
D/BtGatt.GattService( 5122): start()
I/bluedroid( 5122): get_profile_interface gatt
,I/BluetoothManagerService( 2419): enableGatt, doBind called
D/BluetoothManagerService( 2419): Broadcasting onBluetoothServiceUp() to 1 receivers.
D/BluetoothRadioManager( 5096): onGattServiceStateChange: up = truemBleCount = 1
E/QuickConnect[1.1][2] ( 5096): BleHelper.onGattServiceStateChange - up = true, BluetoothGatt is android.bluetooth.IBluetoothGatt$Stub$Proxy@4230cbf8
E/QuickConnect[1.1][2] ( 5096): BleHelper.onGattServiceStateChange - Radio turned on
,D/dalvikvm( 5206): GC_CONCURRENT freed 3001K, 31% free 9572K/13768K, paused 8ms+2ms, total 31ms
,D/dalvikvm( 5206): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 5230): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5230):  
,I/ActivityManager( 2419): Killing 4270:com.sec.android.app.msa/u0a23 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 12% free 9502K/10744K, paused 3ms+4ms, total 39ms
,I/SELinux ( 5230): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5230):  
I/SELinux ( 5230):  
,I/SELinux ( 5230): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5230): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5230): >>>>> Normal User
,E/dalvikvm( 5230): >>>>> com.sec.modem.settings [ userId:0 | appId:1000 ]
,E/SELinux ( 5230): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5230): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 3ms+3ms, total 37ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 5230): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5230): Added TimaKesytore provider
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 2ms+3ms, total 27ms
,D/dalvikvm( 5230): GC_CONCURRENT freed 3004K, 31% free 9565K/13768K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 5230): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 5250): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5250):  
,I/ActivityManager( 2419): Killing 4285:com.samsung.android.MtpApplication/1000 (adj 15): empty #43
I/Process ( 5186): Sending signal. PID: 5186 SIG: 9
D/BadgeProvider( 4158): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/BadgeProvider( 4158): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4158): sendNotify, [notify] : null
D/BadgeProvider( 4158): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2773): reloadBadges entered.
D/BadgeProvider( 4158): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4158): update, [UpdateCount] : 1
,I/SELinux ( 5250): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5250):  
I/SELinux ( 5250):  
,I/SELinux ( 5250): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5250): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5250): >>>>> Normal User
,E/dalvikvm( 5250): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 5250): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/ActivityManager( 2419): Process com.android.exchange (pid 5186) (adj 9) has died.
,D/TimaKeyStoreProvider( 5250): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5250): Cannot add TimaSignature Service, License check Failed
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/ActivityThread( 5250): Added TimaKesytore provider
,I/QuickConnect[1.1][2] ( 5096): BleAdvertiser.BleAdvertiser - Constructor
,D/BluetoothGattServer( 5096): registerCallback()
,D/BluetoothGattServer( 5096): registerCallback() - UUID=80dbff42-85d6-48bc-b3c8-af9bfd1b7ef5
,D/BtGatt.GattService( 5122): registerServer() - UUID=80dbff42-85d6-48bc-b3c8-af9bfd1b7ef5
D/BtGatt.btif( 5122): btif_gatts_register_app
D/BtGatt.btif( 5122): btgatts_handle_event: Event 2000
E/bt-btif ( 5122): register application first_unuse rcb_idx = 0
,D/BtGatt.btif( 5122): btapp_gatts_handle_cback: Event 0
,D/BtGatt.GattService( 5122): onServerRegistered() - UUID=80dbff42-85d6-48bc-b3c8-af9bfd1b7ef5, serverIf=4
,D/BluetoothGattServer( 5096): onServerRegistered() - status=0 serverIf=4
V/QuickConnect[1.1][2] ( 5096): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5096): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
,V/QuickConnect[1.1][2] ( 5096): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
V/QuickConnect[1.1][2] ( 5096): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b16a0
,D/QuickConnect[1.1][2] ( 5096): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5096): BleHelper.startScan - bluetoothActionState = 0
,D/QuickConnect[1.1][2] ( 5096): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5096): BleHelper.startScan - shouldScanBleFg = false
,D/dalvikvm( 5250): GC_CONCURRENT freed 3025K, 31% free 9548K/13768K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 5250): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 9 sec
,D/dalvikvm( 2419): GC_EXPLICIT freed 1240K, 19% free 24118K/29708K, paused 9ms+13ms, total 186ms
,D/NotiRemoteService( 5250): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/NotiRemoteService( 5250): connectToPeelService 0
,W/ContextImpl( 5250): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:529 tv.peel.samsung.widget.a.c.<init>:68 tv.peel.samsung.widget.NotiRemoteService.a:554 
,I/SELinux ( 5271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5271):  
,D/NotiRemoteService( 5250): onServiceOn() mServiceState = 1
,D/NotiRemoteService( 5250): Send action to self com.peel.widget.notification.SERVICE_BINDED
,D/NotiRemoteService( 5250): action com.peel.widget.notification.SERVICE_BINDED
D/NotiRemoteService( 5250): feature is Off. Stop service
,D/NotiRemoteService( 5250): Send action to self com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5250): action com.peel.widget.notification.STOP_PROCESS
,D/NotiRemoteService( 5250): onDestroy()
,D/NotiRemoteService( 5250): mOrientationChangeReceier was not registered
,I/SELinux ( 5271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5271):  
I/SELinux ( 5271):  
,I/SELinux ( 5271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5271): >>>>> Normal User
,E/dalvikvm( 5271): >>>>> org.simalliance.openmobileapi.service [ userId:0 | appId:1101 ]
,E/SELinux ( 5271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5271): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5271): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5271): Added TimaKesytore provider
,D/dalvikvm( 5271): GC_CONCURRENT freed 3001K, 31% free 9570K/13768K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 5271): WAIT_FOR_CONCURRENT_GC blocked 30ms
,V/SmartcardService( 5271): main Received broadcast
,V/SmartcardService( 5271): Starting smartcard service after boot completed
,I/ActivityManager( 2419): Killing 4298:com.android.onetimeinitializer/u0a28 (adj 15): empty #43
,D/SensorService( 2419):   0.3 0.0 9.9
,I/SELinux ( 5285): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5285):  
,I/SELinux ( 5285): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5285):  
I/SELinux ( 5285):  
,I/SELinux ( 5285): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5285): >>>>> Normal User
,E/dalvikvm( 5285): >>>>> com.sec.android.app.sysscope [ userId:0 | appId:1000 ]
,E/SELinux ( 5285): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5285): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5285): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5285): Added TimaKesytore provider
,D/dalvikvm( 5285): GC_CONCURRENT freed 3004K, 31% free 9565K/13764K, paused 6ms+2ms, total 35ms
,D/dalvikvm( 5285): WAIT_FOR_CONCURRENT_GC blocked 25ms
,W/ContextImpl( 5285): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 5298): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5298):  
,I/SELinux ( 5298): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5298):  
I/SELinux ( 5298):  
,I/SELinux ( 5298): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5298): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 5298): >>>>> Normal User
,E/dalvikvm( 5298): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 5298): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 5298): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5298): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5298): Added TimaKesytore provider
,D/dalvikvm( 5298): GC_CONCURRENT freed 3002K, 31% free 9566K/13764K, paused 2ms+2ms, total 25ms,
,D/dalvikvm( 5298): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/SELinux ( 5310): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5310):  
,I/ActivityManager( 2419): Killing 4312:com.sec.pcw.device/1000 (adj 15): empty #43,
,D/BluetoothAdapterService(1109878392)( 5122): unRegister RemoteMessageListener
,D/BluetoothAdapterState( 5122): CURRENT_STATE=OFF, MSG = USER_TURN_OFF,
,I/WifiManager( 4858): packageName : com.example.hello,
,I/WifiManager( 4858): setWifiEnabled : false
,I/WifiService( 2419): setWifiEnabled: false pid=4858, uid=10509
,I/jxcore-log( 4858): ****TEST TOOK:  5148  ms ****
I/jxcore-log( 4858): 
,I/jxcore-log( 4858): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4858): 
,I/SELinux ( 5310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5310):  
I/SELinux ( 5310):  
,I/SELinux ( 5310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,E/dalvikvm( 5310): >>>>> Normal User
E/dalvikvm( 5310): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 5310): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 5310): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5310): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5310): Added TimaKesytore provider
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 10 sec,
,D/dalvikvm( 5310): GC_CONCURRENT freed 2999K, 31% free 9572K/13768K, paused 5ms+2ms, total 29ms,
,D/dalvikvm( 5310): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Intent to TravelDirActivity( 5310): inside TravelBroadcastReceiver,
,I/GAV2    ( 4996): Thread[GAThread,5,main]: No campaign data found.,
,I/SELinux ( 5327): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5327):  
I/ActivityManager( 2419): Killing 4338:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/SELinux ( 5327): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 5327):  
I/SELinux ( 5327):  
,I/SELinux ( 5327): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 5327): >>>>> Normal User,
,E/dalvikvm( 5327): >>>>> com.sec.android.daemonapp [ userId:0 | appId:10173 ],
,E/SELinux ( 5327): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/TimaKeyStoreProvider( 5327): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 5327): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 5327): Added TimaKesytore provider
,D/dalvikvm( 5327): GC_CONCURRENT freed 2985K, 31% free 9578K/13764K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 5327): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/comsamsungapp( 5327): [MSC_Daemon]>>> KWCP:218 [0:0] KWeather Provider Created
,D/comsamsungapp( 5327): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WCP:1080 [0:0] Provider Created
,D/comsamsungapp( 5327): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5327): [MSC_Daemon]>>> CCP:223 [0:0] CmaWeather Provider Created
,D/comsamsungapp( 5327): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WNCP:204 [0:0] WeatherNewsJP Provider Created
,D/comsamsungapp( 5327): [MSC_Daemon]>>> AOH:53 [0:0] OpenHelper : 62
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/settings
,D/AndroidRuntime( 5323): 
D/AndroidRuntime( 5323): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5323): CheckJNI is OFF
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://daemonappapaccuweatherprovider/weatherinfo
,D/AndroidRuntime( 5323): setted country_code = Poland
,D/AndroidRuntime( 5323): setted countryiso_code = PL
,D/AndroidRuntime( 5323): setted sales_code = PLS
D/AndroidRuntime( 5323): readGMSProperty: start
,D/AndroidRuntime( 5323): readGMSProperty: already setted!!
,D/AndroidRuntime( 5323): readGMSProperty: end
,D/AndroidRuntime( 5323): addProductProperty: start
,D/comsamsungapp( 5327): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionBOOT_COMPLETED, run:false
D/comsamsunglog( 5327): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5327): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5327): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5327): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5327): [MSC_Daemon]>>> WDSM:48 [0:0] WeatherClockService start : 
,D/daemonapp( 5327): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5327): [MSC_Daemon]>>> WDSM:87 [0:0] ABOOTCOPLD
,D/dalvikvm( 5323): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 5323): Added shared lib libjavacore.so 0x0
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,W/BackupManagerService( 2419): dataChanged but no participant pkg='com.android.providers.settings' uid=10173
D/dalvikvm( 5323): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 5323): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 5323): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/daemonapp( 5327): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1761 [0:0] [boot]now           :1449497319319
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1762 [0:0] [boot]NUT :1449493980000
D/daemonapp( 5327): [MSC_Daemon]>>> WU:1763 [0:0] [boot]interval       :3 (21600000 ms)
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1764 [0:0] [boot]NUT - now :false
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1567 [0:0] CnclAtRftAl
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1633 [0:0] [setARfAam]now :1449497319335
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1635 [0:0] [setARfAam]LUT :144949731933521600000
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1637 [0:0] [setARfAam]interval       :3
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1639 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1422 [0:0] util getnext by config 1449518880000
,D/daemonapp( 5327): [MSC_Daemon]>>> WDBH:2157 [0:0] ud NT1449518880000
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1212 [0:0] cp update : count : 1, pt : 7
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:1644 [0:0] [dbset]NT       :1449518880000
,D/daemonapp( 5327): [MSC_Daemon]>>> WCS:40 [0:0] onStartcommand()
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5327): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5327): [MSC_Daemon]>>> WCS:63 [0:0] CP Name cp_eng
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5327): [MSC_Daemon]>>> WCS:82 [0:0] td null
,D/comdaemonstockapp( 5327): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 5327): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/SELinux ( 5347): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5347):  
,I/SELinux ( 5347): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5347):  
I/SELinux ( 5347):  
,I/SELinux ( 5347): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5347): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5347): >>>>> Normal User
,E/dalvikvm( 5347): >>>>> com.gameloft.android.GloftGF2H [ userId:0 | appId:10179 ]
,E/SELinux ( 5347): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/memtrack( 5323): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 5323): failed to load memtrack module: -2
,D/TimaKeyStoreProvider( 5347): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5347): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5347): Added TimaKesytore provider
,D/dalvikvm( 5323): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/PowerManagerService( 2419): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2419): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2419): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/dalvikvm( 5347): GC_CONCURRENT freed 3014K, 31% free 9559K/13768K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 5347): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/lights  ( 2419): lcd : 2 +
D/RampAnimator( 2419): Light Animator Finished currentValue=2
,D/lights  ( 2419): lcd : 2 -
,I/SELinux ( 5362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5362):  
,I/ActivityManager( 2419): Killing 4377:com.sec.android.service.health/u0a16 (adj 15): empty #43
,D/AndroidRuntime( 5323): Calling main entry com.android.commands.pm.Pm
,I/SELinux ( 5362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5362):  
I/SELinux ( 5362):  
,I/SELinux ( 5362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/PackageManager( 2419): START PACKAGE DELETE: observer{1121162664}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
E/dalvikvm( 5362): >>>>> Normal User
E/dalvikvm( 5362): >>>>> com.gameloft.android.GloftKLMF [ userId:0 | appId:10180 ]
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2419): deletePackageX- pkg:com.example.hello, userId:0
,E/SELinux ( 5362): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
,D/TimaKeyStoreProvider( 5362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5362): Added TimaKesytore provider
D/PackageManager( 2419): !@killApplicatoin: 10509, uninstall pkg
I/ActivityManager( 2419): Killing 4858:com.example.hello/u0a509 (adj 0): stop com.example.hello
,I/WindowState( 2419): WIN DEATH: Window{430572d8 u0 com.example.hello/com.example.hello.MainActivity}
I/SurfaceFlinger( 1921): id=17 Removed NainActivit (8/9)
I/SurfaceFlinger( 1921): id=17 Removed NainActivit (-2/9)
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2419): Skipping PackageSetting{427b9320 com.test.thalitest/10508} due to missing metadata
,D/PackageManager( 2419): queryIntentReceivers - Execution time: 117 ms
,I/SurfaceFlinger( 1921): id=15 Removed EimLayer (6/8)
I/SurfaceFlinger( 1921): id=15 Removed EimLayer (-2/8)
,I/SurfaceFlinger( 1921): id=14 Removed EimLayer (5/7)
,I/SurfaceFlinger( 1921): id=14 Removed EimLayer (-2/7)
W/ActivityManager( 2419): Force removing ActivityRecord{43452bd8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10509, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/SQLiteSecureOpenHelper( 4117): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4117): getDatabaseLocked(b,b,pwd)...
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.acquire()
,V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowOrientationListener( 2419): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.example.hello flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10509, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Launcher( 2773): onRestart, Launcher: 1110133920
D/Launcher( 2773): onStart, Launcher: 1110133920
,D/Launcher.HomeView( 2773): onStart
,D/Launcher( 2773): onResume, Launcher: 1110133920
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/Launcher.HomeView( 2773): onResume
D/StatusBarManagerService( 2419): semi p:2773,o:f
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2773,o:f
D/StatusBarManagerService( 2419): semi p:2773,o:f
,D/dalvikvm( 5362): GC_CONCURRENT freed 2993K, 31% free 9568K/13760K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 5362): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 2990): GC_EXPLICIT freed 1297K, 28% free 10012K/13764K, paused 4ms+5ms, total 60ms
,E/SamsungIME( 2966): mOCRHelper is null
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 11 sec
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 5096): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.example.hello
,W/GeofencerStateMachine( 2733): Ignoring removeGeofence because network location is disabled.
,D/RCPManagerService( 2419): PackageReceiver onReceive(),
,D/MenuAppsGridFragment( 2773): onResume,
,I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0,
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms",
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/SurfaceFlinger( 1921): id=18 createSurf (720x1280),1 flag=4, Mauncher,
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/RegisteredServicesCache( 2755): empty dynamic service
D/StatusBarManagerService( 2419): tr p:2773,o:f
,D/StatusBarManagerService( 2419): semi p:2773,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/dalvikvm( 2419): Jit: resizing JitTable from 8192 to 16384
,D/PackageManager( 2419): checkUidPermission - Execution time: 161 ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2419): GC_EXPLICIT freed 1540K, 19% free 24252K/29708K, paused 16ms+61ms, total 281ms
,I/SELinux ( 5378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5378):  
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2419): Killing 4541:com.policydm/1000 (adj 15): empty #43
,I/SELinux ( 5378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5378):  
I/SELinux ( 5378):  
,I/SELinux ( 5378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 5378): >>>>> Normal User
,E/dalvikvm( 5378): >>>>> com.gameloft.android.GloftPSHU [ userId:0 | appId:10181 ]
,E/SELinux ( 5378): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PackageManager( 2419): delete sourFile : 
,D/TimaKeyStoreProvider( 5378): in addTimaSignatureService
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4,
,D/TimaKeyStoreProvider( 5378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5378): Added TimaKesytore provider
W/ActivityManager( 2419): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2755): GC_CONCURRENT freed 2312K, 26% free 10251K/13756K, paused 4ms+2ms, total 45ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/PackageManager( 2419): delete native library directory: 
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 4858 uid 10509
D/PackageManager( 2419): return delete result to caller: 1121162664
,D/PackageManager( 2419): returnCode: 1
D/AndroidRuntime( 5323): Shutting down VM
,D/dalvikvm( 5323): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 3ms
,D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 5378): GC_CONCURRENT freed 2997K, 31% free 9568K/13764K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 5378): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10509 #1
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5392):  
I/ActivityManager( 2419): Killing 4557:com.osp.app.signin/u0a44 (adj 15): empty #43
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 5392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5392):  
I/SELinux ( 5392):  
,I/SELinux ( 5392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5392): >>>>> Normal User
,E/dalvikvm( 5392): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 5392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 5392): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5392): Added TimaKesytore provider
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(4)
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 5392): GC_CONCURRENT freed 2994K, 31% free 9576K/13764K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 5392): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2419): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 2419): clearDefaults: com.example.hello
,W/AtomicFile( 2419): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,W/AppWidgetServiceImpl( 2419): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/dalvikvm( 5392): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 5392): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0008
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
E/dalvikvm( 5392): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0000
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 2773): SEC_PRODUCT_FEATURE_COMMON_ENABLE_TEXTURE_COMPRESSION is true
,E/dalvikvm( 5392): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0037
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 12 sec
,W/System.err( 4631): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:455)
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(38)
W/System.err( 4631): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
,W/System.err( 4631): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
,W/System.err( 4631): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4631): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4631): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4631): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4631): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4631): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
,W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4631): 	... 11 more
,W/ApplicationsProvider( 2990): Could not fetch usage stats
W/ApplicationsProvider( 2990): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2990): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2990): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2990): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2990): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2990): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2990): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2990): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2990): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2990): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2990): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5392): Link of class 'Ldqp;' failed
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5392): Link of class 'Ldqp;' failed
I/dalvikvm( 5392): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 5392): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5392): Link of class 'Ldqp;' failed
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5392): Link of class 'Ldqp;' failed
I/dalvikvm( 5392): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 5392): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
D/dalvikvm( 5392): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 5392): Link of class 'Ldqp;' failed
W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 5392): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 5392): Link of class 'Ldqp;' failed
I/dalvikvm( 5392): Could not find method dqp.d, referenced from method g.a
,W/dalvikvm( 5392): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0003,
W/dalvikvm( 5392): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 5392): Link of class 'Lax;' failed
E/dalvikvm( 5392): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;,
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0006,
W/dalvikvm( 5392): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 5392): Link of class 'Laz;' failed
,E/dalvikvm( 5392): Could not find class 'az', referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;,
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x002c,
I/dalvikvm( 5392): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I,
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0008,
,I/dalvikvm( 5392): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a,
W/dalvikvm( 5392): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x000c,
I/dalvikvm( 5392): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0006,
I/dalvikvm( 5392): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 5392): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 5392): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5392): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
,W/dalvikvm( 5392): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 5392): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 5392): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 5392): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z,
,D/dalvikvm( 5392): VFY: replacing opcode 0x72 at 0x0000,
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5392): Could not find class 'android.app.RemoteInput[]', referenced from method g.a,
W/dalvikvm( 5392): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x23 at 0x0005,
,I/dalvikvm( 5392): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b,
W/dalvikvm( 5392): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0009,
,W/dalvikvm( 5392): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764),
W/dalvikvm( 5392): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed,
E/dalvikvm( 5392): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 5392): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x1c at 0x0002,
E/dalvikvm( 5392): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 5392): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 5392): VFY: replacing opcode 0x1f at 0x000c,
,D/dalvikvm( 5392): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 5392): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5392): VFY: replacing opcode 0x62 at 0x0006,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a,
W/dalvikvm( 5392): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 5392): Link of class 'Lax;' failed,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a,
W/dalvikvm( 5392): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 5392): Link of class 'Laz;' failed,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a,
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l,
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0),
,D/dalvikvm( 5392): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227d900,
,D/dalvikvm( 5392): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227d900,
,D/GKI_LINUX( 5122): release_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0,
,I/dalvikvm( 5392): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b,
,W/dalvikvm( 5392): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0076,
,I/Babel_SMS( 5392): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5392): MmsConfig.loadMmsSettings
I/Babel_SMS( 5392): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 5392): MmsConfig.loadFromDatabase
,E/SQLiteDatabase( 5392): Failed to open database '/data/data/com.google.android.talk/databases/apn.db'.
E/SQLiteDatabase( 5392): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5392): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5392): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5392): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5392): 	at alg.<init>(SourceFile:161)
E/SQLiteDatabase( 5392): 	at alj.a(SourceFile:1015)
E/SQLiteDatabase( 5392): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/SQLiteDatabase( 5392): 	at gvf.d(SourceFile:408)
E/SQLiteDatabase( 5392): 	at gvf.b(SourceFile:238)
E/SQLiteDatabase( 5392): 	at gvf.a(SourceFile:204)
E/SQLiteDatabase( 5392): 	at gvf.a(SourceFile:485)
E/SQLiteDatabase( 5392): 	at alg.a(SourceFile:167)
E/SQLiteDatabase( 5392): 	at dnm.c(SourceFile:606)
E/SQLiteDatabase( 5392): 	at dnm.b(SourceFile:570)
E/SQLiteDatabase( 5392): 	at dnn.run(SourceFile:221)
,W/dalvikvm( 5392): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5392): FATAL EXCEPTION: Thread-444
E/AndroidRuntime( 5392): Process: com.google.android.talk, PID: 5392
E/AndroidRuntime( 5392): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5392): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5392): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5392): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5392): 	at alg.<init>(SourceFile:161)
E/AndroidRuntime( 5392): 	at alj.a(SourceFile:1015)
E/AndroidRuntime( 5392): 	at gen_binder.root.RootModule$Generated.a(SourceFile:662)
E/AndroidRuntime( 5392): 	at gvf.d(SourceFile:408)
E/AndroidRuntime( 5392): 	at gvf.b(SourceFile:238)
E/AndroidRuntime( 5392): 	at gvf.a(SourceFile:204)
E/AndroidRuntime( 5392): 	at gvf.a(SourceFile:485)
E/AndroidRuntime( 5392): 	at alg.a(SourceFile:167)
E/AndroidRuntime( 5392): 	at dnm.c(SourceFile:606)
E/AndroidRuntime( 5392): 	at dnm.b(SourceFile:570)
E/AndroidRuntime( 5392): 	at dnn.run(SourceFile:221)
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop205.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,W/dalvikvm( 5392): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5392): Link of class 'Lfzc;' failed
E/dalvikvm( 5392): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 5392): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 5392): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 5392): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 5392): VFY: replacing opcode 0x74 at 0x006d
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
I/dalvikvm( 5392): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 5392): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 5392): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 5392): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 5392): Link of class 'Lfzc;' failed
D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
W/ServiceManager( 2419): Permission failure: com.samsung.permission.SSENSOR from uid=10109 pid=5392
D/PermissionCache( 2419): checking com.samsung.permission.SSENSOR for uid=10109 => denied (251 us)
E/SensorService( 2419): Permission Denial : SEC Private Sensor 
E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=4, ualk
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/dalvikvm( 5392): GC_CONCURRENT freed 1814K, 22% free 10842K/13844K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 5392): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/Settings( 5392): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(8)
,I/Babel_Crash( 5392): startup - clean
,I/Babel   ( 5392): deleted: false for 0
,I/dalvikvm( 5392): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 5392): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 5392): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 5392): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5392): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
,W/dalvikvm( 5392): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 5392): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 5392): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 5392): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 5392): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 5392): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 5392): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,F/PackageManager( 2419): Unable to backup user packages state file, current changes will be lost at reboot
D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/DropBoxManagerService( 2419): Can't write: system_server_wtf
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2419): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2419): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2419): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2419): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.PackageManagerService$PackageHandler.doHandleMessage(PackageManagerService.java:1223)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.PackageManagerService$PackageHandler.handleMessage(PackageManagerService.java:815)
E/DropBoxManagerService( 2419): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DropBoxManagerService( 2419): 	at android.os.Looper.loop(Looper.java:146)
E/DropBoxManagerService( 2419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 17 more
,I/SELinux ( 5418): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 5418):  
E/dalvikvm( 5392): Could not find class 'android.content.pm.LauncherApps', referenced from method cbk.a
W/dalvikvm( 5392): VFY: unable to resolve check-cast 469 (Landroid/content/pm/LauncherApps;) in Lcbk;
,D/dalvikvm( 5392): VFY: replacing opcode 0x1f at 0x0014,
,I/dalvikvm( 5392): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
,W/dalvikvm( 5392): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 5392): VFY: replacing opcode 0x6e at 0x0074
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9502K/10744K, paused 6ms+3ms, total 37ms
,I/ActivityManager( 2419): Killing 4573:com.android.providers.calendar/u0a45 (adj 15): empty #43
I/SELinux ( 5418): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5418):  
I/SELinux ( 5418):  
I/SELinux ( 5418): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5418): >>>>> Normal User
E/dalvikvm( 5418): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
E/SELinux ( 5418): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/vclib   ( 5392): onServiceConnected
W/Babel   ( 5392): Attempted to change video mute state without an active call.
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 2ms+3ms, total 28ms
,D/TimaKeyStoreProvider( 5418): in addTimaSignatureService
,D/TimaKeyStoreProvider( 5418): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 5418): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9502K/10744K, paused 2ms+3ms, total 28ms
,E/SQLiteDatabase( 2845): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 2845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 2845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.playlog.store.r.b(SourceFile:406)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.playlog.store.r.a(SourceFile:301)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.playlog.service.d.a(SourceFile:126)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/SQLiteDatabase( 2845): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2845): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2845): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/SQLiteDatabase( 2845): 	at java.lang.Thread.run(Thread.java:841)
,D/SensorService( 2419):   0.3 0.0 9.8
,E/PlayLogIntentService( 2845): not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PlayLogIntentService( 2845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PlayLogIntentService( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PlayLogIntentService( 2845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PlayLogIntentService( 2845): 	at com.google.android.gms.playlog.store.r.b(SourceFile:406)
E/PlayLogIntentService( 2845): 	at com.google.android.gms.playlog.store.r.a(SourceFile:301)
E/PlayLogIntentService( 2845): 	at com.google.android.gms.playlog.service.d.a(SourceFile:126)
E/PlayLogIntentService( 2845): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/PlayLogIntentService( 2845): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/PlayLogIntentService( 2845): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/PlayLogIntentService( 2845): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/PlayLogIntentService( 2845): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 3149): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3149): threadid=42: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 3149): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 3149): Process: com.google.android.gms, PID: 3149
E/AndroidRuntime( 3149): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3149): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 3149): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$ImageCleaner.performCleanup(PlayGamesContentProvider.java:1865)
E/AndroidRuntime( 3149): 	at com.google.android.gms.games.provider.PlayGamesContentProvider.performBackgroundTask(PlayGamesContentProvider.java:1671)
E/AndroidRuntime( 3149): 	at com.google.android.gms.games.provider.PlayGamesContentProvider$1.handleMessage(PlayGamesContentProvider.java:1586)
E/AndroidRuntime( 3149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3149): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3149): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop208.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
D/dalvikvm( 5418): GC_CONCURRENT freed 2998K, 31% free 9569K/13764K, paused 5ms+1ms, total 26ms
D/dalvikvm( 5418): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/dalvikvm( 5392): GC_CONCURRENT freed 988K, 16% free 11893K/14084K, paused 9ms+2ms, total 45ms
D/dalvikvm( 5392): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, hms
,D/dalvikvm( 5392): GC_FOR_ALLOC freed 556K, 18% free 12401K/14980K, paused 32ms, total 32ms
,D/dalvikvm( 5392): GC_FOR_ALLOC freed 1759K, 23% free 12772K/16572K, paused 26ms, total 26ms
,E/dalvikvm( 5418): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 5418): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 5418): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5418): Link of class 'Lal;' failed
E/dalvikvm( 5418): Could not find class 'al', referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 5418): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 5418): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 5418): Link of class 'Lan;' failed
E/dalvikvm( 5418): Could not find class 'an', referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 5418): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 5418): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 5418): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 5418): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 5418): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 5418): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 5418): VFY: replacing opcode 0x23 at 0x0005
,I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 13 sec
,W/System.err( 4631): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4631): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4631): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
,W/System.err( 4631): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
,W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
,W/System.err( 4631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4631): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
,W/System.err( 4631): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 4631): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.Posix.writeBytes(Native Method)
,W/System.err( 4631): 	at libcore.io.Posix.write(Posix.java:202)
,W/System.err( 4631): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:450)
,W/System.err( 4631): 	... 11 more
,D/dalvikvm( 5418): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm( 5418): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 5418): Link of class 'Lal;' failed
D/dalvikvm( 5418): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 5418): Unable to resolve superclass of Lan; (749)
,W/dalvikvm( 5418): Link of class 'Lan;' failed
D/dalvikvm( 5418): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 5418): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm( 5418): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 5418): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5418): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5418): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5418): VFY: unable to resolve instance field 46
,D/dalvikvm( 5418): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 5418): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5418): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5418): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5418): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 5418): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
,D/dalvikvm( 5418): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42335a40
,D/dalvikvm( 5418): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42335a40
,D/dalvikvm( 5418): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42335a40, skipping init
,D/dalvikvm( 5418): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42335a40
D/dalvikvm( 5418): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42335a40
,V/JNIHelp ( 5418): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/dalvikvm( 5418): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42335a40
D/dalvikvm( 5418): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42335a40
,D/dalvikvm( 5418): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42335a40
,D/dalvikvm( 5418): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42335a40
,I/dalvikvm( 5418): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 5418): VFY: unable to resolve static method 1165: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 5418): VFY: replacing opcode 0x71 at 0x0046
,E/android.os.Debug( 2419): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,I/dumpstate( 5445): begin
,I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5418): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 5418): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5418): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0220
,I/ProviderInstaller( 5418): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 5418): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
,E/SQLiteLog( 3149): (3850) statement aborts at 168: [DELETE FROM FileContent154 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
E/DocListDatabase( 3149): Failed to delete from FileContent154 table,
E/DocListDatabase( 3149): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 3149): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 3149): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/DocListDatabase( 3149): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 3149): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 3149): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
,E/DocListDatabase( 3149): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 3149): 	at com.google.android.gms.drive.database.f.a(SourceFile:984)
E/DocListDatabase( 3149): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 3149): 	at com.google.android.gms.drive.j.ag.run(SourceFile:51)
E/DocListDatabase( 3149): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 3149): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 3149): ,	at java.lang.Thread.run(Thread.java:841)
W/ContextImpl( 5418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/dalvikvm( 3149): threadid=34: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 3149): Sending signal. PID: 3149 SIG: 9,
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/ActivityManager( 2419): Process com.google.android.gms (pid 3149) (adj 1) has died.,
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,E/ViewRootImpl( 2419): sendUserActionEvent() mView == null
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,D/dalvikvm( 5418): GC_CONCURRENT freed 1922K, 23% free 10716K/13832K, paused 4ms+5ms, total 49ms
,I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 5418): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 5418): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 5418): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 5418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5418): 	at ghq.a(SourceFile:1037)
E/SQLiteDatabase( 5418): 	at ghq.a(SourceFile:1060)
E/SQLiteDatabase( 5418): 	at glm.b(SourceFile:152)
E/SQLiteDatabase( 5418): 	at glp.run(SourceFile:128)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5418): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5418): 	at java.lang.Thread.run(Thread.java:841)
,W/ContextImpl( 5418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.google.android.youtube/databases/com.google.android.libraries.youtube.common.task.ScheduledTaskStore'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5418): 	at ghq.b(SourceFile:1110)
E/SQLiteDatabase( 5418): 	at glm.a(SourceFile:139)
E/SQLiteDatabase( 5418): 	at glo.run(SourceFile:116)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5418): 	at goz.run(SourceFile:40)
E/SQLiteDatabase( 5418): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5418): Couldn't open com.google.android.libraries.youtube.common.task.ScheduledTaskStore for writing (will try read-only):
E/SQLiteOpenHelper( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5418): 	at ghq.b(SourceFile:1110)
E/SQLiteOpenHelper( 5418): 	at glm.a(SourceFile:139)
E/SQLiteOpenHelper( 5418): 	at glo.run(SourceFile:116)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5418): 	at goz.run(SourceFile:40)
E/SQLiteOpenHelper( 5418): 	at java.lang.Thread.run(Thread.java:841)
I/SELinux ( 5475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 5475):  
W/SQLiteOpenHelper( 5418): Opened com.google.android.libraries.youtube.common.task.ScheduledTaskStore in read-only mode
W/InstanceID/Rpc( 5418): Found 10012
E/android.os.Debug( 2419): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
I/SELinux ( 5475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 5475):  
I/SELinux ( 5475):  
I/SELinux ( 5475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 5475): >>>>> Normal User
E/dalvikvm( 5475): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
E/SELinux ( 5475): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 5418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
I/dumpstate( 5479): begin
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/TimaKeyStoreProvider( 5475): in addTimaSignatureService
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaKeyStoreProvider( 5475): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 5475): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 2578): checkOverflow(384), More:false, Req:false Child:2
I/SurfaceFlinger( 1921): id=20 Removed hms (8/9)
I/SurfaceFlinger( 1921): id=20 Removed hms (-2/9)
I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
I/AdvertisingIdClient( 5418): GMS remote exception 
I/AdvertisingIdClient( 5418): android.os.DeadObjectException
I/AdvertisingIdClient( 5418): 	at android.os.BinderProxy.transact(Native Method)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.identifier.a.f.a(SourceFile:114)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.identifier.a.a(SourceFile:266)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.u.f(SourceFile:182)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.u.b(SourceFile:215)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.q.a(SourceFile:273)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.adshield.a.a.c(SourceFile:78)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.adshield.a.c.onTransact(SourceFile:113)
I/AdvertisingIdClient( 5418): 	at android.os.Binder.transact(Binder.java:361)
I/AdvertisingIdClient( 5418): 	at eqi.c(Unknown Source)
I/AdvertisingIdClient( 5418): 	at fbj.a(SourceFile:5000)
I/AdvertisingIdClient( 5418): 	at fye.d(SourceFile:2062)
I/AdvertisingIdClient( 5418): 	at fye.c(SourceFile:1048)
I/AdvertisingIdClient( 5418): 	at fyf.c(SourceFile:115)
I/AdvertisingIdClient( 5418): 	at fyf.a(SourceFile:75)
I/AdvertisingIdClient( 5418): 	at fyb.run(SourceFile:254)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/AdvertisingIdClient( 5418): 	at goz.run(SourceFile:40)
I/AdvertisingIdClient( 5418): 	at java.lang.Thread.run(Thread.java:841)
I/AdvertisingIdClient( 5418): GMS remote exception 
I/AdvertisingIdClient( 5418): android.os.DeadObjectException
I/AdvertisingIdClient( 5418): 	at android.os.BinderProxy.transact(Native Method)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.identifier.a.f.a(SourceFile:114)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.identifier.a.a(SourceFile:266)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.u.f(SourceFile:182)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.u.b(SourceFile:215)
I/AdvertisingIdClient( 5418): 	at com.google.android.a.q.a(SourceFile:273)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.adshield.a.a.c(SourceFile:78)
I/AdvertisingIdClient( 5418): 	at com.google.android.gms.ads.adshield.a.c.onTransact(SourceFile:113)
I/AdvertisingIdClient( 5418): 	at android.os.Binder.transact(Binder.java:361)
I/AdvertisingIdClient( 5418): 	at eqi.c(Unknown Source)
I/AdvertisingIdClient( 5418): 	at fbj.a(SourceFile:5000)
I/AdvertisingIdClient( 5418): 	at fye.d(SourceFile:2062)
I/AdvertisingIdClient( 5418): 	at fye.c(SourceFile:1048)
I/AdvertisingIdClient( 5418): 	at fyf.c(SourceFile:115)
I/AdvertisingIdClient( 5418): 	at fyf.a(SourceFile:80)
I/AdvertisingIdClient( 5418): 	at fyb.run(SourceFile:254)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
I/AdvertisingIdClient( 5418): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
I/AdvertisingIdClient( 5418): 	at goz.run(SourceFile:40)
I/AdvertisingIdClient( 5418): 	at java.lang.Thread.run(Thread.java:841)
D/dalvikvm( 5475): GC_CONCURRENT freed 2941K, 31% free 9627K/13768K, paused 3ms+2ms, total 23ms
D/dalvikvm( 5475): WAIT_FOR_CONCURRENT_GC blocked 18ms
W/dalvikvm( 5475): VFY: unable to resolve static field 529 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/dalvikvm( 5475): VFY: replacing opcode 0x60 at 0x000b
I/dalvikvm( 5475): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 5475): VFY: unable to resolve virtual method 10979: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x00ca
I/MultiDex( 5475): VM with version 1.6.0 does not have multidex support
I/MultiDex( 5475): install
I/MultiDex( 5475): MultiDexExtractor.load(/data/app/com.google.android.gms-4.apk, false)
E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.google.android.youtube/databases/youtube_upload_service'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5418): 	at lax.a(SourceFile:1057)
E/SQLiteDatabase( 5418): 	at lax.call(SourceFile:41)
E/SQLiteDatabase( 5418): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5418): 	at lay.run(SourceFile:336)
E/SQLiteDatabase( 5418): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 5418): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 5475): loading existing secondary dex files
I/MultiDex( 5475): load found 3 secondary dex files
I/MultiDex( 5475): install done
E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.google.android.youtube/databases/preload_videos_tasks.db'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5418): 	at jqg.a(SourceFile:65)
E/SQLiteDatabase( 5418): 	at jqj.handleMessage(SourceFile:1309)
E/SQLiteDatabase( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5418): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5418): threadid=60: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 5418): FATAL EXCEPTION: jqi
E/AndroidRuntime( 5418): Process: com.google.android.youtube, PID: 5418
E/AndroidRuntime( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5418): 	at jqg.a(SourceFile:65)
E/AndroidRuntime( 5418): 	at jqj.handleMessage(SourceFile:1309)
E/AndroidRuntime( 5418): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5418): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5418): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop210.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, zoutube
D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5475): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5475): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 5475): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 5475): VFY: unable to resolve instance field 46
D/dalvikvm( 5475): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5475): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5475): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 5475): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 5475): DexOpt: unable to optimize instance field ref 0x002e at 0x63 in Lcom/google/android/gms/common/util/bc;.b
D/dalvikvm( 5475): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42271bf0
D/dalvikvm( 5475): Added shared lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42271bf0
D/dalvikvm( 5475): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42271bf0, skipping init
D/dalvikvm( 5475): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42271bf0
D/dalvikvm( 5475): Added shared lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42271bf0
V/JNIHelp ( 5475): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
D/dalvikvm( 5475): Trying to load lib /data/app-lib/com.google.android.gms-4/libgmscore.so 0x42271bf0
D/dalvikvm( 5475): Shared lib '/data/app-lib/com.google.android.gms-4/libgmscore.so' already loaded in same CL 0x42271bf0
D/dalvikvm( 5475): Trying to load lib /data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so 0x42271bf0
D/dalvikvm( 5475): Shared lib '/data/app-lib/com.google.android.gms-4/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42271bf0
I/DBG_DM  ( 4631): [3.19.140541][Line:441][xdmInitAdpWaitSystemRootingCheck] waits 14 sec
W/System.err( 4631): java.io.IOException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:455)
W/System.err( 4631): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
W/System.err( 4631): 	at java.io.OutputStream.write(OutputStream.java:82)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.xdmSaveLog(XDMDebug.java:322)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMDebug.XDM_DEBUG(XDMDebug.java:72)
W/System.err( 4631): 	at com.wssyncmldm.adapter.XDMInitAdapter.xdmInitAdpWaitSystemRootingCheck(XDMInitAdapter.java:441)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.xdmAgentTaskHandler(XDMTask.java:220)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask$1.handleMessage(XDMTask.java:88)
W/System.err( 4631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4631): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 4631): 	at com.wssyncmldm.agent.XDMTask.run(XDMTask.java:98)
W/System.err( 4631): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 4631): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
W/System.err( 4631): 	at libcore.io.Posix.writeBytes(Native Method)
W/System.err( 4631): 	at libcore.io.Posix.write(Posix.java:202)
W/System.err( 4631): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
W/System.err( 4631): 	at libcore.io.IoBridge.write(IoBridge.java:450)
W/System.err( 4631): 	... 11 more
I/ProviderInstaller( 5475): Installed default security provider GmsCore_OpenSSL
W/NativeLibraryUtils( 5475): Failed to open lock file
W/NativeLibraryUtils( 5475): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5475): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 5475): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 5475): 	at com.google.android.gms.common.util.bc.b(SourceFile:325)
W/NativeLibraryUtils( 5475): 	at com.google.android.gms.common.app.a.run(SourceFile:205)
W/NativeLibraryUtils( 5475): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 5475): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 5475): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 5475): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 5475): 	... 3 more
E/SQLiteDatabase( 5418): Failed to open database '/data/data/com.google.android.youtube/databases/google_conversion_tracking.db'.
E/SQLiteDatabase( 5418): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5418): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5418): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5418): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5418): 	at ahe.a(SourceFile:102)
E/SQLiteDatabase( 5418): 	at aha.a(SourceFile:2161)
E/SQLiteDatabase( 5418): 	at ags.run(SourceFile:34)
E/SQLiteDatabase( 5418): 	at java.lang.Thread.run(Thread.java:841)
W/GoogleConversionReporter( 5418): Error opening writable conversion tracking database
I/GAv4-SVC( 5475): Google Analytics 8.3.01 is starting up.
E/SQLiteDatabase( 5475): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.v.getWritableDatabase(SourceFile:884)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.l(SourceFile:812)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.a(SourceFile:630)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.e(SourceFile:264)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.x.d(SourceFile:885)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.x.b(SourceFile:242)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.aa.run(SourceFile:152)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5475): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.measurement.n.run(SourceFile:388)
E/GAv4-SVC( 5475): Opening the database failed, dropping the table and recreating it
E/SharedPreferencesImpl( 5475): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
E/SQLiteDatabase( 5475): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 5475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/SQLiteDatabase( 5475): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5475): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5475): 	at java.lang.Thread.run(Thread.java:841)
E/SharedPreferencesImpl( 5475): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5475): Failed to open database '/data/data/com.google.android.gms/databases/google_analytics_v4.db'.
E/SQLiteDatabase( 5475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.v.getWritableDatabase(SourceFile:897)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.l(SourceFile:812)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.a(SourceFile:630)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.u.e(SourceFile:264)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.x.d(SourceFile:885)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.x.b(SourceFile:242)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.analytics.internal.aa.run(SourceFile:152)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5475): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.measurement.n.run(SourceFile:388)
W/dalvikvm( 5475): threadid=14: thread exiting with uncaught exception (group=0x4180ac08)
E/GAv4-SVC( 5475): Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml to backup file /data/data/com.google.android.gms/shared_prefs/LocalSensorState.xml.bak
W/GAv4-SVC( 5475): Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SharedPreferencesImpl( 5475): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SharedPreferencesImpl( 5475): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/GAv4-SVC( 5475): Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5475): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 5475): Process: com.google.android.gms, PID: 5475
E/AndroidRuntime( 5475): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 5475): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 5475): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 5475): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 5475): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5475): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 5475): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5475): 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
E/AndroidRuntime( 5475): 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
E/AndroidRuntime( 5475): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5475): 	... 4 more
E/SharedPreferencesImpl( 5475): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
E/SQLiteDatabase( 5475): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 5475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteDatabase( 5475): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase( 5475): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase( 5475): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase( 5475): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteDatabase( 5475): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 5475): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 5475): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 5475): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteOpenHelper( 5475): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 5475): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 5475): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 5475): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 5475): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 5475): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:421)
E/SQLiteOpenHelper( 5475): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteOpenHelper( 5475): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteOpenHelper( 5475): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteOpenHelper( 5475): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteOpenHelper( 5475): 	at com.google.android.gms.reminders.a.a.a(SourceFile:64)
E/SQLiteOpenHelper( 5475): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 5475): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 5475): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 5475): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 5475): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 5475): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 5475): 	at java.lang.Thread.run(Thread.java:841)
W/SQLiteOpenHelper( 5475): Opened reminders.db in read-only mode
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop212.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, hms
D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5475): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 5475): VFY: replacing opcode 0x62 at 0x0008
W/InstanceID/Rpc( 5475): Found 10012
D/FileApkUtils( 5475): Spent 54ms computing apk sha1.
D/FileApkUtils( 5475): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 5475): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 5475): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,D/GmsModuleFndr( 5475): Beginning GMS chimera module scan
,I/dalvikvm( 5475): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.ma.a
W/dalvikvm( 5475): VFY: unable to resolve virtual method 484: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 5475): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.ma.b
W/dalvikvm( 5475): VFY: unable to resolve virtual method 148: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x0220
,E/dalvikvm( 5475): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 5475): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
,D/dalvikvm( 5475): VFY: replacing opcode 0x1f at 0x000e
,E/android.os.Debug( 2419): !@Dumpstate > dumpstate -k -t -z -d -o /data/log/dumpstate_app_error
,I/dumpstate( 5540): begin
,W/Auth    ( 2845): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtils( 2578): isPcwEnable = 10
,D/dalvikvm( 5475): GC_CONCURRENT freed 2222K, 25% free 10518K/13876K, paused 5ms+8ms, total 65ms
E/dalvikvm( 5475): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 5475): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,D/dalvikvm( 5475): VFY: replacing opcode 0x1f at 0x00ef
,W/dalvikvm( 5475): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,I/dalvikvm( 5475): Could not find method android.telephony.SubscriptionManager.getActiveSubscriptionInfoList, referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 5475): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x0004
D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5475): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5475): VFY: replacing opcode 0x62 at 0x0008
,D/GCM     ( 5475): COMPAT: Multi user not supported
,D/GCM     ( 2845): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/dalvikvm( 5475): DexOpt: unable to optimize static field ref 0x00a2 at 0x0c in Lcom/google/android/gms/checkin/d;.a
,D/dalvikvm( 5475): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 5475): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 5475): VFY: replacing opcode 0x62 at 0x0022
,I/CheckinService( 5475): Checkin interval check for package: unspecified last checkin: 1449001650308 min interval config: 0 actual interval: 495673350
,D/ChimeraCfgMgr( 5475): Beginning module configuration check
,D/ChimeraCfgMgr( 5475): Module APKs unchanged, check complete
,I/CheckinService( 5475): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 5475): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 2733): DispatchingService.onCreate()
,W/dalvikvm( 5475): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 5475): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/SharedPreferencesImpl( 2733): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml to backup file /data/data/com.google.android.gms/shared_prefs/LOCATION_REPORTING.xml.bak
,E/GCoreUlr( 2733): Error opening datastore
E/GCoreUlr( 2733): com.google.android.gms.leveldb.LevelDbIoErrorException: IO error: /data/data/com.google.android.gms/app_ulr_db/LOCK: Read-only file system
E/GCoreUlr( 2733): 	at com.google.android.gms.leveldb.LevelDb.nativeOpen(Native Method)
E/GCoreUlr( 2733): 	at com.google.android.gms.leveldb.LevelDb.a(SourceFile:137)
E/GCoreUlr( 2733): 	at com.google.android.location.reporting.b.a.a(SourceFile:82)
E/GCoreUlr( 2733): 	at com.google.android.location.reporting.service.DispatchingService.onCreate(SourceFile:379)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2859)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/GCoreUlr( 2733): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1390)
E/GCoreUlr( 2733): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/GCoreUlr( 2733): 	at android.os.Looper.loop(Looper.java:146)
E/GCoreUlr( 2733): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/GCoreUlr( 2733): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/GCoreUlr( 2733): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/GCoreUlr( 2733): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/GCoreUlr( 2733): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/GCoreUlr( 2733): 	at dalvik.system.NativeStart.main(Native Method)
,V/GmsCoreStatsServiceLauncher( 5475): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,I/GCoreUlr( 2733): DispatchingService.onDestroy()
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/SystemUpdateService( 5475): onCreate
,F/PackageManager( 2419): Unable to backup user packages state file, current changes will be lost at reboot
,D/EnterpriseDeviceManagerService( 2419): Creating context as user 0
E/DropBoxManagerService( 2419): Can't write: system_server_wtf
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop169.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2419): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2419): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2419): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2419): 	at android.util.Log.wtf(Log.java:381)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1509)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.PackageManagerService.setEnabledSetting(PackageManagerService.java:14463)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.PackageManagerService.setComponentEnabledSetting(PackageManagerService.java:14321)
E/DropBoxManagerService( 2419): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1138)
E/DropBoxManagerService( 2419): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
E/DropBoxManagerService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
E/DropBoxManagerService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 18 more
,I/CheckinService( 5475): Checking schedule, now: 1449497323747 next: 1449559993214
,I/CheckinService( 5475): active receiver: disabled
,D/SystemUpdateService( 5475): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/BroadcastQueue( 2419): Skipping deliver [background] BroadcastRecord{4345f3e0 u-1 android.intent.action.BATTERY_CHANGED} to ReceiverList{4345f1d0 5475 com.google.android.gms/10012/u0 remote:4345eae0}: process crashing
,I/dalvikvm( 5475): Could not find method android.app.Notification$Builder.setCategory, referenced from method com.google.android.gms.update.t.a
W/dalvikvm( 5475): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
,D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x040d
V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AuthZen ( 5475): Handling intent: android.intent.action.BOOT_COMPLETED
,I/dalvikvm( 5475): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
,W/dalvikvm( 5475): VFY: unable to resolve virtual method 1305: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 5475): VFY: replacing opcode 0x6e at 0x002b
I/SystemUpdateService( 5475): cancelUpdate (empty URL)
,I/SystemUpdateService( 5475): active receiver: disabled
,W/dalvikvm( 5475): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,D/AuthZenEventHandler( 5475): Handling event: android.intent.action.BOOT_COMPLETED
,D/dalvikvm( 5475): Trying to load lib /data/app-lib/com.google.android.gms-4/libAppDataSearch.so 0x42271bf0
,D/dalvikvm( 5475): Added shared lib /data/app-lib/com.google.android.gms-4/libAppDataSearch.so 0x42271bf0

```
