#### Test 5038801932cd575_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:46, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
D/BatteryService( 3522): stay LED for fully charged
--------- beginning of main
D/KeyguardUpdateMonitor( 3689): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3689): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3689):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3689): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PowerManagerService( 3522): [PWL] Off : 30s ago
D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 291, CUR = 46
,D/AndroidRuntime(10683): 
D/AndroidRuntime(10683): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10683): CheckJNI is OFF
D/AndroidRuntime(10683): readGMSProperty: start
D/AndroidRuntime(10683): readGMSProperty: already setted!!
D/AndroidRuntime(10683): readGMSProperty: end
D/AndroidRuntime(10683): addProductProperty: start
E/AffinityControl(10683): AffinityControl: registerfunction enter
D/AndroidRuntime(10683): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3522): mDVFSHelper.acquire()
D/FocusedStackFrame( 3522): Set to : 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  (10714): MountEmulatedStorage()
I/libpersona(10714): KNOX_SDCARD checking this for 10421
E/Zygote  (10714): v2
I/libpersona(10714): KNOX_SDCARD not a persona
I/SELinux (10714): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10714 uid=10421 gids={50421, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux (10714): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10714): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(10683): Shutting down VM
D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10714): TimaSignature is unavailable
D/ActivityThread(10714): Added TimaKeyStore provider
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3522): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(10714): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
V/ActivityThread( 3997): updateVisibility : ActivityRecord{3a7d3c7b token=android.os.BinderProxy@3344e10c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3997): onTrimMemory. Level: 20
I/WebViewFactory(10714): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10714): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10714): Loading: webviewchromium
I/LibraryLoader(10714): Time to load native libraries: 5 ms (timestamps 5547-5552)
I/LibraryLoader(10714): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10714): Binding Chromium to main looper Looper (main, tid 1) {304f7173}
I/LibraryLoader(10714): Expected native library version number "",actual native library version number ""
I/chromium(10714): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(10714): Initializing chromium process, renderers=0
,W/art     (10714): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(10714): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
,W/chromium(10714): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(10714): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10714): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,D/BluetoothAdapter(10714): 945195056: getState() :  mService = null. Returning STATE_OFF
,W/chromium(10714): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(10714): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (10714): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(10714): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(10714): CordovaWebView is running on device made by: samsung
,W/art     (10714): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10714): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(10714): performCreate Call secproduct feature valuefalse
D/Activity(10714): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(10714): Render dirty regions requested: true
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(10714): Initialized EGL, version 1.4
,I/OpenGLRenderer(10714): HWUI protection enabled for context ,  &this =0xafa45060 ,&mEglDisplay = 1 , &mEglConfig = -1278963440 
,D/OpenGLRenderer(10714): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10714): Enabling debug mode 0
,D/mali_winsys(10714): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(10714): updateVisibility : ActivityRecord{29f45d60 token=android.os.BinderProxy@23844e56 {com.example.hello/com.example.hello.MainActivity}} show : true
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3522): mDVFSHelper.release()
I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{378b0c4c u0 com.example.hello/.MainActivity t28} time:126018
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 48022(2MB) AllocSpace objects, 22(352KB) LOS objects, 24% free, 48MB/64MB, paused 1.665ms total 162.385ms
,W/IInputConnectionWrapper(10714): showStatusIcon on inactive InputConnection
,I/Timeline(10714): Timeline: Activity_idle id: android.os.BinderProxy@23844e56 time:126190
,I/chromium(10714): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler(10714): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium(10714): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10714): 
,D/JsMessageQueue(10714): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(10714): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357916416
,D/JX-Cordova(10714): jxcore cordova android initializing
,W/jxcore-log(10714): Initializing JXcore engine
W/jxcore-log(10714): JXcore engine is ready
,W/jxcore-log(10714): Starting JXcore engine
,E/auditd  ( 4546): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3522): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3522): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10714): Platform android
W/jxcore-log(10714): 
W/jxcore-log(10714): Process ARCH arm
W/jxcore-log(10714): 
,I/jxcore-log(10714): JXcore Cordova bridge is ready!
I/jxcore-log(10714): 
W/jxcore-log(10714): JXcore engine is started
,E/jxcore-log(10714): >> samsung-SM-N910C
E/jxcore-log(10714): 
,I/jxcore-log(10714): Total memory 2970812416
I/jxcore-log(10714): 
,I/jxcore-log(10714): Free memory 126967808
I/jxcore-log(10714): 
I/jxcore-log(10714): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10714): 
I/jxcore-log(10714): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10714): 
,I/jxcore-log(10714): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log(10714): 
,I/jxcore-log(10714): Size 1440 2560
I/jxcore-log(10714): 
,I/jxcore-log(10714): Screen Brightness 134
I/jxcore-log(10714): 
,E/jxcore-log(10714): Dummy Error Log.
E/jxcore-log(10714): 
,I/jxcore-log(10714): getBuffer is called!!!!
I/jxcore-log(10714): 
,D/BluetoothAdapter(10714): disable()
,E/BluetoothManagerService( 3522): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3522): New client listening to asynchronous messages
,I/WifiManager(10714): packageName : com.example.hello
,D/SecContentProvider( 3522): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 3522): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3522): mCursor = null
,D/WifiService( 3522): setWifiEnabled: false pid=10714, uid=10421
E/WifiService( 3522): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3522): name = wifi_on
,I/jxcore-log(10714): ****TEST TOOK:  5073  ms ****
I/jxcore-log(10714): 
,I/jxcore-log(10714): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10714): 
,D/AndroidRuntime(10801): 
D/AndroidRuntime(10801): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10801): CheckJNI is OFF
,D/AndroidRuntime(10801): readGMSProperty: start
D/AndroidRuntime(10801): readGMSProperty: already setted!!
,D/AndroidRuntime(10801): readGMSProperty: end
D/AndroidRuntime(10801): addProductProperty: start
,E/AffinityControl(10801): AffinityControl: registerfunction enter
,D/AndroidRuntime(10801): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3522): START PACKAGE DELETE: observer{998436447}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{3}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3522): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3522): !@killApplicatoin: 10421, uninstall pkg
,I/ActivityManager( 3522): Force stopping com.example.hello appid=10421 user=-1: uninstall pkg
I/ActivityManager( 3522): Killing 10714:com.example.hello/u0a421 (adj 0): stop com.example.hello
,I/ActivityManager( 3522):   Force finishing activity ActivityRecord{378b0c4c u0 com.example.hello/.MainActivity t28}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3522): Skipping PackageSetting{18aeecb6 com.test.thalitest/10418} due to missing metadata
,D/WifiService( 3522): Client connection lost with reason: 4
,I/ActivityManager( 3522): Force stopping com.example.hello appid=10421 user=0: pkg removed
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 7963): Explicit concurrent mark sweep GC freed 27172(1545KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.067ms total 34.487ms
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4257): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 4445): mOCRHelper is null
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/LWLocationManager(10236): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(10236): getLastUiLocationId() : mLastUiLocationId = -100
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Zygote  (10821): MountEmulatedStorage()
E/Zygote  (10821): v2
,I/libpersona(10821): KNOX_SDCARD checking this for 10063
I/libpersona(10821): KNOX_SDCARD not a persona
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10821 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10821): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10821): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10821): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,D/TimaKeyStoreProvider(10821): TimaSignature is unavailable
,D/ActivityThread(10821): Added TimaKeyStore provider
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/ResourceType( 4947): For resource 0x7f020a0f, entry index(2575) is beyond type entryCount(725)
W/ResourceType( 4947): Failure getting entry for 0x7f020a0f (t=1 e=2575) (error -75)
W/ResourceType( 4947): For resource 0x7f020a62, entry index(2658) is beyond type entryCount(725)
W/ResourceType( 4947): Failure getting entry for 0x7f020a62 (t=1 e=2658) (error -75)
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 16619(1401KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 48MB/64MB, paused 2.870ms total 161.304ms
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 3522): WaitForGcToComplete blocked for 150.522ms for cause Explicit
,W/ResourceType( 4947): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 4947): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager(10821): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/VRSetupWizardStub/PackageIntentReceiver(10821): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10821): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10821): packagename:com.example.hello
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/Zygote  (10838): MountEmulatedStorage()
I/libpersona(10838): KNOX_SDCARD checking this for 10021
E/Zygote  (10838): v2
I/libpersona(10838): KNOX_SDCARD not a persona
I/SELinux (10838): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10838 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/SELinux (10838): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10838): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9895:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/TimaKeyStoreProvider(10838): TimaSignature is unavailable
,D/ActivityThread(10838): Added TimaKeyStore provider
,D/RegisteredServicesCache( 3961): empty dynamic service
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10838): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/KLMS-2.4.521: (10838): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Nov 23 22:48:22 GMT+01:00 2015
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (10838): KLMSAbstractReciever(): onReceive().END.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=24, mSplitNum[2]=34 divideNum= 10 r.nextReceiver= 2 receivers.size=44
,I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10838): KLMSIntentService(): onCreate()
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (10838): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
I/KLMS-2.4.521: (10838): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(10236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (10838): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (10838): KLMSIntentService(): PACKAGE_REMOVED
W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/KLMS-2.4.521: (10838): KLMSIntentService(): listeningToPackageRemoved().START
W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 7634(439KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.806ms total 164.534ms
,I/KLMS-2.4.521: (10838): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/Zygote  (10856): MountEmulatedStorage()
E/Zygote  (10856): v2
I/libpersona(10856): KNOX_SDCARD checking this for 10106
I/libpersona(10856): KNOX_SDCARD not a persona
,I/SELinux (10856): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10856): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/SELinux (10856): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10856 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10236): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
W/ResourcesManager(10236): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10236): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10236): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/PackageManager( 3522): delete codoeFile: 
,I/AASAUninstall( 3522):  com.example.hello not target!
,D/PackageManager( 3522): result of delete: 1{998436447}
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/AndroidRuntime(10801): Shutting down VM
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider(10856): TimaSignature is unavailable
,D/ActivityThread(10856): Added TimaKeyStore provider
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(10856): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Watchdog( 3522): !@Sync 4
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(10056): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,I/KLMS-2.4.521: (10838): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:14491(10856): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(10856): ELMEngine.ELMEngine( context ).
,D/elm:14491(10856): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(10236): creating new AssetManager and set to /data/app/com.android.vending-2/base.apk
,E/Zygote  (10873): MountEmulatedStorage()
E/Zygote  (10873): v2
I/libpersona(10873): KNOX_SDCARD checking this for 10190
I/libpersona(10873): KNOX_SDCARD not a persona
,I/SELinux (10873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10873 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/SELinux (10873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10236): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/KLMS-2.4.521: (10838): KLMSIntentService(): onDestroy()
,D/elm:14491(10856): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/elm:14491(10856): ElmAgentService : onCreate()
,D/elm:14491(10856): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/Mms/FreeMessageStatusReceiver(10544): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/elm:14491(10856): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10856): MDMBridge.getInstance()
D/elm:14491(10856): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(10856): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/Zygote  (10890): MountEmulatedStorage()
I/libpersona(10890): KNOX_SDCARD checking this for 10116
E/Zygote  (10890): v2
I/libpersona(10890): KNOX_SDCARD not a persona
,I/SELinux (10890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager( 3522): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10890 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,I/SELinux (10890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10890): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10873): TimaSignature is unavailable
,D/ActivityThread(10873): Added TimaKeyStore provider
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/Mms/FreeMessageReceiverService(10544): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,D/Mms/FreeMessageReceiverService(10544): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/TimaKeyStoreProvider(10890): TimaSignature is unavailable
,D/ActivityThread(10890): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/elm:14491(10856): ElmAgentService : onDestroy().
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager(10873): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(10890): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Books/Books.apk
V/AlarmManager( 3522): waitForAlarm result :4
E/Zygote  (10907): MountEmulatedStorage()
E/Zygote  (10907): v2
I/libpersona(10907): KNOX_SDCARD checking this for 10019
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
I/libpersona(10907): KNOX_SDCARD not a persona
,I/SELinux (10907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10907 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (10907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/RCPManagerService( 3522): PackageReceiver onReceive()
I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/CrashAnrDetector( 3522): onPackageRemoved : com.example.hello
D/UsbSettingsManager( 3522): clearDefaults: com.example.hello
,D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10421
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10873): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10873): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=28_task.xml
,I/TapandpayWidget:Utils(10873): Clear T&P info.
,I/TactileAssist( 3522): enable value -1
,I/TactileAssist( 3522): internal enable value -1
I/TactileAssist( 3522): intensity value -1
I/TactileAssist( 3522): saveAppList value true
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/TimaKeyStoreProvider(10907): TimaSignature is unavailable
,D/ActivityThread(10907): Added TimaKeyStore provider
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10873): Widget is not attached.
,I/TactileAssist( 3522): List of disabled apps :
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/Zygote  (10925): MountEmulatedStorage()
E/Zygote  (10925): v2
I/libpersona(10925): KNOX_SDCARD checking this for 1000
I/libpersona(10925): KNOX_SDCARD not a persona
,I/SELinux (10925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/ActivityManager( 3522): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=10925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager(10907): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/TimaKeyStoreProvider(10925): TimaSignature is unavailable
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ActivityThread(10925): Added TimaKeyStore provider
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/Zygote  (10941): MountEmulatedStorage()
I/libpersona(10941): KNOX_SDCARD checking this for 10059
E/Zygote  (10941): v2
I/libpersona(10941): KNOX_SDCARD not a persona
,I/ActivityManager( 3522): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=10941 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9923:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,I/SELinux (10941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/FileUtils(10890): Failed to chmod(/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/SQLiteLog(10890): (284) automatic index on titles(filter_id)
,I/SELinux (10941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10941): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10925): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (10955): MountEmulatedStorage()
E/Zygote  (10955): v2
I/libpersona(10955): KNOX_SDCARD checking this for 10110
I/libpersona(10955): KNOX_SDCARD not a persona
,I/SELinux (10955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10955): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.packages.PackageReceiver: pid=10955 uid=10110 gids={50110, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
,D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
I/ActivityManager( 3522): Killing 9965:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
,D/TimaKeyStoreProvider(10941): TimaSignature is unavailable
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
D/ActivityThread(10941): Added TimaKeyStore provider
,D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
,D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10907): onReceive()
,I/com.sec.android.service.health.upgrade.UninstallReceiver(10907): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10907): onReceive() : package name is not s health. Return !!!
,W/ContextImpl(10925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,D/MtpClient(10456): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
,D/MtpClient(10456): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
D/TimaKeyStoreProvider(10955): TimaSignature is unavailable
,D/ActivityThread(10955): Added TimaKeyStore provider
,D/ResourcesManager(10941): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,D/LocationWidgetApplication(10236): getLastUiLocationId() : mLastUiLocationId = -100
,W/ResourcesManager(10941): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,E/SQLiteLog(10925): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10925): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(10925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(10925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(10925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10925): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime(10925): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(10925): Process: com.android.keychain, PID: 10925
E/AndroidRuntime(10925): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10925): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10925): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10925): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10925): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(10925): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime(10925): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(10925): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10925): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10925): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager( 3522): Killing 9943:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
,D/Compatibility(10941): onReceive() it will make start service
,D/ResourcesManager(10955): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
,D/ResourcesManager(10236): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
,E/Zygote  (10982): MountEmulatedStorage()
E/Zygote  (10982): v2
I/libpersona(10982): KNOX_SDCARD checking this for 1000
I/libpersona(10982): KNOX_SDCARD not a persona
I/SELinux (10982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10982 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (10982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (10982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8719(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.245ms total 36.771ms
,I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,D/TimaKeyStoreProvider(10982): TimaSignature is unavailable
,D/ActivityThread(10982): Added TimaKeyStore provider
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 618us total 26.287ms
,D/Compatibility(10941): onHandleIntent()
,D/Compatibility(10941): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10421, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility(10941): found: 2
,D/ResourcesManager(10236): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 626us total 26.946ms
,D/Compatibility(10941): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10941): skipping ResolveInfo{3b98071 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10941): considering ResolveInfo{23844e56 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10941): default: com.sec.android.app.soundalive.SAControlPanelActivity
,I/EventHub( 3522): Removing device '/dev/input/event11' due to inotify event
,D/Compatibility(10941): enabling receiver ResolveInfo{1bb7bed7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility(10941): enabling receiver ResolveInfo{3aabf3c4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  (10999): MountEmulatedStorage()
E/Zygote  (10999): v2
I/libpersona(10999): KNOX_SDCARD checking this for 1000
I/libpersona(10999): KNOX_SDCARD not a persona
,I/SELinux (10999): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=10999 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10236): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/EventHub( 3522): Removing device '/dev/input/event12' due to inotify event
I/SELinux (10999): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10999): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Compatibility(10941): enabling receiver ResolveInfo{2d14b2ad com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/EventHub( 3522): Removing device '/dev/input/event13' due to inotify event
,D/TimaKeyStoreProvider(10999): TimaSignature is unavailable
,D/Compatibility(10941): enabling receiver ResolveInfo{1f0ef9e2 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityThread(10999): Added TimaKeyStore provider
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
,I/EventHub( 3522): Removing device '/dev/input/event14' due to inotify event
,D/ResourcesManager(10236): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,D/Compatibility(10941): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/Process (10925): Sending signal. PID: 10925 SIG: 9
,D/AndroidRuntime(10955): Shutting down VM
D/ResourcesManager(10982): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/AndroidRuntime(10955): FATAL EXCEPTION: main
E/AndroidRuntime(10955): Process: com.facebook.appmanager, PID: 10955
E/AndroidRuntime(10955): java.lang.RuntimeException: Unable to instantiate application com.facebook.oxygen.appmanager.app.AppManagerApplication: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10955): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
E/AndroidRuntime(10955): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5088)
E/AndroidRuntime(10955): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10955): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10955): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10955): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10955): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10955): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10955): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10955): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10955): Caused by: java.lang.RuntimeException: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10955): 	at com.facebook.ad.e.a(FBSoLoader.java:66)
E/AndroidRuntime(10955): 	at com.facebook.base.a.f.attachBaseContext(DelegatingApplication.java:81)
E/AndroidRuntime(10955): 	at android.app.Application.attach(Application.java:205)
E/AndroidRuntime(10955): 	at android.app.Instrumentation.newApplication(Instrumentation.java:1004)
E/AndroidRuntime(10955): 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
E/AndroidRuntime(10955): 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
E/AndroidRuntime(10955): 	... 10 more
E/AndroidRuntime(10955): Caused by: java.io.FileNotFoundException: /data/data/com.facebook.appmanager/libs-dir-lock: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10955): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/AndroidRuntime(10955): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/AndroidRuntime(10955): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/AndroidRuntime(10955): 	at com.facebook.soloader.e.<init>(FileLocker.java:20)
E/AndroidRuntime(10955): 	at com.facebook.soloader.e.a(FileLocker.java:16)
E/AndroidRuntime(10955): 	at com.facebook.soloader.SysUtil.a(SysUtil.java:215)
E/AndroidRuntime(10955): 	at com.facebook.ad.d.a(DirectorySoSourceWithAssets.java:69)
E/AndroidRuntime(10955): 	at com.facebook.ad.e.a(FBSoLoader.java:63)
E/AndroidRuntime(10955): 	... 15 more
E/AndroidRuntime(10955): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime(10955): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime(10955): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime(10955): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/AndroidRuntime(10955): 	... 22 more
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.facebook.appmanager
I/ActivityManager( 3522): Killing 9988:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
D/ResourcesManager(10999): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/DropBoxManagerService( 3522): Can't write: system_app_crash
E/DropBoxManagerService( 3522): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3522): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3522): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3522): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3522): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3522): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3522): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3522): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3522): 	... 5 more
,I/UpdateIcingCorporaServi( 4048): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/AcmsPackageEventListener(10982): Received: android.intent.action.PACKAGE_REMOVED
,W/ContextImpl(10982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_LOG(10999): DEFAULT_LOGON : true,
,I/PCWCLIENTTRACE_LOG(10999): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(10999): new DMDBOpenHelper instance
,E/SQLiteLog(10999): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10999): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(10999): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10999): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10999): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10999): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10999): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(10999): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(10999): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(10999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10999): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10999): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(10999): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(10999): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(10999): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(10999): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(10999): Shutting down VM
,E/AndroidRuntime(10999): FATAL EXCEPTION: main
E/AndroidRuntime(10999): Process: com.sec.pcw.device, PID: 10999
E/AndroidRuntime(10999): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10999): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(10999): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(10999): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(10999): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(10999): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(10999): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(10999): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(10999): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(10999): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(10999): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(10999): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(10999): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(10999): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(10999): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(10999): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(10999): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(10999): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(10999): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(10999): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(10999): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(10999): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(10999): 	... 11 more
,E/Zygote  (11018): MountEmulatedStorage()
,E/Zygote  (11018): v2
,I/libpersona(11018): KNOX_SDCARD checking this for 10114
I/libpersona(11018): KNOX_SDCARD not a persona
,I/SELinux (11018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027

```
