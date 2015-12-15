#### Test 50388019385b4d9_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
D/AndroidRuntime(10846): 
D/AndroidRuntime(10846): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10846): CheckJNI is OFF
D/AndroidRuntime(10846): readGMSProperty: start
D/AndroidRuntime(10846): readGMSProperty: already setted!!
D/AndroidRuntime(10846): readGMSProperty: end
D/AndroidRuntime(10846): addProductProperty: start
E/AffinityControl(10846): AffinityControl: registerfunction enter
D/AndroidRuntime(10846): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3525): inState():  stateMachine is null !!
I/PersonaManagerService( 3525): PersonaId don't exist
I/ActivityManager( 3525): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3525): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3525): mDVFSHelper.acquire()
D/FocusedStackFrame( 3525): Set to : 0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (10864): MountEmulatedStorage()
E/Zygote  (10864): v2
I/libpersona(10864): KNOX_SDCARD checking this for 10498
I/libpersona(10864): KNOX_SDCARD not a persona
I/SELinux (10864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10864 uid=10498 gids={50498, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (10864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10864): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10846): Shutting down VM
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10864): TimaSignature is unavailable
D/ActivityThread(10864): Added TimaKeyStore provider
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3525): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3525): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/SurfaceFlinger( 2852): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2852): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4001): updateVisibility : ActivityRecord{2b4209c9 token=android.os.BinderProxy@10a182e2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4001): onTrimMemory. Level: 20
D/ResourcesManager(10864): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/WebViewFactory(10864): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10864): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10864): Loading: webviewchromium
I/LibraryLoader(10864): Time to load native libraries: 4 ms (timestamps 7753-7757)
I/LibraryLoader(10864): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10864): Binding Chromium to main looper Looper (main, tid 1) {2db5918b}
I/LibraryLoader(10864): Expected native library version number "",actual native library version number ""
I/chromium(10864): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10864): Initializing chromium process, renderers=0
W/art     (10864): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10864): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(10864): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10864): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10864): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10864): 623477352: getState() :  mService = null. Returning STATE_OFF
W/chromium(10864): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10864): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (10864): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(10864): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(10864): CordovaWebView is running on device made by: samsung
W/art     (10864): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10864): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(10864): performCreate Call secproduct feature valuefalse
D/Activity(10864): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(10864): Render dirty regions requested: true
D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
I/SurfaceFlinger( 2852): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10864): Initialized EGL, version 1.4
I/OpenGLRenderer(10864): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278906096 
D/OpenGLRenderer(10864): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10864): Enabling debug mode 0
D/mali_winsys(10864): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10864): updateVisibility : ActivityRecord{17f65598 token=android.os.BinderProxy@37a584e {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{3973bdd2 u0 com.example.hello/.MainActivity t25} time:208217
W/ActivityManager( 3525): mDVFSHelper.release()
W/IInputConnectionWrapper(10864): showStatusIcon on inactive InputConnection
I/Timeline(10864): Timeline: Activity_idle id: android.os.BinderProxy@37a584e time:208224
I/chromium(10864): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler(10864): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium(10864): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10864): 
D/JsMessageQueue(10864): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(10864): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359522048
D/JX-Cordova(10864): jxcore cordova android initializing
,W/jxcore-log(10864): Initializing JXcore engine
W/jxcore-log(10864): JXcore engine is ready
,W/jxcore-log(10864): Starting JXcore engine
,E/auditd  ( 4545): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10864): Platform android
W/jxcore-log(10864): 
W/jxcore-log(10864): Process ARCH arm
W/jxcore-log(10864): 
,I/jxcore-log(10864): JXcore Cordova bridge is ready!
I/jxcore-log(10864): 
,W/jxcore-log(10864): JXcore engine is started
,E/jxcore-log(10864): >> samsung-SM-N910C
E/jxcore-log(10864): 
,I/jxcore-log(10864): Total memory 2970812416
I/jxcore-log(10864): 
,I/jxcore-log(10864): Free memory 123641856
I/jxcore-log(10864): 
I/jxcore-log(10864): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10864): 
I/jxcore-log(10864): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10864): 
,I/jxcore-log(10864): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10864): 
,I/jxcore-log(10864): Size 1440 2560
I/jxcore-log(10864): 
,I/jxcore-log(10864): Screen Brightness 134
I/jxcore-log(10864): 
,E/jxcore-log(10864): Dummy Error Log.
E/jxcore-log(10864): 
,I/jxcore-log(10864): getBuffer is called!!!!
I/jxcore-log(10864): 
,V/AlarmManager( 3525): waitForAlarm result :8
,D/BluetoothAdapter(10864): disable()
,E/BluetoothManagerService( 3525): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3525): New client listening to asynchronous messages
,I/WifiManager(10864): packageName : com.example.hello
,D/SecContentProvider( 3525): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3525): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 3525): mCursor = null
,D/WifiService( 3525): setWifiEnabled: false pid=10864, uid=10498
,E/WifiService( 3525): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3525): name = wifi_on
,I/jxcore-log(10864): ****TEST TOOK:  5074  ms ****
I/jxcore-log(10864): 
,I/jxcore-log(10864): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10864): 
,D/AndroidRuntime(10963): 
D/AndroidRuntime(10963): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10963): CheckJNI is OFF
,D/AndroidRuntime(10963): readGMSProperty: start
D/AndroidRuntime(10963): readGMSProperty: already setted!!
D/AndroidRuntime(10963): readGMSProperty: end
D/AndroidRuntime(10963): addProductProperty: start
,E/AffinityControl(10963): AffinityControl: registerfunction enter
,D/SSRM:n  ( 3525): SIOP:: AP = 240, PST = 246, CUR = 34
,D/AndroidRuntime(10963): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3525): START PACKAGE DELETE: observer{921977149}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
,D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 3525): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3525): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3525): !@killApplicatoin: 10498, uninstall pkg
D/PackageManagerService( 3525): deletePackage- pkg:com.example.hello, edmuserId:0
I/ActivityManager( 3525): Force stopping com.example.hello appid=10498 user=-1: uninstall pkg
D/PackageManagerService( 3525): deletePackage- pkg:com.example.hello, edmuserId:-1
I/ActivityManager( 3525): Killing 10864:com.example.hello/u0a498 (adj 0): stop com.example.hello
,D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{3973bdd2 u0 com.example.hello/.MainActivity t25}
,I/SurfaceFlinger( 2852): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2852): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3525): Skipping PackageSetting{ab77768 com.test.thalitest/10496} due to missing metadata
,D/WifiService( 3525): Client connection lost with reason: 4
,I/ActivityManager( 3525): Force stopping com.example.hello appid=10498 user=0: pkg removed
,V/AlarmManager( 3525): waitForAlarm result :8
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 7942): Explicit concurrent mark sweep GC freed 24966(1453KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.087ms total 39.046ms
,I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,W/GeofencerStateMachine( 4260): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 4479): mOCRHelper is null
,D/LWLocationManager(10628): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10628): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (10981): MountEmulatedStorage()
,E/Zygote  (10981): v2
,I/libpersona(10981): KNOX_SDCARD checking this for 10063
I/libpersona(10981): KNOX_SDCARD not a persona
I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10981 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourceType( 4966): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4966): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TimaKeyStoreProvider(10981): TimaSignature is unavailable
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ActivityThread(10981): Added TimaKeyStore provider
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 32705(2MB) AllocSpace objects, 23(368KB) LOS objects, 24% free, 48MB/64MB, paused 3.959ms total 165.565ms
I/art     ( 3525): WaitForGcToComplete blocked for 151.908ms for cause Explicit
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(10981): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10981): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10981): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10981): packagename:com.example.hello
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/Zygote  (10999): MountEmulatedStorage()
E/Zygote  (10999): v2
I/libpersona(10999): KNOX_SDCARD checking this for 10021
I/libpersona(10999): KNOX_SDCARD not a persona
,I/SELinux (10999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux (10999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10999 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,E/SELinux (10999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager( 3525): Killing 10092:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TimaKeyStoreProvider(10999): TimaSignature is unavailable
,D/ActivityThread(10999): Added TimaKeyStore provider
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(10999): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (10999): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Dec 15 15:25:03 GMT+01:00 2015
,I/KLMS-2.4.521: (10999): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
,I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10999): KLMSIntentService(): onCreate()
,W/ResourceType( 3525): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/KLMS-2.4.521: (10999): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (10999): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.521: (10999): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  (11016): MountEmulatedStorage()
E/Zygote  (11016): v2
I/libpersona(11016): KNOX_SDCARD checking this for 10106
I/libpersona(11016): KNOX_SDCARD not a persona
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/SELinux (11016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
I/SELinux (11016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11016 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/KLMS-2.4.521: (10999): KLMSIntentService(): PACKAGE_REMOVED
W/ResourcesManager(10628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 11691(792KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.281ms total 190.477ms
,I/KLMS-2.4.521: (10999): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10999): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/TimaKeyStoreProvider(11016): TimaSignature is unavailable
,E/Zygote  (11031): MountEmulatedStorage()
E/Zygote  (11031): v2
I/libpersona(11031): KNOX_SDCARD checking this for 1000
I/libpersona(11031): KNOX_SDCARD not a persona
,I/SELinux (11031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11031): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11031 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ActivityThread(11016): Added TimaKeyStore provider
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/PackageManager( 3525): delete codoeFile: 
,I/AASAUninstall( 3525):  com.example.hello not target!
,D/PackageManager( 3525): result of delete: 1{921977149}
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/AndroidRuntime(10963): Shutting down VM
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10628): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10628): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10628): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10628): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(11016): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(11031): TimaSignature is unavailable
,D/ActivityThread(11031): Added TimaKeyStore provider
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/elm:14491(11016): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(11016): ELMEngine.ELMEngine( context ).
I/TapandpayWidget:TanpandpayAppWidgetProvider(10487): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10487): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
D/elm:14491(11016): MDMBridge.setEnterpriseBridge()
,I/TapandpayWidget:Utils(10487): Clear T&P info.
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/TapandpayWidget:TanpandpayAppWidgetProvider(10487): Widget is not attached.
,D/elm:14491(11016): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/elm:14491(11016): ElmAgentService : onCreate()
D/elm:14491(11016): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/Mms/FreeMessageStatusReceiver( 9738): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/elm:14491(11016): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11016): MDMBridge.getInstance()
D/elm:14491(11016): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11016): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(11031): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager(11031): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
W/ResourcesManager( 3525): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3525): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.521: (10999): KLMSIntentService(): listeningToPackageRemoved().END
D/Mms/FreeMessageReceiverService( 9738): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 9738): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/elm:14491(11016): ElmAgentService : onDestroy().
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/PackageBroadcastService( 4462): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 4462): Clearing selected account for com.example.hello
,D/ResourcesManager(10628): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/RCPManager(11031):  in createShortcut() for packageName: com.example.hello userId0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/RCPManagerService( 3525):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  (11052): MountEmulatedStorage()
E/Zygote  (11052): v2
I/libpersona(11052): KNOX_SDCARD checking this for 10019
I/libpersona(11052): KNOX_SDCARD not a persona
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux (11052): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/SELinux (11052): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=11052 uid=10019 gids={50019, 9997} abi=armeabi-v7a
D/ResourcesManager(10628): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/SELinux (11052): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3525): stay LED for fully charged
,D/TimaKeyStoreProvider(11052): TimaSignature is unavailable
,D/ActivityThread(11052): Added TimaKeyStore provider
,I/KLMS-2.4.521: (10999): KLMSIntentService(): onDestroy()
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/TactileAssist( 3525): enable value -1
I/TactileAssist( 3525): internal enable value -1
I/TactileAssist( 3525): intensity value -1
I/TactileAssist( 3525): saveAppList value true
,I/TactileAssist( 3525): List of disabled apps :
,I/LocationSettingsChecker( 4462): Removing dialog suppression flag for package com.example.hello
D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/gH_CompatibleDatabase( 4462): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4462): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4462): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 4462): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/gH_CompatibleDatabase( 4462): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4462): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4462): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(11052): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/gH_CompatibleDatabase( 4462): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4462): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4462): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4462): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4462): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4462): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11052): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11052): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(11052): onReceive() : package name is not s health. Return !!!
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 3525): clearDefaults: com.example.hello
I/CrashAnrDetector( 3525): onPackageRemoved : com.example.hello
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/RCPManagerService( 3525): PackageReceiver onReceive()
I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10498
V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager(10628): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/TaskPersister( 3525): removeObsoleteFile: deleting file=25_task.xml
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager( 3525): Killing 10117:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3695): handleTimeUpdate
,D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/KeyguardUpdateMonitor( 3695): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3695): handleBatteryUpdate
,I/Icing   ( 4462): doRemovePackageData com.example.hello
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 3695):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4462): Module APK com.google.android.play.games already loaded
,D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3695): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/LocationWidgetApplication(10628): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,W/ContextImpl(10296): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/KeyguardEffectViewController( 3695): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3695): *** don't update sliding image ***
,D/ChimeraCfgMgr( 4462): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4462): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/SQLiteLog( 4462): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4462): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AndroidRuntime( 4462): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 4462): Process: com.google.android.gms, PID: 4462
E/AndroidRuntime( 4462): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4462): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:474)
E/AndroidRuntime( 4462): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 4462): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 4462): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 4462): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:318)
E/AndroidRuntime( 4462): 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
E/AndroidRuntime( 4462): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 4462): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 4462): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 4462): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 4462): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4462): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4462): 	at java.lang.Thread.run(Thread.java:818)
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/Zygote  (11083): MountEmulatedStorage()
E/Zygote  (11083): v2
I/libpersona(11083): KNOX_SDCARD checking this for 10116
I/libpersona(11083): KNOX_SDCARD not a persona
,I/ActivityManager( 3525): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=11083 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
I/SELinux (11083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3525): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3525): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3525): displayNotification : [02h,0dh,00h]
,D/Compatibility(10173): onReceive() it will make start service
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3525): displayNotification : [0ah,00h,01h]
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3525): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3525): displayNotification : [09h,00h,00h]
,D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/MtpClient( 9204): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient( 9204): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/TimaKeyStoreProvider(11083): TimaSignature is unavailable
,D/ActivityThread(11083): Added TimaKeyStore provider
,D/Compatibility(10173): onHandleIntent()
,D/Compatibility(10173): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10498, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/Compatibility(10173): found: 2
D/Compatibility(10173): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10173): skipping ResolveInfo{3cd86681 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10173): considering ResolveInfo{20252326 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10173): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10173): enabling receiver ResolveInfo{15e9bb67 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/001
,E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/Compatibility(10173): enabling receiver ResolveInfo{24485d14 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ResourcesManager(10628): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/SQLiteLog( 4260): (10) POSIX Error : 9 SQLite Error : 3850
,E/SQLiteLog( 4260): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
,D/AndroidRuntime( 4260): Shutting down VM
,D/ResourcesManager(10628): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/EventHub( 3525): Removing device '/dev/input/event10' due to inotify event
,E/AndroidRuntime( 4260): FATAL EXCEPTION: main
E/AndroidRuntime( 4260): Process: com.google.android.gms.persistent, PID: 4260
E/AndroidRuntime( 4260): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4260): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4260): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4260): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4260): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4260): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4260): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4260): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4260): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4260): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4260): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4260): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4260): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4260): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4260): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4260): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4260): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4260): 	... 9 more
,D/Compatibility(10173): enabling receiver ResolveInfo{10a3e9bd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/Process ( 4462): Sending signal. PID: 4462 SIG: 9
,I/EventHub( 3525): Removing device '/dev/input/event7' due to inotify event
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3525): Removing device '/dev/input/event8' due to inotify event
D/Compatibility(10173): enabling receiver ResolveInfo{c304bb2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  (11107): MountEmulatedStorage()
E/Zygote  (11107): v2
I/libpersona(11107): KNOX_SDCARD checking this for 1000
I/libpersona(11107): KNOX_SDCARD not a persona
,I/SELinux (11107): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3525): Removing device '/dev/input/event9' due to inotify event
,I/SELinux (11107): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11107): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3525): Killing 10157:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,D/ResourcesManager(11083): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/Compatibility(10173): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,W/ActivityManager( 3525): Process com.google.android.gms has crashed too many times: killing!
,I/ActivityManager( 3525): Killing 4260:com.google.android.gms.persistent/u0a14 (adj 0): crash
,D/ConnectivityService( 3525): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@7bfebc8)
D/PowerManagerService( 3525): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10014, pid=4462, ws=WorkSource{10014 com.google.android.gms}) (elapsedTime=211)
,I/EventHub( 3525): Removing device '/dev/input/event11' due to inotify event
,D/ConnectivityService( 3525): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService( 3525): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ResourcesManager(10628): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
,V/BackupManagerService( 3525): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/EventHub( 3525): Removing device '/dev/input/event12' due to inotify event
V/BackupManagerService( 3525): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/TimaKeyStoreProvider(11107): TimaSignature is unavailable
W/ActivityManager( 3525): Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.clearcut.service.ClearcutLoggerService} to connection android.os.BinderProxy@327922af (in com.google.android.gms)
W/ActivityManager( 3525): android.os.DeadObjectException
W/ActivityManager( 3525): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3525): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3525): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3525): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1686)
W/ActivityManager( 3525): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3525): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ActivityThread(11107): Added TimaKeyStore provider
W/ActivityManager( 3525): Failure disconnecting service ComponentInfo{com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService} to connection android.os.BinderProxy@126d24f (in com.google.android.gms)
W/ActivityManager( 3525): android.os.DeadObjectException
W/ActivityManager( 3525): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager( 3525): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager( 3525): 	at android.app.IServiceConnection$Stub$Proxy.connected(IServiceConnection.java:92)
W/ActivityManager( 3525): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1686)
W/ActivityManager( 3525): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2288)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:17705)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:6129)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:7561)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:14542)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:14421)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:15187)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14695)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14677)
W/ActivityManager( 3525): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1457)
W/ActivityManager( 3525): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3123)
W/ActivityManager( 3525): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ResourcesManager(10628): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,W/BroadcastQueue( 3525): Unable to launch app com.google.android.gms/10014 for broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }: process is bad
,E/SQLiteLog(11083): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,I/EventHub( 3525): Removing device '/dev/input/event13' due to inotify event
,E/SQLiteDatabase(11083): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(11083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(11083): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(11083): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(11083): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(11083): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(11083): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper(11083): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(11083): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(11083): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(11083): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(11083): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(11083): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(11083): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(11083): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(11083): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(11083): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ActivityManager( 3525): Process com.google.android.gms (pid 4462)(adj 0) has died(280,1316)
,W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
,W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20998ms
W/SQLiteOpenHelper(11083): Opened filter.db in read-only mode
,W/ActivityManager( 3525): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30996ms
,E/SQLiteLog(11083): (284) automatic index on titles(filter_id),
,I/EventHub( 3525): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(11107): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/LocationManagerService( 3525): Location listener died
I/LocationManagerService( 3525): remove 1bfe9ebd by com.google.android.gms
,D/LocationManagerService( 3525): provider request: passive ProviderRequest[ON interval=0]
D/WifiService( 3525): Client connection lost with reason: 4
,D/GpsStatusListenerHelper( 3525): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@39fa1b86
,D/LocationManagerService( 3525): Location listener died
I/LocationManagerService( 3525): remove 2b1fe8d3 by com.google.android.gms
D/LocationManagerService( 3525): provider request: passive ProviderRequest[ON interval=0]
,I/PCWCLIENTTRACE_LOG(11107): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11107): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11107): new DMDBOpenHelper instance
,E/SQLiteLog(11107): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(11107): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(11107): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11107): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(11107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(11107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(11107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11107): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11107): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11107): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11107): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11107): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11107): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(11107): Shutting down VM
,E/AndroidRuntime(11107): FATAL EXCEPTION: main
E/AndroidRuntime(11107): Process: com.sec.pcw.device, PID: 11107
E/AndroidRuntime(11107): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11107): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(11107): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(11107): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(11107): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(11107): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(11107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11107): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11107): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(11107): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(11107): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(11107): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(11107): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(11107): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11107): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11107): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11107): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11107): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(11107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(11107): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(11107): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(11107): 	... 11 more
E/ActivityThread(10526): Failed to find provider info for com.facebook.appmanager.installrecord
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3525): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3525): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3525): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3525): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3525): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3525): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3525): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3525): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3525): 	... 5 more
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11128): MountEmulatedStorage()
E/Zygote  (11128): v2
I/libpersona(11128): KNOX_SDCARD checking this for 10035
I/libpersona(11128): KNOX_SDCARD not a persona
I/SELinux (11128): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11128): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=11128 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (11128): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
