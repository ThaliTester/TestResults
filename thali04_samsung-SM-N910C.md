#### Test 50242285feafdeb_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,D/BatteryService( 3492): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3492): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 238, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3492): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3492): stay LED for fully charged
D/BatteryService( 3492): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 3492): Plugged
I/MotionRecognitionService( 3492): setPowerConnected  = true
--------- beginning of main
D/KeyguardUpdateMonitor( 3696): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3696): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 3696):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3696): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime(10739): 
D/AndroidRuntime(10739): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(10739): CheckJNI is OFF
D/AndroidRuntime(10739): readGMSProperty: start
D/AndroidRuntime(10739): readGMSProperty: already setted!!
D/AndroidRuntime(10739): readGMSProperty: end
D/AndroidRuntime(10739): addProductProperty: start
W/ContextImpl( 3492): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/AffinityControl(10739): AffinityControl: registerfunction enter
D/AndroidRuntime(10739): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3492): inState():  stateMachine is null !!
I/PersonaManagerService( 3492): PersonaId don't exist
I/ActivityManager( 3492): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3492): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager( 3492): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3492): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ActivityManager( 3492): mDVFSHelper.acquire()
D/FocusedStackFrame( 3492): Set to : 0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/Zygote  (10759): MountEmulatedStorage()
E/Zygote  (10759): v2
I/libpersona(10759): KNOX_SDCARD checking this for 10563
I/libpersona(10759): KNOX_SDCARD not a persona
I/SELinux (10759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (10759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3492): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=10759 uid=10563 gids={50563, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime(10739): Shutting down VM
E/SELinux (10759): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3492): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3492): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3492): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3492): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(10759): TimaSignature is unavailable
D/ActivityThread(10759): Added TimaKeyStore provider
V/WindowOrientationListener( 3492): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3492): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener( 3492): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager( 3492): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3492): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger( 2849): id=8 Removed Mauncher (-2/8)
D/ResourcesManager(10759): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
V/ActivityThread( 4003): updateVisibility : ActivityRecord{4ac703a token=android.os.BinderProxy@2ccfd945 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 4003): onTrimMemory. Level: 20
I/WebViewFactory(10759): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(10759): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(10759): Loading: webviewchromium
,I/LibraryLoader(10759): Time to load native libraries: 6 ms (timestamps 5950-5956)
I/LibraryLoader(10759): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider(10759): Binding Chromium to main looper Looper (main, tid 1) {13dad7e3}
I/LibraryLoader(10759): Expected native library version number "",actual native library version number ""
I/chromium(10759): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController(10759): Initializing chromium process, renderers=0
W/art     (10759): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium(10759): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium(10759): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium(10759): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(10759): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter(10759): 1049052640: getState() :  mService = null. Returning STATE_OFF
W/chromium(10759): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium(10759): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     (10759): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents(10759): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine(10759): CordovaWebView is running on device made by: samsung
W/art     (10759): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (10759): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity(10759): performCreate Call secproduct feature valuefalse
D/Activity(10759): performCreate Call debug elastic valuetrue
D/OpenGLRenderer(10759): Render dirty regions requested: true
D/ActivityManager( 3492): post active user change for 0
D/KnoxTimeoutHandler( 3492): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3492): handleActiveUserChange for user 0
I/SurfaceFlinger( 2849): id=12 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService( 3492): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 3492): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 3492): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3492): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3492): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3492): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(10759): Initialized EGL, version 1.4
I/OpenGLRenderer(10759): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1278893808 
D/OpenGLRenderer(10759): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(10759): Enabling debug mode 0
D/mali_winsys(10759): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/ActivityThread(10759): updateVisibility : ActivityRecord{67e710 token=android.os.BinderProxy@3d3c4586 {com.example.hello/com.example.hello.MainActivity}} show : true
D/InputMethodManagerService( 3492): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 3492): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager( 3492): mDVFSHelper.release()
I/Timeline( 3492): Timeline: Activity_windows_visible id: ActivityRecord{354ff6d9 u0 com.example.hello/.MainActivity t25} time:226443
W/IInputConnectionWrapper(10759): showStatusIcon on inactive InputConnection
I/Timeline(10759): Timeline: Activity_idle id: android.os.BinderProxy@3d3c4586 time:226449
I/chromium(10759): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler(10759): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium(10759): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(10759): 
D/JsMessageQueue(10759): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(10759): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1358473472
,W/jxcore-log(10759): Initializing JXcore engine
W/jxcore-log(10759): JXcore engine is ready
,E/auditd  ( 4544): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3492): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3492): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3492): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(10759): Starting JXcore engine
,W/jxcore-log(10759): Platform android
W/jxcore-log(10759): 
W/jxcore-log(10759): Process ARCH arm
W/jxcore-log(10759): 
,I/jxcore-log(10759): JXcore Cordova bridge is ready!
I/jxcore-log(10759): 
,W/jxcore-log(10759): JXcore engine is started
,E/jxcore-log(10759): >> samsung-SM-N910C
E/jxcore-log(10759): 
,I/jxcore-log(10759): Total memory 2970812416
I/jxcore-log(10759): 
,I/jxcore-log(10759): Free memory 158277632
I/jxcore-log(10759): 
I/jxcore-log(10759): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10759): 
I/jxcore-log(10759): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log(10759): 
,I/jxcore-log(10759): userPath [ 'rList-com.example.hello.MainActivity', 'www', 'www' ]
I/jxcore-log(10759): 
,I/jxcore-log(10759): Size 1440 2560
I/jxcore-log(10759): 
,I/jxcore-log(10759): Screen Brightness 134
I/jxcore-log(10759): 
,E/jxcore-log(10759): Dummy Error Log.
E/jxcore-log(10759): 
,I/jxcore-log(10759): getBuffer is called!!!!
I/jxcore-log(10759): 
,D/BluetoothAdapter(10759): disable(),
,E/BluetoothManagerService( 3492): Bluetooth is already disabled. DO NOT disable again.
,D/WifiService( 3492): New client listening to asynchronous messages
,I/WifiManager(10759): packageName : com.example.hello
,D/SecContentProvider( 3492): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 3492): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 3492): mCursor = null
,D/WifiService( 3492): setWifiEnabled: false pid=10759, uid=10563
,E/WifiService( 3492): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider( 3492): name = wifi_on
,I/jxcore-log(10759): ****TEST TOOK:  5070  ms ****
I/jxcore-log(10759): 
,I/jxcore-log(10759): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(10759): 
,D/AndroidRuntime(10874): 
D/AndroidRuntime(10874): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(10874): CheckJNI is OFF
,D/AndroidRuntime(10874): readGMSProperty: start
D/AndroidRuntime(10874): readGMSProperty: already setted!!
,D/AndroidRuntime(10874): readGMSProperty: end
D/AndroidRuntime(10874): addProductProperty: start
,E/AffinityControl(10874): AffinityControl: registerfunction enter
,D/AndroidRuntime(10874): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3492): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3492): START PACKAGE DELETE: observer{557763456}
D/PackageManager( 3492): pkg{<packageName>}
D/PackageManager( 3492): user{0}
D/PackageManager( 3492): caller{2000}
D/PackageManager( 3492): flags{3}
D/PersonaManagerService( 3492): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3492): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3492): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3492): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 3492): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManagerService( 3492): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 3492): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 3492): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3492): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3492): !@killApplicatoin: 10563, uninstall pkg
,I/ActivityManager( 3492): Force stopping com.example.hello appid=10563 user=-1: uninstall pkg
,I/ActivityManager( 3492): Killing 10759:com.example.hello/u0a563 (adj 0): stop com.example.hello
,I/ActivityManager( 3492):   Force finishing activity ActivityRecord{354ff6d9 u0 com.example.hello/.MainActivity t25}
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (6/8)
,I/SurfaceFlinger( 2849): id=12 Removed NainActivit (-2/8)
,D/PointerIcon( 3492): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3492): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3492): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3492): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 3492): Skipping PackageSetting{238c2199 com.test.thalitest/10560} due to missing metadata
,D/WifiService( 3492): Client connection lost with reason: 4
,I/ActivityManager( 3492): Force stopping com.example.hello appid=10563 user=0: pkg removed
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 8323): Explicit concurrent mark sweep GC freed 748(49KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 3.088ms total 32.876ms
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 7970): Explicit concurrent mark sweep GC freed 26374(1511KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.084ms total 47.978ms
,E/SamsungIME( 4436): mOCRHelper is null
,I/InputReader( 3492): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 4191): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/LWLocationManager(10549): getDeviceLocationId :  id = -100
,D/LocationWidgetApplication(10549): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10895): MountEmulatedStorage()
E/Zygote  (10895): v2
I/libpersona(10895): KNOX_SDCARD checking this for 10063
I/libpersona(10895): KNOX_SDCARD not a persona
,I/SELinux (10895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3492): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=10895 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (10895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/ResourceType( 4942): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 4942): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/TimaKeyStoreProvider(10895): TimaSignature is unavailable
,D/ActivityThread(10895): Added TimaKeyStore provider
,D/EnterpriseDeviceManagerService( 3492): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3492): Admin package name: com.google.android.gms
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(10895): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/art     ( 3492): Explicit concurrent mark sweep GC freed 32746(2MB) AllocSpace objects, 26(416KB) LOS objects, 24% free, 48MB/64MB, paused 7.843ms total 168.979ms
,D/ResourcesManager( 3492): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 3492): WaitForGcToComplete blocked for 156.497ms for cause Explicit
D/VRSetupWizardStub/PackageIntentReceiver(10895): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(10895): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(10895): packagename:com.example.hello
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Music2/Music2.apk
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  (10912): MountEmulatedStorage()
E/Zygote  (10912): v2
I/libpersona(10912): KNOX_SDCARD checking this for 10021
I/libpersona(10912): KNOX_SDCARD not a persona
,I/SELinux (10912): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/SELinux (10912): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3492): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=10912 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (10912): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ActivityManager( 3492): Killing 10007:com.sec.spp.push/u0a39 (adj 15): bgCount ##31
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/TimaKeyStoreProvider(10912): TimaSignature is unavailable
,D/ActivityThread(10912): Added TimaKeyStore provider
,D/SecContentProvider2( 3492): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3492): mCursor = null
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/RegisteredServicesCache( 3963): empty dynamic service
,D/ResourcesManager(10912): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (10912): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 23:51:54 GMT+01:00 2016
D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,I/KLMS-2.4.521: (10912): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3492): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3492): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (10912): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (10912): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,I/KLMS-2.4.521: (10912): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (10912): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (10912): KLMSIntentService(): PACKAGE_REMOVED
E/Zygote  (10929): MountEmulatedStorage()
E/Zygote  (10929): v2
I/libpersona(10929): KNOX_SDCARD checking this for 10106
I/libpersona(10929): KNOX_SDCARD not a persona
,I/SELinux (10929): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (10912): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     ( 3492): Explicit concurrent mark sweep GC freed 8682(577KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.950ms total 121.477ms
,I/ActivityManager( 3492): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=10929 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/SELinux (10929): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10929): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (10912): KLMSIntentService(): REPLACING: false | pkgName: com.example.hello
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10549): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10929): TimaSignature is unavailable
,D/ActivityThread(10929): Added TimaKeyStore provider
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  (10944): MountEmulatedStorage()
E/Zygote  (10944): v2
I/libpersona(10944): KNOX_SDCARD checking this for 1000
I/libpersona(10944): KNOX_SDCARD not a persona
,I/SELinux (10944): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10944): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10944): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3492): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=10944 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8725(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 434us total 11.974ms
,D/ResourcesManager(10929): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,W/ResourceType( 3492): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 292us total 9.722ms
,D/TimaKeyStoreProvider(10944): TimaSignature is unavailable
,D/ActivityThread(10944): Added TimaKeyStore provider
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/elm:14491(10929): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(10929): ELMEngine.ELMEngine( context ).
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 298us total 9.815ms
D/elm:14491(10929): MDMBridge.setEnterpriseBridge()
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10549): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10549): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10549): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10549): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager(10944): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,I/KLMS-2.4.521: (10912): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:14491(10929): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14491(10929): ElmAgentService : onCreate()
,D/elm:14491(10929): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,W/ResourcesManager(10944): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:14491(10929): MainReceiver.listeningToPackageRemoved()
D/elm:14491(10929): MDMBridge.getInstance()
D/elm:14491(10929): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(10929): MDMBridge.getAllLicenseInfoFromSDK()
,D/Mms/FreeMessageStatusReceiver( 7824): onReceive, action : android.intent.action.PACKAGE_REMOVED
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/KLMS-2.4.521: (10912): KLMSIntentService(): onDestroy()
I/TapandpayWidget:TanpandpayAppWidgetProvider(10406): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10406): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(10406): Clear T&P info.
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
D/TapandpayWidget:TanpandpayAppWidgetProvider(10406): Widget is not attached.
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  (10963): MountEmulatedStorage()
I/libpersona(10963): KNOX_SDCARD checking this for 10019
E/Zygote  (10963): v2
I/libpersona(10963): KNOX_SDCARD not a persona
,I/SELinux (10963): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/RCPManager(10944):  in createShortcut() for packageName: com.example.hello userId0
,D/RCPManagerService( 3492):  in createShortcut() for packageName: com.example.hello userId0
D/RCPManagerService( 3492): queryAllProviders():  providerCallBack is not register for 0
I/SELinux (10963): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3492): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=10963 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux (10963): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:14491(10929): ElmAgentService : onDestroy().
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/Mms/FreeMessageReceiverService( 7824): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 7824): onHandleIntent: ACTION_PACKAGE_REMOVED
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/TactileAssist( 3492): enable value -1
I/TactileAssist( 3492): internal enable value -1
I/TactileAssist( 3492): intensity value -1
I/TactileAssist( 3492): saveAppList value true
,D/TimaKeyStoreProvider(10963): TimaSignature is unavailable
D/ActivityThread(10963): Added TimaKeyStore provider
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
I/TactileAssist( 3492): List of disabled apps :
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/PackageBroadcastService( 4504): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 4504): Clearing selected account for com.example.hello
,D/PackageManager( 3492): delete codoeFile: 
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Books/Books.apk
,I/AASAUninstall( 3492):  com.example.hello not target!
,D/PackageManager( 3492): result of delete: 1{557763456}
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/AndroidRuntime(10874): Shutting down VM
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/LocationSettingsChecker( 4504): Removing dialog suppression flag for package com.example.hello
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(10963): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl(10254): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/gH_CompatibleDatabase( 4504): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4504): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/gH_MetricsDatabase( 4504): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 4504): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/ResourcesManager( 3492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 4504): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
W/ResourcesManager( 3492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 4504): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
W/ResourcesManager( 3492): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/gH_CompatibleDatabase( 4504): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/gH_CompatibleDatabase( 4504): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4504): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 4504): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 4504): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 4504): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 4504): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager( 3492): Killing 10024:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(10963): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(10963): onReceive called  PACKAGE_REMOVED package:com.example.hello
D/com.sec.android.service.health.upgrade.UninstallReceiver(10963): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/Zygote  (10986): MountEmulatedStorage()
E/Zygote  (10986): v2
I/libpersona(10986): KNOX_SDCARD checking this for 10116
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/libpersona(10986): KNOX_SDCARD not a persona
I/SELinux (10986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3492): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager( 3492): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/SELinux (10986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3492): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=10986 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
E/SELinux (10986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager( 3492): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/RCPManagerService( 3492): PackageReceiver onReceive()
I/HarmonyEASService( 3492): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/KnoxMUMContainerPolicy( 3492): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 3492): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 3492): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3492): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3492): uID is 10563
V/EnterpriseBillingPolicy( 3492): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3492): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3492): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3492): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3492): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3492): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 3492): getBillingProfileForVpnEngine - end - null
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3492): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Books/Books.apk
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3492): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider(10986): TimaSignature is unavailable
,D/ActivityThread(10986): Added TimaKeyStore provider
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,I/Icing   ( 4504): doRemovePackageData com.example.hello
,D/UsbSettingsManager( 3492): clearDefaults: com.example.hello
I/CrashAnrDetector( 3492): onPackageRemoved : com.example.hello
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/TaskPersister( 3492): removeObsoleteFile: deleting file=25_task.xml
,D/ResourcesManager(10986): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/LocationWidgetApplication(10549): getLastUiLocationId() : mLastUiLocationId = -100
,D/Compatibility(10117): onReceive() it will make start service
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/Compatibility(10117): onHandleIntent()
,D/Compatibility(10117): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10563, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/Compatibility(10117): found: 2
D/Compatibility(10117): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility(10117): skipping ResolveInfo{2233099 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility(10117): considering ResolveInfo{11207f5e com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility(10117): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility(10117): enabling receiver ResolveInfo{12590f3f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ChimeraCfgMgr( 4504): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4504): Module APK com.google.android.play.games already loaded
,D/Compatibility(10117): enabling receiver ResolveInfo{3c4ae00c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/Compatibility(10117): enabling receiver ResolveInfo{116d3d55 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ChimeraCfgMgr( 4504): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4504): Module APK com.google.android.play.games already loaded
,E/SQLiteLog(10986): (284) automatic index on titles(filter_id)
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/Compatibility(10117): enabling receiver ResolveInfo{38f1336a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,D/Compatibility(10117): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  (11008): MountEmulatedStorage()
E/Zygote  (11008): v2
I/libpersona(11008): KNOX_SDCARD checking this for 1000
I/libpersona(11008): KNOX_SDCARD not a persona
,I/SELinux (11008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/SELinux (11008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3492): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11008 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (11008): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,I/UpdateIcingCorporaServi( 4226): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/TimaKeyStoreProvider(11008): TimaSignature is unavailable
,D/ActivityThread(11008): Added TimaKeyStore provider
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10549): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
E/Zygote  (11025): MountEmulatedStorage()
E/Zygote  (11025): v2
I/libpersona(11025): KNOX_SDCARD checking this for 1000
I/libpersona(11025): KNOX_SDCARD not a persona
,I/SELinux (11025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3492): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=11025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (11025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11025): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3492): Killing 10055:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/ResourcesManager(10549): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,D/ResourcesManager(10549): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/ActivityManager( 3492): Killing 10101:com.sec.android.app.myfiles/u0a53 (adj 15): bgCount ##31
,E/SQLiteLog( 4191): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4191): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 4191): Shutting down VM
,E/AndroidRuntime( 4191): FATAL EXCEPTION: main
E/AndroidRuntime( 4191): Process: com.google.android.gms.persistent, PID: 4191
E/AndroidRuntime( 4191): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4191): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime( 4191): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime( 4191): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime( 4191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4191): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4191): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime( 4191): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 4191): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 4191): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 4191): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 4191): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4191): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4191): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/AndroidRuntime( 4191): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4191): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4191): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
E/AndroidRuntime( 4191): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 4191): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 4191): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 4191): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime( 4191): 	... 9 more
,D/TimaKeyStoreProvider(11025): TimaSignature is unavailable
,D/ActivityThread(11025): Added TimaKeyStore provider
,V/ApplicationPolicy( 3492): isApplicationStateBlocked userId 0 pkgname com.google.android.gms.persistent
,D/ResourcesManager(11008): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/SQLiteLog( 4226): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4226): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/UsbHostManager( 3492): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3492): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3492): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
,D/UsbHostManager( 3492): displayNotification : [0ah,00h,00h]
,D/UsbHostManager( 3492): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3492): displayNotification : [02h,0dh,00h]
,D/UsbHostManager( 3492): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
,D/UsbHostManager( 3492): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3492): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3492): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3492): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,D/UsbHostManager( 3492): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
,D/UsbHostManager( 3492): displayNotification : [09h,00h,00h]
D/UserAnalysis.UserAnalysisBroadcastReceiver(10290): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
D/UserAnalysis.SecurePlaceDbHelper(10290): SecurePlaceDbHelper() 
D/UserAnalysis.UserAnalysisBroadcastReceiver(10290): Create SecureDbHelper
,E/AndroidRuntime( 4226): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 4226): Process: com.google.android.googlequicksearchbox:search, PID: 4226
E/AndroidRuntime( 4226): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 4226): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 4226): 	at csx.d(PG:186)
E/AndroidRuntime( 4226): 	at cun.g(PG:594)
E/AndroidRuntime( 4226): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 4226): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:334)
E/AndroidRuntime( 4226): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4226): 	at cuw.Tg(PG:368)
E/AndroidRuntime( 4226): 	at cuy.ub(PG:301)
E/AndroidRuntime( 4226): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
E/AndroidRuntime( 4226): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
E/AndroidRuntime( 4226): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4226): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4226): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/MtpClient( 9192): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient( 9192): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
,E/SQLiteLog(10290): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10290): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteDatabase(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteDatabase(10290): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10290): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager(11025): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
E/SQLiteOpenHelper(10290): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper(10290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(10290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(10290): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:167)
E/SQLiteOpenHelper(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:336)
E/SQLiteOpenHelper(10290): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteOpenHelper(10290): 	at java.lang.Thread.run(Thread.java:818)
,I/PCWCLIENTTRACE_LOG(11008): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11008): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11008): new DMDBOpenHelper instance
W/SQLiteOpenHelper(10290): Opened privacy in read-only mode
V/ApplicationPolicy( 3492): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
D/UsbHostManager( 3492): usbDeviceRemoved : /dev/bus/usb/001/001
E/SQLiteLog(11008): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
E/UsbHostManager( 3492): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SQLiteDatabase(11008): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(11008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11008): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(11008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(11008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(11008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11008): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11008): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11008): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11008): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(11008): Shutting down VM
E/AndroidRuntime(11008): FATAL EXCEPTION: main
E/AndroidRuntime(11008): Process: com.sec.pcw.device, PID: 11008
E/AndroidRuntime(11008): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(11008): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(11008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(11008): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(11008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(11008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11008): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11008): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(11008): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(11008): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(11008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(11008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(11008): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11008): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(11008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(11008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(11008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(11008): 	... 11 more
E/DropBoxManagerService( 3492): Can't write: system_app_crash
E/DropBoxManagerService( 3492): java.io.FileNotFoundException: /data/system/dropbox/drop180.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3492): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3492): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3492): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3492): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3492): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3492): 	... 5 more
E/SQLiteLog(10290): (28) failed to open "/data/user/0/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(10290): Failed to open database '/data/user/0/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase(10290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10290): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
E/SQLiteDatabase(10290): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
E/SQLiteDatabase(10290): 	at java.lang.Thread.run(Thread.java:818)
W/System.err(10290): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err(10290): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err(10290): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(10290): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10290): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10290): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(10290): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10290): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10290): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10290): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10290): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10290): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10290): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:341)
W/System.err(10290): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$PackageRemovedRunnable.run(UserAnalysisBroadcastReceiver.java:108)
W/System.err(10290): 	at java.lang.Thread.run(Thread.java:818)
W/ContextImpl(11025): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
W/ContextImpl(10135): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2994 
I/EventHub( 3492): Removing device '/dev/input/event10' due to inotify event
I/Process ( 4191): Sending signal. PID: 4191 SIG: 9
D/ResourcesManager(10549): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
E/DropBoxManagerService( 3492): Can't write: system_app_crash
E/DropBoxManagerService( 3492): java.io.FileNotFoundException: /data/system/dropbox/drop181.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3492): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3492): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3492): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3492): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3492): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3492): 	... 5 more
,V/ApplicationPolicy( 3492): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,I/EventHub( 3492): Removing device '/dev/input/event7' due to inotify event
,E/ActivityThread(10447): Failed to find provider info for com.facebook.appmanager.installrecord
,E/SQLiteLog(10135): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/DropBoxManagerService( 3492): Can't write: system_app_crash
E/DropBoxManagerService( 3492): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3492): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3492): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3492): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3492): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3492): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3492): 	... 5 more
I/EventHub( 3492): Removing device '/dev/input/event8' due to inotify event
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,E/SQLiteDatabase(10135): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase(10135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(10135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(10135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(10135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(10135): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase(10135): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase(10135): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(10135): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(10135): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(10135): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err(10135): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,W/System.err(10135): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err(10135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
,E/SQLiteLog(11025): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
W/System.err(10135): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err(10135): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err(10135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err(10135): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err(10135): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
W/System.err(10135): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
W/System.err(10135): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err(10135): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
W/System.err(10135): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err(10135): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err(10135): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err(10135): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err(10135): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err(10135): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err(10135): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(10135): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(10135): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteDatabase(11025): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(11025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11025): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11025): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(11025): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(11025): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(11025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11025): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11025): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime(11025): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(11025): Process: com.android.keychain, PID: 11025
E/AndroidRuntime(11025): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11025): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11025): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11025): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11025): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(11025): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime(11025): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(11025): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11025): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11025): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3492): Removing device '/dev/input/event9' due to inotify event
,E/Zygote  (11054): MountEmulatedStorage()
E/Zygote  (11054): v2
I/libpersona(11054): KNOX_SDCARD checking this for 1000
I/libpersona(11054): KNOX_SDCARD not a persona
,I/SELinux (11054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/GpsStatusListenerHelper( 3492): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@28b86abf
,D/LocationManagerService( 3492): Location listener died
I/LocationManagerService( 3492): remove 101f7daa by com.google.android.gms
,D/LocationManagerService( 3492): provider request: passive ProviderRequest[ON interval=0]
,I/SELinux (11054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/WifiService( 3492): Client connection lost with reason: 4
,E/SELinux (11054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/BackupManagerService( 3492): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager( 3492): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
V/BackupManagerService( 3492): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
,D/LocationManagerService( 3492): Location listener died
,I/LocationManagerService( 3492): remove 1086303e by com.google.android.gms
,D/LocationManagerService( 3492): provider request: passive ProviderRequest[ON interval=0]
,V/ApplicationPolicy( 3492): isApplicationStateBlocked userId 0 pkgname com.android.keychain
I/ActivityManager( 3492): Process com.google.android.gms.persistent (pid 4191)(adj 0) has died(246,1295)
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService$LightweightWorkerService in 1000ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 10999ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 20999ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 30998ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 40998ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 50998ms
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 60998ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 70998ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 80998ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 90997ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 100997ms
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 110997ms
W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 120996ms
,I/EventHub( 3492): Removing device '/dev/input/event11' due to inotify event
,I/Process ( 4226): Sending signal. PID: 4226 SIG: 9
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3492): Removing device '/dev/input/event12' due to inotify event
,D/TimaKeyStoreProvider(11054): TimaSignature is unavailable
D/ActivityThread(11054): Added TimaKeyStore provider
,E/Zygote  (11069): MountEmulatedStorage()
E/Zygote  (11069): v2
I/libpersona(11069): KNOX_SDCARD checking this for 10035
I/libpersona(11069): KNOX_SDCARD not a persona
,I/SELinux (11069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3492): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=11069 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux (11069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/EventHub( 3492): Removing device '/dev/input/event13' due to inotify event
,E/DropBoxManagerService( 3492): Can't write: system_app_crash
E/DropBoxManagerService( 3492): java.io.FileNotFoundException: /data/system/dropbox/drop183.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3492): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3492): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3492): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3492): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3492): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3492): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3492): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3492): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3492): 	... 5 more
,I/Process (11008): Sending signal. PID: 11008 SIG: 9
,W/Icing   ( 4504): Usage report connection failed.
,I/Process (11025): Sending signal. PID: 11025 SIG: 9
,I/EventHub( 3492): Removing device '/dev/input/event14' due to inotify event
,I/ActivityManager( 3492): Killing 10193:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/WifiService( 3492): Client connection lost with reason: 4
,I/ActivityManager( 3492): Process com.google.android.googlequicksearchbox:search (pid 4226)(adj 5) has died(264,1295)
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 130849ms
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 130848ms
,W/ActivityManager( 3492): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 140846ms
,D/TimaKeyStoreProvider(11069): TimaSignature is unavailable
,D/ActivityThread(11069): Added TimaKeyStore provider
,W/RocketImpressions( 4504): ClearcutLogger connection suspended: 1
,W/Icing   ( 4504): Failed to get file descriptor. Status code: 8.
,D/ResourcesManager(11054): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3492): checkUser: useridlist=null, currentuser=0
,E/Zygote  (11085): MountEmulatedStorage()
E/Zygote  (11085): v2
I/libpersona(11085): KNOX_SDCARD checking this for 10014
I/libpersona(11085): KNOX_SDCARD not a persona
,I/SELinux (11085): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11085): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/AcmsPackageEventListener(11054): Received: android.intent.action.PACKAGE_REMOVED
E/SELinux (11085): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ContextImpl(11054): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/ActivityManager( 3492): Start proc com.google.android.gms.persistent for service com.google.android.gms/.icing.service.LightweightIndexService: pid=11085 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a

```
