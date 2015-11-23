#### Test 503880196b4ec73_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/SSRM:n  ( 3517): SIOP:: AP = 260, PST = 299, CUR = 53
,--------- beginning of main
D/AndroidRuntime(10579): 
D/AndroidRuntime(10579): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10579): CheckJNI is OFF
D/AndroidRuntime(10579): readGMSProperty: start
D/AndroidRuntime(10579): readGMSProperty: already setted!!
D/AndroidRuntime(10579): readGMSProperty: end
D/AndroidRuntime(10579): addProductProperty: start
E/AffinityControl(10579): AffinityControl: registerfunction enter
D/AndroidRuntime(10579): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3517): inState():  stateMachine is null !!
I/PersonaManagerService( 3517): PersonaId don't exist
I/ActivityManager( 3517): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3517): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3517): mDVFSHelper.acquire()
D/FocusedStackFrame( 3517): Set to : 0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/Zygote  (10597): MountEmulatedStorage()
I/libpersona(10597): KNOX_SDCARD checking this for 10420
E/Zygote  (10597): v2
I/libpersona(10597): KNOX_SDCARD not a persona
I/SELinux (10597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3517): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10597 uid=10420 gids={50420, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (10597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10597): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10579): Shutting down VM
D/PointerIcon( 3517): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3517): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3517): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3517): setHoveringSpenCustomIcon IconType is same.1
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8711(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 976us total 28.546ms
D/TimaKeyStoreProvider(10597): TimaSignature is unavailable
D/ActivityThread(10597): Added TimaKeyStore provider
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3517): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3517): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 842us total 19.055ms
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.309ms total 19.318ms
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
D/ResourcesManager(10597): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/ActivityThread( 4001): updateVisibility : ActivityRecord{39a61351 token=android.os.BinderProxy@3ed174a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4001): onTrimMemory. Level: 20
I/WebViewFactory(10597): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10597): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10597): Loading: webviewchromium
I/LibraryLoader(10597): Time to load native libraries: 4 ms (timestamps 5217-5221)
I/LibraryLoader(10597): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10597): Binding Chromium to main looper Looper (main, tid 1) {39e3a70e}
I/LibraryLoader(10597): Expected native library version number "",actual native library version number ""
I/chromium(10597): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10597): Initializing chromium process, renderers=0
W/art     (10597): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10597): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(10597): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10597): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10597): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10597): 94934319: getState() :  mService = null. Returning STATE_OFF
W/chromium(10597): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10597): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (10597): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(10597): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(10597): CordovaWebView is running on device made by: samsung
W/art     (10597): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10597): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(10597): performCreate Call secproduct feature valuefalse
D/Activity(10597): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(10597): Render dirty regions requested: true
D/ActivityManager( 3517): post active user change for 0
D/KnoxTimeoutHandler( 3517): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3517): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3517): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3517): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3517): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3517): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3517): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3517): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10597): Initialized EGL, version 1.4
I/OpenGLRenderer(10597): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1278897904 
D/OpenGLRenderer(10597): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10597): Enabling debug mode 0
D/mali_winsys(10597): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10597): updateVisibility : ActivityRecord{3aef281f token=android.os.BinderProxy@d1b490d {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 3517): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3517): mDVFSHelper.release()
I/Timeline( 3517): Timeline: Activity_windows_visible id: ActivityRecord{1d6facb8 u0 com.example.hello/.MainActivity t28} time:105669
W/IInputConnectionWrapper(10597): showStatusIcon on inactive InputConnection
I/Timeline(10597): Timeline: Activity_idle id: android.os.BinderProxy@d1b490d time:105675
I/chromium(10597): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler(10597): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue(10597): Set native->JS mode to OnlineEventsBridgeMode
I/chromium(10597): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10597): 
D/jxcore_app_log(10597): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1356870400
D/JX-Cordova(10597): jxcore cordova android initializing
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/jxcore-log(10597): Initializing JXcore engine
W/jxcore-log(10597): JXcore engine is ready
W/jxcore-log(10597): Starting JXcore engine
E/auditd  ( 4538): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService( 3517): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3517): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
D/SecurityLogAgent:SEDenialService( 3517): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
W/jxcore-log(10597): Platform android
W/jxcore-log(10597): 
W/jxcore-log(10597): Process ARCH arm
W/jxcore-log(10597): 
,I/jxcore-log(10597): JXcore Cordova bridge is ready!
I/jxcore-log(10597): 
W/jxcore-log(10597): JXcore engine is started
,E/jxcore-log(10597): >> samsung-SM-N910C
E/jxcore-log(10597): 
,I/jxcore-log(10597): Total memory 2970812416
I/jxcore-log(10597): 
I/jxcore-log(10597): Free memory 119029760
I/jxcore-log(10597): 
I/jxcore-log(10597): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10597): 
I/jxcore-log(10597): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10597): 
,I/jxcore-log(10597): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10597): 
,I/jxcore-log(10597): Size 1440 2560
I/jxcore-log(10597): 
,I/jxcore-log(10597): Screen Brightness 134
I/jxcore-log(10597): 
,E/jxcore-log(10597): Dummy Error Log.
E/jxcore-log(10597): 
,I/jxcore-log(10597): getBuffer is called!!!!
I/jxcore-log(10597): 
,I/PowerManagerService( 3517): [PWL] Off : 15s ago
,D/BluetoothAdapter(10597): disable()
,E/BluetoothManagerService( 3517): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3517): New client listening to asynchronous messages
,I/WifiManager(10597): packageName : com.example.hello
,D/SecContentProvider( 3517): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3517): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3517): mCursor = null
,D/WifiService( 3517): setWifiEnabled: false pid=10597, uid=10420
,E/WifiService( 3517): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider( 3517): name = wifi_on
,I/jxcore-log(10597): ****TEST TOOK:  5078  ms ****
I/jxcore-log(10597): 
,I/jxcore-log(10597): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10597): 
,D/AndroidRuntime(10692): 
D/AndroidRuntime(10692): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10692): CheckJNI is OFF
,D/AndroidRuntime(10692): readGMSProperty: start
D/AndroidRuntime(10692): readGMSProperty: already setted!!
,D/AndroidRuntime(10692): readGMSProperty: end
D/AndroidRuntime(10692): addProductProperty: start
,E/AffinityControl(10692): AffinityControl: registerfunction enter
,D/AndroidRuntime(10692): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3517): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3517): START PACKAGE DELETE: observer{703126267}
D/PackageManager( 3517): pkg{<packageName>}
D/PackageManager( 3517): user{0}
D/PackageManager( 3517): caller{2000}
D/PackageManager( 3517): flags{3}
D/PersonaManagerService( 3517): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3517): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3517): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3517): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3517): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3517): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3517): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3517): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3517): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3517): !@killApplicatoin: 10420, uninstall pkg
,I/ActivityManager( 3517): Force stopping com.example.hello appid=10420 user=-1: uninstall pkg
I/ActivityManager( 3517): Killing 10597:com.example.hello/u0a420 (adj 0): stop com.example.hello
,I/ActivityManager( 3517):   Force finishing activity ActivityRecord{1d6facb8 u0 com.example.hello/.MainActivity t28}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3517): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3517): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3517): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3517): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3517): Skipping PackageSetting{25c21e com.test.thalitest/10418} due to missing metadata
D/WifiService( 3517): Client connection lost with reason: 4
,I/ActivityManager( 3517): Force stopping com.example.hello appid=10420 user=0: pkg removed
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     ( 7960): Explicit concurrent mark sweep GC freed 26378(1511KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.090ms total 32.309ms
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,W/GeofencerStateMachine( 4231): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4447): mOCRHelper is null
,I/InputReader( 3517): Reconfiguring input devices.  changes=0x00000010
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/LWLocationManager(10184): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10184): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (10710): MountEmulatedStorage()
,E/Zygote  (10710): v2
I/libpersona(10710): KNOX_SDCARD checking this for 10063
I/libpersona(10710): KNOX_SDCARD not a persona
,I/SELinux (10710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10710 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3517): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3517): Admin package name: com.google.android.gms
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TimaKeyStoreProvider(10710): TimaSignature is unavailable
,D/ActivityThread(10710): Added TimaKeyStore provider
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(10710): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 3517): Explicit concurrent mark sweep GC freed 38072(2MB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 48MB/64MB, paused 1.916ms total 175.077ms
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/art     ( 3517): WaitForGcToComplete blocked for 173.778ms for cause Explicit
,W/ResourceType( 4945): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 4945): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10710): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10710): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10710): packagename:com.example.hello
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourceType( 4945): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4945): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/Zygote  (10727): MountEmulatedStorage()
I/libpersona(10727): KNOX_SDCARD checking this for 10021
E/Zygote  (10727): v2
I/libpersona(10727): KNOX_SDCARD not a persona
,I/SELinux (10727): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10727): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10727): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10727 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 9852:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider(10727): TimaSignature is unavailable
,D/SecContentProvider2( 3517): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3517): mCursor = null
,D/ActivityThread(10727): Added TimaKeyStore provider
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10727): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourceType( 3517): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
I/KLMS-2.4.521: (10727): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 20:22:37 GMT+01:00 2015
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/KLMS-2.4.521: (10727): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3517): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
,I/splitIntent( 3517): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/KLMS-2.4.521: (10727): KLMSIntentService(): onCreate()
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,I/KLMS-2.4.521: (10727): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ResourcesManager(10184): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/KLMS-2.4.521: (10727): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/KLMS-2.4.521: (10727): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
I/art     ( 3517): Explicit concurrent mark sweep GC freed 9224(546KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 3.976ms total 154.761ms
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10727): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (10727): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10727): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 3517): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3517): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3517): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3517): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/Zygote  (10744): MountEmulatedStorage()
E/Zygote  (10744): v2
I/libpersona(10744): KNOX_SDCARD checking this for 10106
I/libpersona(10744): KNOX_SDCARD not a persona
,I/SELinux (10744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/SELinux (10744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3517): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10744 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (10744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/PackageManager( 3517): delete codoeFile: 
,I/AASAUninstall( 3517):  com.example.hello not target!
,D/PackageManager( 3517): result of delete: 1{703126267}
,D/AndroidRuntime(10692): Shutting down VM
D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10184): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10184): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10184): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/TimaKeyStoreProvider(10744): TimaSignature is unavailable
,D/ActivityThread(10744): Added TimaKeyStore provider
,W/ContextImpl(10009): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  (10761): MountEmulatedStorage()
,E/Zygote  (10761): v2
I/libpersona(10761): KNOX_SDCARD checking this for 10190
I/libpersona(10761): KNOX_SDCARD not a persona
,I/SELinux (10761): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10761): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10761): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10761 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/KLMS-2.4.521: (10727): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.4.521: (10727): KLMSIntentService(): onDestroy()
,D/ResourcesManager(10744): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/Mms/FreeMessageStatusReceiver(10461): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/TimaKeyStoreProvider(10761): TimaSignature is unavailable
,D/ActivityThread(10761): Added TimaKeyStore provider
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/Mms/FreeMessageReceiverService(10461): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(10461): onHandleIntent: ACTION_PACKAGE_REMOVED
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/elm:14491(10744): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/elm:14491(10744): ELMEngine.ELMEngine( context ).
D/elm:14491(10744): MDMBridge.setEnterpriseBridge()
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(10761): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  (10778): MountEmulatedStorage()
E/Zygote  (10778): v2
I/libpersona(10778): KNOX_SDCARD checking this for 10116
I/libpersona(10778): KNOX_SDCARD not a persona
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux (10778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux (10778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10778 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/SELinux (10778): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10761): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10761): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/TapandpayWidget:Utils(10761): Clear T&P info.
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/TapandpayWidget:TanpandpayAppWidgetProvider(10761): Widget is not attached.
D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14491(10744): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/elm:14491(10744): ElmAgentService : onCreate()
,D/elm:14491(10744): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14491(10744): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10744): MDMBridge.getInstance()
D/elm:14491(10744): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14491(10744): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider(10778): TimaSignature is unavailable
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
D/ActivityThread(10778): Added TimaKeyStore provider
,D/ResourcesManager( 3517): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3517): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/elm:14491(10744): ElmAgentService : onDestroy().
D/RCPManagerService( 3517): PackageReceiver onReceive()
I/HarmonyEASService( 3517): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3517): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/BackupManagerService( 3517): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3517): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3517): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3517): uID is 10420
V/EnterpriseBillingPolicy( 3517): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3517): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3517): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3517): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3517): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3517): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 3517): getBillingProfileForVpnEngine - end - null
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3517): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3517): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/TactileAssist( 3517): enable value -1
I/TactileAssist( 3517): internal enable value -1
I/TactileAssist( 3517): intensity value -1
I/TactileAssist( 3517): saveAppList value true
,D/ResourcesManager(10778): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,I/TactileAssist( 3517): List of disabled apps :
,D/UsbSettingsManager( 3517): clearDefaults: com.example.hello
I/CrashAnrDetector( 3517): onPackageRemoved : com.example.hello
,D/TaskPersister( 3517): removeObsoleteFile: deleting file=28_task.xml
,D/ResourcesManager(10184): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Books/Books.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,E/SQLiteLog(10778): (284) automatic index on titles(filter_id)
,E/Zygote  (10796): MountEmulatedStorage()
E/Zygote  (10796): v2
I/libpersona(10796): KNOX_SDCARD checking this for 10019
I/libpersona(10796): KNOX_SDCARD not a persona
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/SELinux (10796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10796 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,I/SELinux (10796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10796): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (10809): MountEmulatedStorage()
E/Zygote  (10809): v2
I/libpersona(10809): KNOX_SDCARD checking this for 1000
I/libpersona(10809): KNOX_SDCARD not a persona
,I/SELinux (10809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10184): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/SELinux (10809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10809): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3517): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/TimaKeyStoreProvider(10796): TimaSignature is unavailable
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ActivityThread(10796): Added TimaKeyStore provider
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/TimaKeyStoreProvider(10809): TimaSignature is unavailable
D/ResourcesManager(10184): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ActivityThread(10809): Added TimaKeyStore provider
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/Zygote  (10828): MountEmulatedStorage()
I/libpersona(10828): KNOX_SDCARD checking this for 10110
E/Zygote  (10828): v2
I/libpersona(10828): KNOX_SDCARD not a persona
,I/SELinux (10828): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10828): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10828): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=10828 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3517): Killing 9874:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/TimaKeyStoreProvider(10828): TimaSignature is unavailable
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ActivityThread(10828): Added TimaKeyStore provider
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10809): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/ResourcesManager(10184): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(10796): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  (10843): MountEmulatedStorage()
E/Zygote  (10843): v2
I/libpersona(10843): KNOX_SDCARD checking this for 10059
I/libpersona(10843): KNOX_SDCARD not a persona
,I/SELinux (10843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3517): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10843 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3517): Killing 9922:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/UsbHostManager( 3517): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3517): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3517): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3517): displayNotification : [0ah,00h,00h]
I/SELinux (10843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/UsbHostManager( 3517): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,D/UsbHostManager( 3517): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3517): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3517): displayNotification : [0ah,00h,01h]
D/ResourcesManager(10184): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/UsbHostManager( 3517): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3517): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3517): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/SELinux (10843): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3517): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3517): displayNotification : [09h,00h,00h]
,D/ResourcesManager(10184): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/MtpClient(10373): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(10373): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,W/ContextImpl(10809): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,I/ActivityManager( 3517): Killing 9943:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,E/lowmemorykiller( 2826): Error writing /proc/9943/oom_score_adj; errno=22
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10796): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10796): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10796): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(10184): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10828): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/UsbHostManager( 3517): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3517): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,E/SQLiteLog(10809): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10809): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10809): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10809): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10809): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10809): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10809): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime(10809): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10809): Process: com.android.keychain, PID: 10809
E/AndroidRuntime(10809): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10809): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10809): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10809): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10809): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10809): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:55,4)
E/AndroidRuntime(10809): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10809): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10809): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider(10843): TimaSignature is unavailable
,I/EventHub( 3517): Removing device '/dev/input/event10' due to inotify event
,D/ActivityThread(10843): Added TimaKeyStore provider
,E/Zygote  (10867): MountEmulatedStorage()
E/Zygote  (10867): v2
I/libpersona(10867): KNOX_SDCARD checking this for 1000
I/libpersona(10867): KNOX_SDCARD not a persona
,I/SELinux (10867): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10867): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3517): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10867 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10867): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3517): Removing device '/dev/input/event7' due to inotify event
,V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,D/TimaKeyStoreProvider(10867): TimaSignature is unavailable
,D/ActivityThread(10867): Added TimaKeyStore provider
,D/LocationWidgetApplication(10184): getLastUiLocationId() : mLastUiLocationId = -100
I/EventHub( 3517): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(10843): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(10843): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility(10843): onReceive() it will make start service
,D/ResourcesManager(10867): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
I/EventHub( 3517): Removing device '/dev/input/event9' due to inotify event
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3517): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService( 3517): Can't write: system_app_crash
E/DropBoxManagerService( 3517): java.io.FileNotFoundException: /data/system/dropbox/drop180.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3517): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3517): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3517): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3517): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3517): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3517): 	... 5 more
,I/EventHub( 3517): Removing device '/dev/input/event11' due to inotify event
,E/Zygote  (10883): MountEmulatedStorage()
E/Zygote  (10883): v2
I/libpersona(10883): KNOX_SDCARD checking this for 1000
I/libpersona(10883): KNOX_SDCARD not a persona
,I/SELinux (10883): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10883): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10883): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3517): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10883 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/AcmsPackageEventListener(10867): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl(10867): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/EventHub( 3517): Removing device '/dev/input/event12' due to inotify event
,D/AndroidRuntime(10828): Shutting down VM
,E/AndroidRuntime(10828): FATAL EXCEPTION: main
E/AndroidRuntime(10828): Process: com.facebook.appmanager, PID: 10828
E/AndroidRuntime(10828): java.lang.RuntimeException: Unable to instantiate application com.facebook.oxygen.appmanager.app.AppManagerApplication: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10828): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime(10828): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5088)
E/AndroidRuntime(10828): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10828): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10828): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10828): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10828): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10828): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10828): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10828): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10828): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10828): Caused by: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10828): 	at com.facebook.ad.e.a(FBSoLoader.java:66)
E/AndroidRuntime(10828): 	at com.facebook.base.a.f.attachBaseContext(DelegatingApplication.java:81)
E/AndroidRuntime(10828): 	at android.app.Application.attach(Application.java:205)
E/AndroidRuntime(10828): 	at android.app.Instrumentation.newApplication(Instrumentation.java:1004)
E/AndroidRuntime(10828): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime(10828): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime(10828): 	... 10 more
E/AndroidRuntime(10828): Caused by: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10828): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/AndroidRuntime(10828): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/AndroidRuntime(10828): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/AndroidRuntime(10828): 	at com.facebook.soloader.e.<init>(FileLocker.java:20)
E/AndroidRuntime(10828): 	at com.facebook.soloader.e.a(FileLocker.java:16)
E/AndroidRuntime(10828): 	at com.facebook.soloader.SysUtil.a(SysUtil.java:215)
E/AndroidRuntime(10828): 	at com.facebook.ad.d.a(DirectorySoSourceWithAssets.java:69)
E/AndroidRuntime(10828): 	at com.facebook.ad.e.a(FBSoLoader.java:63)
E/AndroidRuntime(10828): 	... 15 more
E/AndroidRuntime(10828): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10828): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime(10828): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime(10828): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/AndroidRuntime(10828): 	... 22 more
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 675us total 41.662ms
,V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.facebook.appmanager
,I/EventHub( 3517): Removing device '/dev/input/event13' due to inotify event
,D/Compatibility(10843): onHandleIntent()
,D/Compatibility(10843): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10420, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/AcmsService(10867): Enter Oncreate
D/AcmsServiceMonitor(10867): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10867): creating AcmsCore
D/AcmsCore(10867): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10867): AcmsCore
,D/AcmsCore(10867): init
D/AcmsCore(10867): Looper handler is not null
D/AcmsCore(10867): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10867): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10867): Incrementing - Counter value: 1
D/AcmsCore(10867): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10867): onStartCommand
D/AcmsService(10867): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor(10867): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10867): Incrementing - Counter value: 2
D/Compatibility(10843): found: 2
D/AcmsService(10867): Incremented Counter Value : onStartCommand
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 615us total 27.695ms
,D/AcmsCertificateMngr(10867): AcmsCertificateMngr
D/AcmsRevocationMngr(10867): AcmsRevocationMngr
,E/DropBoxManagerService( 3517): Can't write: system_app_crash
E/DropBoxManagerService( 3517): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3517): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3517): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3517): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3517): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3517): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3517): 	... 5 more
,D/TimaKeyStoreProvider(10883): TimaSignature is unavailable
D/ActivityThread(10883): Added TimaKeyStore provider
D/Compatibility(10843): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10843): skipping ResolveInfo{14af67a4 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10843): considering ResolveInfo{d1b490d com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 581us total 24.594ms
D/Compatibility(10843): default: com.sec.android.app.soundalive.SAControlPanelActivity
I/EventHub( 3517): Removing device '/dev/input/event14' due to inotify event
,I/Process (10809): Sending signal. PID: 10809 SIG: 9
,D/Compatibility(10843): enabling receiver ResolveInfo{31ee40c2 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityThread(10867): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/SQLiteLog(10867): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10867): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10867): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/SQLiteDatabase(10867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10867): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10867): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10867): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10867): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10867): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(10867): Shutting down VM
,E/AndroidRuntime(10867): FATAL EXCEPTION: main
E/AndroidRuntime(10867): Process: ACMS.Process, PID: 10867
E/AndroidRuntime(10867): java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@31ee40c2 with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10867): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3326)
E/AndroidRuntime(10867): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/AndroidRuntime(10867): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/AndroidRuntime(10867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10867): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10867): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10867): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10867): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10867): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10867): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10867): Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10867): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10867): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/AndroidRuntime(10867): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/AndroidRuntime(10867): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/AndroidRuntime(10867): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/AndroidRuntime(10867): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/AndroidRuntime(10867): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/AndroidRuntime(10867): 	... 9 more
E/AndroidRuntime(10867): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10867): 	at android.dat,abase.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10867): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10867): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/AndroidRuntime(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10867): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10867): 	... 20 more
D/Compatibility(10843): enabling receiver ResolveInfo{3238ded3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
W/ContextImpl(10009): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:44 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:149 android.os.Handler.dispatchMessage:102 
D/ResourcesManager(10883): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/Compatibility(10843): enabling receiver ResolveInfo{204d5a10 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/ActivityManager( 3517): Killing 9901:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/PCWCLIENTTRACE_LOG(10883): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10883): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10883): new DMDBOpenHelper instance
,E/SQLiteLog(10883): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,D/Compatibility(10843): enabling receiver ResolveInfo{ac06909 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/SQLiteDatabase(10883): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10883): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10883): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10883): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10883): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10883): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10883): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10883): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10883): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10883): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10883): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10883): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10883): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10883): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10883): Shutting down VM
E/AndroidRuntime(10883): FATAL EXCEPTION: main
E/AndroidRuntime(10883): Process: com.sec.pcw.device, PID: 10883
E/AndroidRuntime(10883): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10883): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10883): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10883): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10883): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10883): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10883): 	at android.os.Looper.loop(Looper.java:14,5)
E/AndroidRuntime(10883): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10883): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10883): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10883): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10883): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10883): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10883): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10883): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10883): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10883): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10883): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10883): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10883): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10883): 	... 11 more
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname ACMS.Process
I/ActivityManager( 3517): Process com.android.keychain (pid 10809)(adj 5) has died(149,1306)
W/ActivityManager( 3517): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/ActivityThread(10867): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/Compatibility(10843): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/SQLiteLog(10867): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase(10867): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10867): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10867): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10867): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10867): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10867): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.<init>(AcmsRevocationMngr.java:118)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.manager.AcmsRevocationMngr.getAcmsRevocationMngr(AcmsRevocationMngr.java:128)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.<init>(AcmsCertificateMngr.java:94)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.manager.AcmsCertificateMngr.getAcmsCertificateMngr(AcmsCertificateMngr.java:286)
E/SQLiteDatabase(10867): 	at com.samsung.android.mirrorlink.acms.api.AcmsCore$AcmsHandler.handleMessage(AcmsCore.java:138)
E/SQLiteDatabase(10867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10867): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process (10867): Sending signal. PID: 10867 SIG: 9
V/ApplicationPolicy( 3517): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,E/DropBoxManagerService( 3517): Can't write: system_app_crash
E/DropBoxManagerService( 3517): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3517): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3517): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3517): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3517): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3517): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3517): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3517): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3517): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3517): 	... 5 more

```
