#### Test 502422852e23b2c_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
E/Watchdog( 3515): !@Sync 3
,--------- beginning of main
D/AndroidRuntime(10522): 
D/AndroidRuntime(10522): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10522): CheckJNI is OFF
D/AndroidRuntime(10522): readGMSProperty: start
D/AndroidRuntime(10522): readGMSProperty: already setted!!
D/AndroidRuntime(10522): readGMSProperty: end
D/AndroidRuntime(10522): addProductProperty: start
E/AffinityControl(10522): AffinityControl: registerfunction enter
D/AndroidRuntime(10522): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3515): inState():  stateMachine is null !!
I/PersonaManagerService( 3515): PersonaId don't exist
I/ActivityManager( 3515): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3515): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3515): mDVFSHelper.acquire()
D/FocusedStackFrame( 3515): Set to : 0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/Zygote  (10540): MountEmulatedStorage()
E/Zygote  (10540): v2
I/libpersona(10540): KNOX_SDCARD checking this for 10460
I/libpersona(10540): KNOX_SDCARD not a persona
I/SELinux (10540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10540): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10540 uid=10460 gids={50460, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime(10522): Shutting down VM
D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
V/AlarmManager( 3515): waitForAlarm result :8
D/TimaKeyStoreProvider(10540): TimaSignature is unavailable
D/ActivityThread(10540): Added TimaKeyStore provider
V/WindowOrientationListener( 3515): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3515): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3515): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3515): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3515): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10540): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 4000): updateVisibility : ActivityRecord{198277a4 token=android.os.BinderProxy@2ac17d96 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4000): onTrimMemory. Level: 20
D/BatteryService( 3515): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3515): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3515): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:58
D/BatteryService( 3515): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3515): stay LED for fully charged
I/MotionRecognitionService( 3515): Plugged
I/MotionRecognitionService( 3515): setPowerConnected  = true
D/KeyguardUpdateMonitor( 3694): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3694): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3694):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3694): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/WebViewFactory(10540): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10540): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(10540): Loading: webviewchromium
,I/LibraryLoader(10540): Time to load native libraries: 9 ms (timestamps 4092-4101)
,I/LibraryLoader(10540): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(10540): Binding Chromium to main looper Looper (main, tid 1) {5414245}
,I/LibraryLoader(10540): Expected native library version number "",actual native library version number ""
,I/chromium(10540): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10540): Initializing chromium process, renderers=0
,W/art     (10540): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10540): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10540): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,D/BluetoothAdapter(10540): 626552218: getState() :  mService = null. Returning STATE_OFF
,I/chromium(10540): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(10540): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(10540): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10540): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10540): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10540): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10540): CordovaWebView is running on device made by: samsung
,W/art     (10540): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10540): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10540): performCreate Call secproduct feature valuefalse
D/Activity(10540): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10540): Render dirty regions requested: true
,D/ActivityManager( 3515): post active user change for 0
D/KnoxTimeoutHandler( 3515): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3515): handleActiveUserChange for user 0
,D/SSRM:n  ( 3515): SIOP:: AP = 260, PST = 293, CUR = 52
,I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3515): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10540): Initialized EGL, version 1.4
,I/OpenGLRenderer(10540): HWUI protection enabled for context ,  &this =0xaf845060 ,&mEglDisplay = 1 , &mEglConfig = -1278963440 
,D/OpenGLRenderer(10540): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10540): Enabling debug mode 0
,D/mali_winsys(10540): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10540): updateVisibility : ActivityRecord{17f7714a token=android.os.BinderProxy@343dbd90 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3515): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3515): mDVFSHelper.release()
I/Timeline( 3515): Timeline: Activity_windows_visible id: ActivityRecord{14a49c37 u0 com.example.hello/.MainActivity t28} time:104537
W/IInputConnectionWrapper(10540): showStatusIcon on inactive InputConnection
I/Timeline(10540): Timeline: Activity_idle id: android.os.BinderProxy@343dbd90 time:104543
,I/chromium(10540): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(10540): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/JsMessageQueue(10540): Set native->JS mode to OnlineEventsBridgeMode
,I/chromium(10540): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10540): 
,D/jxcore_app_log(10540): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358474752
D/JX-Cordova(10540): jxcore cordova android initializing
,W/jxcore-log(10540): Initializing JXcore engine
,W/jxcore-log(10540): JXcore engine is ready
,W/jxcore-log(10540): Starting JXcore engine
,E/auditd  ( 4536): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3515): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3515): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10540): Platform android
W/jxcore-log(10540): 
W/jxcore-log(10540): Process ARCH arm
W/jxcore-log(10540): 
,I/jxcore-log(10540): JXcore Cordova bridge is ready!
I/jxcore-log(10540): 
W/jxcore-log(10540): JXcore engine is started
,E/jxcore-log(10540): >> samsung-SM-N910C
E/jxcore-log(10540): 
,I/jxcore-log(10540): Total memory 2970812416
I/jxcore-log(10540): 
,I/jxcore-log(10540): Free memory 123568128
I/jxcore-log(10540): 
I/jxcore-log(10540): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10540): 
I/jxcore-log(10540): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10540): 
,I/jxcore-log(10540): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10540): 
,I/jxcore-log(10540): Size 1440 2560
I/jxcore-log(10540): 
,I/jxcore-log(10540): Screen Brightness 134
I/jxcore-log(10540): 
,E/jxcore-log(10540): Dummy Error Log.
E/jxcore-log(10540): 
,W/ContextImpl( 3515): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(10540): getBuffer is called!!!!
I/jxcore-log(10540): 
,I/PowerManagerService( 3515): [PWL] Off : 15s ago
,D/BluetoothAdapter(10540): disable(),
,E/BluetoothManagerService( 3515): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3515): New client listening to asynchronous messages
,I/WifiManager(10540): packageName : com.example.hello
,D/SecContentProvider( 3515): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3515): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3515): mCursor = null
,D/WifiService( 3515): setWifiEnabled: false pid=10540, uid=10460
,E/WifiService( 3515): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3515): name = wifi_on
,I/jxcore-log(10540): ****TEST TOOK:  5075  ms ****
I/jxcore-log(10540): 
,I/jxcore-log(10540): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10540): 
,D/AndroidRuntime(10655): 
D/AndroidRuntime(10655): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10655): CheckJNI is OFF
,D/AndroidRuntime(10655): readGMSProperty: start
D/AndroidRuntime(10655): readGMSProperty: already setted!!
,D/AndroidRuntime(10655): readGMSProperty: end
D/AndroidRuntime(10655): addProductProperty: start
,E/AffinityControl(10655): AffinityControl: registerfunction enter
,D/AndroidRuntime(10655): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3515): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3515): START PACKAGE DELETE: observer{389617302}
D/PackageManager( 3515): pkg{<packageName>}
D/PackageManager( 3515): user{0}
D/PackageManager( 3515): caller{2000}
D/PackageManager( 3515): flags{3}
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3515): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3515): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3515): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3515): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3515): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3515): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3515): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3515): !@killApplicatoin: 10460, uninstall pkg
,I/ActivityManager( 3515): Force stopping com.example.hello appid=10460 user=-1: uninstall pkg
I/ActivityManager( 3515): Killing 10540:com.example.hello/u0a460 (adj 0): stop com.example.hello
,I/ActivityManager( 3515):   Force finishing activity ActivityRecord{14a49c37 u0 com.example.hello/.MainActivity t28}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3515): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3515): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3515): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3515): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3515): Skipping PackageSetting{aad1a9a com.test.thalitest/10459} due to missing metadata
,D/WifiService( 3515): Client connection lost with reason: 4
,I/ActivityManager( 3515): Force stopping com.example.hello appid=10460 user=0: pkg removed
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 7993): Explicit concurrent mark sweep GC freed 27169(1544KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.077ms total 32.710ms
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
I/InputReader( 3515): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 4208): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 4444): mOCRHelper is null
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
D/LWLocationManager(10133): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10133): getLastUiLocationId() : mLastUiLocationId = -100
,E/Zygote  (10676): MountEmulatedStorage()
,E/Zygote  (10676): v2
I/libpersona(10676): KNOX_SDCARD checking this for 10063
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/libpersona(10676): KNOX_SDCARD not a persona
,W/ResourceType( 4942): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4942): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/SELinux (10676): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3515): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10676 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10676): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10676): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3515): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3515): Admin package name: com.google.android.gms
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/TimaKeyStoreProvider(10676): TimaSignature is unavailable
,D/ActivityThread(10676): Added TimaKeyStore provider
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 37285(2MB) AllocSpace objects, 18(288KB) LOS objects, 24% free, 48MB/64MB, paused 2.115ms total 164.296ms
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/art     ( 3515): WaitForGcToComplete blocked for 72.917ms for cause Explicit
,D/ResourcesManager(10676): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SecContentProvider2( 3515): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3515): mCursor = null
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10676): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10676): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10676): packagename:com.example.hello
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/Zygote  (10693): MountEmulatedStorage()
E/Zygote  (10693): v2
I/libpersona(10693): KNOX_SDCARD checking this for 10021
I/libpersona(10693): KNOX_SDCARD not a persona
,I/SELinux (10693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10693 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 9779:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/RegisteredServicesCache( 3965): empty dynamic service
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/TimaKeyStoreProvider(10693): TimaSignature is unavailable
,D/ActivityThread(10693): Added TimaKeyStore provider
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,W/ResourceType( 3515): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10693): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Drive/Drive.apk
,W/ResourcesManager(10133): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.521: (10693): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 07 15:09:33 GMT+01:00 2015
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(10133): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 3515): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3515): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/KLMS-2.4.521: (10693): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/splitIntent( 3515): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3515): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/art     ( 3515): Explicit concurrent mark sweep GC freed 9380(512KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.207ms total 159.693ms
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/KLMS-2.4.521: (10693): KLMSIntentService(): onCreate()
W/ResourcesManager(10133): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10133): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10133): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10133): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10693): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (10693): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
I/KLMS-2.4.521: (10693): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.4.521: (10693): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (10693): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (10693): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
E/Zygote  (10710): MountEmulatedStorage()
E/Zygote  (10710): v2
I/libpersona(10710): KNOX_SDCARD checking this for 10106
I/libpersona(10710): KNOX_SDCARD not a persona
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux (10710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3515): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10710 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,E/SELinux (10710): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10725): MountEmulatedStorage()
E/Zygote  (10725): v2
I/libpersona(10725): KNOX_SDCARD checking this for 1000
I/libpersona(10725): KNOX_SDCARD not a persona
,I/SELinux (10725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(10710): TimaSignature is unavailable
,D/ActivityThread(10710): Added TimaKeyStore provider
,I/SELinux (10725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10725 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,I/KLMS-2.4.521: (10693): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.4.521: (10693): KLMSIntentService(): onDestroy()
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(10133): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(10710): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/TimaKeyStoreProvider(10725): TimaSignature is unavailable
D/ActivityThread(10725): Added TimaKeyStore provider
,D/Mms/FreeMessageStatusReceiver(10402): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/elm:14491(10710): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(10710): ELMEngine.ELMEngine( context ).
D/elm:14491(10710): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/Mms/FreeMessageReceiverService(10402): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(10402): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(10725): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager(10725): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Books/Books.apk
,D/elm:14491(10710): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/elm:14491(10710): ElmAgentService : onCreate()
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/PackageManager( 3515): delete codoeFile: 
D/elm:14491(10710): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/AASAUninstall( 3515):  com.example.hello not target!
D/PackageManager( 3515): result of delete: 1{389617302}
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/elm:14491(10710): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10710): MDMBridge.getInstance()
D/elm:14491(10710): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/elm:14491(10710): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (10744): MountEmulatedStorage()
W/Resources( 3515): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  (10744): v2
I/libpersona(10744): KNOX_SDCARD checking this for 10190
,I/libpersona(10744): KNOX_SDCARD not a persona
,I/SELinux (10744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/RCPManager(10725):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3515):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3515): queryAllProviders():  providerCallBack is not register for 0
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/AndroidRuntime(10655): Shutting down VM
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/SELinux (10744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/SELinux (10744): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10744 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3515): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/UsbSettingsManager( 3515): clearDefaults: com.example.hello
I/CrashAnrDetector( 3515): onPackageRemoved : com.example.hello
,D/elm:14491(10710): ElmAgentService : onDestroy().
,D/ResourcesManager( 3515): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/RCPManagerService( 3515): PackageReceiver onReceive()
,I/HarmonyEASService( 3515): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3515): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3515): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3515): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3515): uID is 10460
V/EnterpriseBillingPolicy( 3515): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3515): getProfileForApplication - exit null
I/TactileAssist( 3515): enable value -1
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3515): packageModificationReceiver - onreceive - might be a vpn vendor package 
I/TactileAssist( 3515): internal enable value -1
V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - start - com.example.hello
I/TactileAssist( 3515): intensity value -1
I/TactileAssist( 3515): saveAppList value true
V/EnterpriseBillingPolicyStorage( 3515): getBillingProfileForVpnEngine - end - null
,I/TactileAssist( 3515): List of disabled apps :
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10744): TimaSignature is unavailable
,D/ActivityThread(10744): Added TimaKeyStore provider
,D/ResourcesManager(10133): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  (10760): MountEmulatedStorage()
E/Zygote  (10760): v2
I/libpersona(10760): KNOX_SDCARD checking this for 10019
I/libpersona(10760): KNOX_SDCARD not a persona
,I/SELinux (10760): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10760): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10760): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10760 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/TaskPersister( 3515): removeObsoleteFile: deleting file=28_task.xml
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ActivityManager( 3515): Killing 9845:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10760): TimaSignature is unavailable
,D/ActivityThread(10760): Added TimaKeyStore provider
,D/ResourcesManager(10744): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,W/ContextImpl( 9959): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10744): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10744): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,D/ResourcesManager(10760): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,I/TapandpayWidget:Utils(10744): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10744): Widget is not attached.
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/Zygote  (10777): MountEmulatedStorage()
E/Zygote  (10777): v2
I/libpersona(10777): KNOX_SDCARD checking this for 10059
I/libpersona(10777): KNOX_SDCARD not a persona
,I/SELinux (10777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10777): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3515): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10777 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3515): Killing 9869:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10760): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10760): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10760): onReceive() : package name is not s health. Return !!!
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/LocationWidgetApplication(10133): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10777): TimaSignature is unavailable
,D/ActivityThread(10777): Added TimaKeyStore provider
,E/Zygote  (10793): MountEmulatedStorage()
,E/Zygote  (10793): v2
I/libpersona(10793): KNOX_SDCARD checking this for 10116
I/libpersona(10793): KNOX_SDCARD not a persona
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
I/SELinux (10793): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3515): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10793 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,I/SELinux (10793): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10793): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/TimaKeyStoreProvider(10793): TimaSignature is unavailable
,D/ActivityThread(10793): Added TimaKeyStore provider
,D/ResourcesManager(10133): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  (10809): MountEmulatedStorage()
E/Zygote  (10809): v2
I/libpersona(10809): KNOX_SDCARD checking this for 1000
I/libpersona(10809): KNOX_SDCARD not a persona
,I/SELinux (10809): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10809): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(10133): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/SELinux (10809): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10809 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10777): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(10777): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider(10809): TimaSignature is unavailable
,D/ActivityThread(10809): Added TimaKeyStore provider
,D/ResourcesManager(10793): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,E/Zygote  (10825): MountEmulatedStorage()
E/Zygote  (10825): v2
I/libpersona(10825): KNOX_SDCARD checking this for 1000
I/libpersona(10825): KNOX_SDCARD not a persona
,I/ActivityManager( 3515): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10825 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10825): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Killing 9829:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 8730(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 890us total 26.541ms
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,D/Compatibility(10777): onReceive() it will make start service
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 348us total 11.235ms
,D/TimaKeyStoreProvider(10825): TimaSignature is unavailable
,D/ActivityThread(10825): Added TimaKeyStore provider
,D/ResourcesManager(10809): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/art     ( 2880): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 351us total 11.826ms
,D/ResourcesManager(10133): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/SQLiteLog(10793): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10793): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(10793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10793): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(10793): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(10793): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(10793): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(10793): 	at android.os.Binder.execTransact(Binder.java:446)
E/SQLiteOpenHelper(10793): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(10793): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10793): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10793): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10793): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10793): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(10793): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(10793): 	at android.content.Co,ntentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(10793): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(10793): 	at android.os.Binder.execTransact(Binder.java:446)
W/SQLiteOpenHelper(10793): Opened filter.db in read-only mode
D/ResourcesManager(10133): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
E/SQLiteLog(10793): (284) automatic index on titles(filter_id)
E/Zygote  (10840): MountEmulatedStorage()
E/Zygote  (10840): v2
I/libpersona(10840): KNOX_SDCARD checking this for 10110
I/libpersona(10840): KNOX_SDCARD not a persona
,I/SELinux (10840): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3515): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=10840 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux (10840): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3515): Killing 9892:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
E/SELinux (10840): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/lowmemorykiller( 2828): Error writing /proc/9892/oom_score_adj; errno=22
,I/PCWCLIENTTRACE_LOG(10809): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(10809): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10809): new DMDBOpenHelper instance
,E/SQLiteLog(10809): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10809): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
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
E/SQLiteDatabase(10809): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10809): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10809): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10809): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10809): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(10809): Shutting down VM
,E/AndroidRuntime(10809): FATAL EXCEPTION: main
E/AndroidRuntime(10809): Process: com.sec.pcw.device, PID: 10809
E/AndroidRuntime(10809): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10809): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10809): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10809): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10809): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10809): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10809): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10809): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10809): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10809): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10809): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10809): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10809): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10809): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
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
E/AndroidRuntime(10809): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10809): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10809): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10809): 	... 11 more
,D/TimaKeyStoreProvider(10840): TimaSignature is unavailable
,D/ActivityThread(10840): Added TimaKeyStore provider
,D/ResourcesManager(10825): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/Compatibility(10777): onHandleIntent()
,D/Compatibility(10777): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10460, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility(10777): found: 2
,D/Compatibility(10777): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10777): skipping ResolveInfo{22e6a053 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10777): considering ResolveInfo{343dbd90 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10777): default: com.sec.android.app.soundalive.SAControlPanelActivity
,V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,D/Compatibility(10777): enabling receiver ResolveInfo{3b6bc689 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ResourcesManager(10840): creating new AssetManager and set to /data/app/com.facebook.appmanager-2/base.apk
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3515): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3515): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
,D/UsbHostManager( 3515): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3515): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3515): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3515): displayNotification : [09h,00h,00h]
,D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3515): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/Compatibility(10777): enabling receiver ResolveInfo{3a57768e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl(10825): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,I/UpdateIcingCorporaServi( 4053): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Compatibility(10777): enabling receiver ResolveInfo{3d30eeaf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/MtpClient(10316): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(10316): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,D/Compatibility(10777): enabling receiver ResolveInfo{e922bc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility(10777): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,D/UserAnalysis.UserAnalysisBroadcastReceiver(10011): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,D/UserAnalysis.SecurePlaceDbHelper(10011): SecurePlaceDbHelper() 
D/UserAnalysis.UserAnalysisBroadcastReceiver(10011): Create SecureDbHelper
,D/UsbHostManager( 3515): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3515): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,E/SQLiteLog(10825): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10825): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10825): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10825): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10825): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime(10825): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10825): Process: com.android.keychain, PID: 10825
E/AndroidRuntime(10825): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10825): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10825): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10825): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10825): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10825): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime(10825): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10825): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10825): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10825): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,E/SQLiteLog(10011): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
I/EventHub( 3515): Removing device '/dev/input/event10' due to inotify event
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/SQLiteDatabase(10011): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10011): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10011): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteDatabase(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteDatabase(10011): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10011): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper(10011): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10011): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10011): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10011): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteOpenHelper(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteOpenHelper(10011): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteOpenHelper(10011): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper(10011): Opened privacy in read-only mode
,I/EventHub( 3515): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog(10011): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10011): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10011): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10011): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10011): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
E/SQLiteDatabase(10011): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10011): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(10011): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(10011): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(10011): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(10011): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10011): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10011): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(10011): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10011): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10011): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10011): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10011): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10011): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10011): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
W/System.err(10011): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
W/System.err(10011): 	at, java.lang.Thread.run(Thread.java:818)
E/Zygote  (10868): MountEmulatedStorage()
E/Zygote  (10868): v2
I/libpersona(10868): KNOX_SDCARD checking this for 1000
I/libpersona(10868): KNOX_SDCARD not a persona
I/SELinux (10868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3515): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10868 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (10868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10868): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 4053): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4053): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/AndroidRuntime( 4053): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4053): Process: com.google.android.googlequicksearchbox:search, PID: 4053
E/AndroidRuntime( 4053): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4053): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4053): 	at csx.d(PG:186)
E/AndroidRuntime( 4053): 	at cun.g(PG:594)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4053): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
E/AndroidRuntime( 4053): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4053): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4053): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4053): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4053): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4053): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4053): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4053): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3515): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (10882): MountEmulatedStorage()
E/Zygote  (10882): v2
I/libpersona(10882): KNOX_SDCARD checking this for 10035
I/libpersona(10882): KNOX_SDCARD not a persona
,I/SELinux (10882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider(10868): TimaSignature is unavailable
,I/SELinux (10882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ActivityThread(10868): Added TimaKeyStore provider
,I/ActivityManager( 3515): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=10882 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux (10882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3515): Removing device '/dev/input/event9' due to inotify event
,V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
,I/Process (10809): Sending signal. PID: 10809 SIG: 9
E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
I/Process ( 4053): Sending signal. PID: 4053 SIG: 9
,E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3515): checkUser: useridlist=null, currentuser=0
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop184.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,I/EventHub( 3515): Removing device '/dev/input/event11' due to inotify event
,D/TimaKeyStoreProvider(10882): TimaSignature is unavailable
,D/ActivityThread(10882): Added TimaKeyStore provider
,E/Zygote  (10900): MountEmulatedStorage()
,E/Zygote  (10900): v2
I/libpersona(10900): KNOX_SDCARD checking this for 1000
I/libpersona(10900): KNOX_SDCARD not a persona
,D/ResourcesManager(10868): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/SELinux (10900): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3515): Removing device '/dev/input/event12' due to inotify event
,I/SELinux (10900): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3515): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=10900 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10900): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3515): Killing 9944:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/AndroidRuntime(10840): Shutting down VM
,E/AndroidRuntime(10840): FATAL EXCEPTION: main
E/AndroidRuntime(10840): Process: com.facebook.appmanager, PID: 10840
E/AndroidRuntime(10840): java.lang.RuntimeException: Unable to instantiate application com.facebook.oxygen.appmanager.app.AppManagerApplication: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10840): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime(10840): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5088)
E/AndroidRuntime(10840): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10840): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10840): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10840): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10840): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10840): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10840): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10840): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10840): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10840): Caused by: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10840): 	at com.facebook.ab.e.a(FBSoLoader.java:66)
E/AndroidRuntime(10840): 	at com.facebook.base.a.e.attachBaseContext(DelegatingApplication.java:82)
E/AndroidRuntime(10840): 	at android.app.Application.attach(Application.java:205)
E/AndroidRuntime(10840): 	at android.app.Instrumentation.newApplication(Instrumentation.java:1004)
E/AndroidRuntime(10840): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime(10840): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime(10840): 	... 10 more
E/AndroidRuntime(10840): Caused by: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10840): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/AndroidRuntime(10840): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/AndroidRuntime(10840): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/AndroidRuntime(10840): 	at com.facebook.soloader.e.<init>(FileLocker.java:20)
E/AndroidRuntime(10840): 	at com.facebook.soloader.e.a(FileLocker.java:16)
E/AndroidRuntime(10840): 	at com.facebook.soloader.SysUtil.a(SysUtil.java:215)
E/AndroidRuntime(10840): 	at com.facebook.ab.d.a(DirectorySoSourceWithAssets.java:69)
E/AndroidRuntime(10840): 	at com.facebook.ab.e.a(FBSoLoader.java:63)
E/AndroidRuntime(10840): 	... 15 more
E/AndroidRuntime(10840): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10840): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime(10840): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime(10840): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/AndroidRuntime(10840): 	... 22 more
,I/EventHub( 3515): Removing device '/dev/input/event13' due to inotify event
,D/WifiService( 3515): Client connection lost with reason: 4
,I/ActivityManager( 3515): Process com.sec.pcw.device (pid 10809)(adj 9) has died(178,1310)
,D/AcmsPackageEventListener(10868): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl(10868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/Process (10825): Sending signal. PID: 10825 SIG: 9
,D/TimaKeyStoreProvider(10900): TimaSignature is unavailable
,D/ActivityThread(10900): Added TimaKeyStore provider
,I/EventHub( 3515): Removing device '/dev/input/event14' due to inotify event
,D/AcmsService(10868): Enter Oncreate
D/AcmsServiceMonitor(10868): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10868): creating AcmsCore
I/ActivityManager( 3515): Process com.google.android.googlequicksearchbox:search (pid 4053)(adj 5) has died(181,1310)
D/AcmsCore(10868): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10868): AcmsCore
,V/ApplicationPolicy( 3515): isApplicationStateBlocked userId 0 pkgname com.facebook.appmanager
D/AcmsCore(10868): init
D/AcmsCore(10868): Looper handler is not null
D/AcmsCore(10868): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10868): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10868): Incrementing - Counter value: 1
D/AcmsCore(10868): Incremented Counter Value: postToAcmsCoreHandler =>1
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
D/AcmsCertificateMngr(10868): AcmsCertificateMngr
D/AcmsService(10868): onStartCommand
D/AcmsService(10868): Action: android.intent.action.PACKAGE_REMOVED
D/AcmsServiceMonitor(10868): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10868): Incrementing - Counter value: 2
D/AcmsService(10868): Incremented Counter Value : onStartCommand
D/AcmsRevocationMngr(10868): AcmsRevocationMngr
,W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
W/ActivityManager( 3515): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 10999ms
,D/ResourcesManager(10882): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager( 3515): Killing 10044:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
,D/ActivityThread(10868): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,E/DropBoxManagerService( 3515): Can't write: system_app_crash
E/DropBoxManagerService( 3515): java.io.FileNotFoundException: /data/system/dropbox/drop185.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3515): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3515): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3515): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3515): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3515): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3515): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3515): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3515): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3515): 	... 5 more
,E/SQLiteLog(10868): (28) failed to open "/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10868): Failed to open database '/data/data/com.samsung.android.app.mirrorlink/databases/pkgnamedb'.
E/SQLiteDatabase(10868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/SQLiteDatabase(10868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/SQLiteDatabase(10868): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/SQLiteDatabase(10868): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/SQLiteDatabase(10868): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/SQLiteDatabase(10868): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/SQLiteDatabase(10868): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/SQLiteDatabase(10868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10868): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10868): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10868): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10868): Shutting down VM
,E/AndroidRuntime(10868): FATAL EXCEPTION: main
E/AndroidRuntime(10868): Process: ACMS.Process, PID: 10868
E/AndroidRuntime(10868): java.lang.RuntimeException: Unable to start service com.samsung.android.mirrorlink.acms.api.AcmsService@3b6bc689 with Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService (has extras) }: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10868): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3326)
E/AndroidRuntime(10868): 	at android.app.ActivityThread.access$2200(ActivityThread.java:178)
E/AndroidRuntime(10868): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1547)
E/AndroidRuntime(10868): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10868): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10868): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10868): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10868): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10868): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10868): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10868): Caused by: java.lang.RuntimeException: Unable to get provider com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10868): 	at android.app.ActivityThread.acquireProvider(ActivityThread.java:5197)
E/AndroidRuntime(10868): 	at android.app.ContextImpl$ApplicationContentResolver.acquireUnstableProvider(ContextImpl.java:2946)
E/AndroidRuntime(10868): 	at android.content.ContentResolver.acquireUnstableProvider(ContentResolver.java:1452)
E/AndroidRuntime(10868): 	at android.content.ContentResolver.query(ContentResolver.java:468)
E/AndroidRuntime(10868): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.checkIfPkgNameExists(AppEntryInterface.java:68)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.<init>(AppEntryInterface.java:53)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.provider.AppEntryInterface.getAppEntryInterface(AppEntryInterface.java:61)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.handleStartIntent(AcmsService.java:95)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.api.AcmsService.onStartCommand(AcmsService.java:77)
E/AndroidRuntime(10868): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3309)
E/AndroidRuntime(10868): 	... 9 more
E/AndroidRuntime(10868): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10868): 	at android.dat,abase.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10868): 	at com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide.onCreate(AcmsPkgNameProvide.java:61)
E/AndroidRuntime(10868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10868): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10868): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10868): 	... 20 more

```
