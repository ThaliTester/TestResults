#### Test 61699762a45f11c_thali04_samsung-SM-N910C Logs


```
--------- beginning of system
,E/Watchdog( 3496): !@Sync 7
D/SSRM:n  ( 3496): SIOP:: AP = 300, PST = 359, CUR = 123
--------- beginning of main
D/AndroidRuntime(13994): 
D/AndroidRuntime(13994): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13994): CheckJNI is OFF
D/AndroidRuntime(13994): readGMSProperty: start
D/AndroidRuntime(13994): readGMSProperty: already setted!!
D/AndroidRuntime(13994): readGMSProperty: end
D/AndroidRuntime(13994): addProductProperty: start
E/AffinityControl(13994): AffinityControl: registerfunction enter
D/AndroidRuntime(13994): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3496): inState():  stateMachine is null !!
I/PersonaManagerService( 3496): PersonaId don't exist
I/ActivityManager( 3496): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3496): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3496): mDVFSHelper.acquire()
D/FocusedStackFrame( 3496): Set to : 0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/Zygote  (14012): MountEmulatedStorage()
E/Zygote  (14012): v2
I/libpersona(14012): KNOX_SDCARD checking this for 10670
I/libpersona(14012): KNOX_SDCARD not a persona
I/SELinux (14012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3496): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=14012 uid=10670 gids={50670, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux (14012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/AndroidRuntime(13994): Shutting down VM
E/SELinux (14012): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(14012): TimaSignature is unavailable
D/ActivityThread(14012): Added TimaKeyStore provider
V/WindowOrientationListener( 3496): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3496): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3496): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3496): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3496): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/ResourcesManager(14012): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/SurfaceFlinger( 2849): id=12 Removed Mauncher (4/8)
I/SurfaceFlinger( 2849): id=12 Removed Mauncher (-2/8)
V/ActivityThread( 3999): updateVisibility : ActivityRecord{1b341eec token=android.os.BinderProxy@1552b59e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 3999): onTrimMemory. Level: 20
I/WebViewFactory(14012): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager(14012): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader(14012): Loading: webviewchromium
I/LibraryLoader(14012): Time to load native libraries: 4 ms (timestamps 3955-3959)
I/LibraryLoader(14012): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(14012): Binding Chromium to main looper Looper (main, tid 1) {1b2a88ed}
I/LibraryLoader(14012): Expected native library version number "",actual native library version number ""
I/chromium(14012): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(14012): Initializing chromium process, renderers=0
,W/art     (14012): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(14012): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(14012): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium(14012): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(14012): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(14012): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (14012): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(14012): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine(14012): CordovaWebView is running on device made by: samsung
,W/art     (14012): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (14012): Attempt to remove local handle scope entry from IRT, ignoring
,D/Activity(14012): performCreate Call secproduct feature valuefalse
D/Activity(14012): performCreate Call debug elastic valuetrue
,W/ActivityManager( 3496): Activity pause timeout for ActivityRecord{1d39a38b u0 com.test.thalitest/.MainActivity t27}
,D/OpenGLRenderer(14012): Render dirty regions requested: true
,D/ActivityManager( 3496): post active user change for 0
D/KnoxTimeoutHandler( 3496): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3496): handleActiveUserChange for user 0
,V/ActivityThread(14012): updateVisibility : ActivityRecord{d7128a0 token=android.os.BinderProxy@9c1d63b {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/SurfaceFlinger( 2849): id=15 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 3496): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,I/OpenGLRenderer(14012): Initialized EGL, version 1.4
,I/OpenGLRenderer(14012): HWUI protection enabled for context ,  &this =0xaf945060 ,&mEglDisplay = 1 , &mEglConfig = -1279901424 
,D/OpenGLRenderer(14012): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(14012): Enabling debug mode 0
,D/mali_winsys(14012): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/InputMethodManagerService( 3496): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3496): mDVFSHelper.release()
I/Timeline( 3496): Timeline: Activity_windows_visible id: ActivityRecord{1d39a38b u0 com.test.thalitest/.MainActivity t27} time:224419
,W/IInputConnectionWrapper(14012): showStatusIcon on inactive InputConnection
,I/Timeline(14012): Timeline: Activity_idle id: android.os.BinderProxy@9c1d63b time:224422
,I/chromium(14012): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(14012): 
,D/JsMessageQueue(14012): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(14012): JniHelper::setJavaVM(0xb4d5c280), pthread_self() = -1362668416
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@142aedc9 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(14012): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b22e2fc added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel(14012): addListener: New listener added - the number of listeners is now 1
,D/WifiService( 3496): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(14012): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(14012): setScanMode: 1 -> 2
,I/chromium(14012): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/BatteryService( 3496): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3496): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3496): online:4, current avg:107, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:101
D/BatteryService( 3496): stay LED for fully charged
D/BatteryService( 3496): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3496): Plugged
I/MotionRecognitionService( 3496): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3686): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3686): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3686):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5555): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5555): Disconnected process message: 10
,D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/jxcore-log(14012): Initializing JXcore engine
W/jxcore-log(14012): JXcore engine is ready
,E/auditd  ( 4613): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3496): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3496): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(14012): Starting JXcore engine
,W/jxcore-log(14012): Platform android
W/jxcore-log(14012): 
W/jxcore-log(14012): Process ARCH arm
W/jxcore-log(14012): 
,I/jxcore-log(14012): JXcore Cordova bridge is ready!
I/jxcore-log(14012): 
W/jxcore-log(14012): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions(14012): execute: REQUEST_ACCESS_COARSE_LOCATION
,V/AlarmManager( 3496): waitForAlarm result :8
,W/ContextImpl( 3496): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/io.jxcore.node.JXcoreExtension(14012): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log(14012): BLE multiple advertisement supported
I/jxcore-log(14012): 
,I/jxcore-log(14012): My device name is: samsung-SM-N910C
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log(14012): 
,I/jxcore-log(14012): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log(14012): 
,I/io.jxcore.node.ConnectivityInfo(14012): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo(14012):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo(14012):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo(14012):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo(14012):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo(14012):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo(14012):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo(14012):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo(14012):     - force notify: true
D/io.jxcore.node.JXcoreExtension(14012): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log(14012): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log(14012): 
I/jxcore-log(14012): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log(14012): 
,D/SSRM:n  ( 3496): SIOP:: AP = 320, PST = 352, CUR = 107
,D/PackageManager( 3496): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log(14012): 
,D/BatteryService( 3496): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3496): level:100, scale:100, status:5, health:2, present:true, voltage: 4359, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3496): online:4, current avg:-84, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-203
D/BatteryService( 3496): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3496): stay LED for fully charged
,I/MotionRecognitionService( 3496): Plugged
I/MotionRecognitionService( 3496): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3686): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3686): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3686):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5555): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5555): Disconnected process message: 10
,D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3686): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(14012): 
,I/jxcore-log(14012): Unit Test app is loaded
I/jxcore-log(14012): 
,I/jxcore-log(14012): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log(14012): 
,I/chromium(14012): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log(14012): --= Surplus to requirements =--
I/jxcore-log(14012): 
I/jxcore-log(14012): ****TEST TOOK:  ms ****
I/jxcore-log(14012): 
I/jxcore-log(14012): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(14012): 
,D/AndroidRuntime(14110): 
D/AndroidRuntime(14110): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(14110): CheckJNI is OFF
,D/AndroidRuntime(14110): readGMSProperty: start
D/AndroidRuntime(14110): readGMSProperty: already setted!!
D/AndroidRuntime(14110): readGMSProperty: end
D/AndroidRuntime(14110): addProductProperty: start
,E/AffinityControl(14110): AffinityControl: registerfunction enter
,D/AndroidRuntime(14110): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 3496): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3496): START PACKAGE DELETE: observer{586021050}
D/PackageManager( 3496): pkg{<packageName>}
D/PackageManager( 3496): user{0}
D/PackageManager( 3496): caller{2000}
D/PackageManager( 3496): flags{3}
D/PersonaManagerService( 3496): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3496): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3496): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3496): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3496): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3496): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3496): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3496): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3496): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 3496): !@killApplicatoin: 10670, uninstall pkg
I/ActivityManager( 3496): Force stopping com.test.thalitest appid=10670 user=-1: uninstall pkg
,I/ActivityManager( 3496): Killing 14012:com.test.thalitest/u0a670 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3496):   Force finishing activity ActivityRecord{1d39a38b u0 com.test.thalitest/.MainActivity t27}
,I/SurfaceFlinger( 2849): id=15 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=15 Removed NainActivit (-2/8)
,D/PointerIcon( 3496): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3496): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 3496): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3496): setHoveringSpenCustomIcon IconType is same.1
,D/WifiService( 3496): Client connection lost with reason: 4
,W/PackageSettings( 3496): Skipping PackageSetting{2ac167be com.example.hello/10656} due to missing metadata
,I/ActivityManager( 3496): Force stopping com.test.thalitest appid=10670 user=0: pkg removed
,I/art     (13503): Explicit concurrent mark sweep GC freed 235(22KB) AllocSpace objects, 0(0B) LOS objects, 19% free, 33MB/41MB, paused 997us total 30.963ms
,I/art     ( 8871): Explicit concurrent mark sweep GC freed 3226(157KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.047ms total 24.223ms
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/art     ( 4055): Explicit concurrent mark sweep GC freed 818(49KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 1.279ms total 34.205ms
I/art     ( 6604): Explicit concurrent mark sweep GC freed 825(34KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 31MB/39MB, paused 1.889ms total 57.108ms
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/InputReader( 3496): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 4502): mOCRHelper is null
,W/GeofencerStateMachine( 4638): Ignoring removeGeofence because network location is disabled.
,D/LocationWidgetApplication(13503): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3496): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3496): Admin package name: com.google.android.gms
,E/Zygote  (14141): MountEmulatedStorage()
E/Zygote  (14141): v2
I/libpersona(14141): KNOX_SDCARD checking this for 10063
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/libpersona(14141): KNOX_SDCARD not a persona
,I/SELinux (14141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
I/ActivityManager( 3496): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=14141 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (14141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (14141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourceType( 5179): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5179): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider(14141): TimaSignature is unavailable
,D/ActivityThread(14141): Added TimaKeyStore provider
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/art     ( 3496): Explicit concurrent mark sweep GC freed 33505(2MB) AllocSpace objects, 28(448KB) LOS objects, 22% free, 53MB/69MB, paused 2.057ms total 155.963ms
,I/art     ( 3496): WaitForGcToComplete blocked for 67.523ms for cause Explicit
D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(14141): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/VRSetupWizardStub/PackageIntentReceiver(14141): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(14141): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(14141): packagename:com.test.thalitest
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 3496): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3496): mCursor = null
,E/Zygote  (14158): MountEmulatedStorage()
E/Zygote  (14158): v2
I/libpersona(14158): KNOX_SDCARD checking this for 10021
I/libpersona(14158): KNOX_SDCARD not a persona
,I/SELinux (14158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3496): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=14158 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
E/SELinux (14158): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3496): Killing 12459:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/RegisteredServicesCache( 3961): empty dynamic service
,W/ResourceType( 3496): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/TimaKeyStoreProvider(14158): TimaSignature is unavailable
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ActivityThread(14158): Added TimaKeyStore provider
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager(14158): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,W/ResourcesManager( 3496): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3496): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/KLMS-2.4.521: (14158): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 04 12:58:11 GMT+01:00 2016
,I/art     ( 3496): Explicit concurrent mark sweep GC freed 8854(550KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 53MB/69MB, paused 2.289ms total 149.684ms
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(13503): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.4.521: (14158): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3496): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3496): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.4.521: (14158): KLMSIntentService(): onCreate()
D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/KLMS-2.4.521: (14158): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.521: (14158): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (14158): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/KLMS-2.4.521: (14158): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.4.521: (14158): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (14158): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  (14176): MountEmulatedStorage()
E/Zygote  (14176): v2
I/libpersona(14176): KNOX_SDCARD checking this for 10106
I/libpersona(14176): KNOX_SDCARD not a persona
,W/ResourcesManager(13503): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(13503): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(13503): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SELinux (14176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(13503): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/SELinux (14176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3496): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=14176 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
E/SELinux (14176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/RCPManager(13800):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3496):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 3496): queryAllProviders():  providerCallBack is not register for 0
D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(14176): TimaSignature is unavailable
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ActivityThread(14176): Added TimaKeyStore provider
,I/KLMS-2.4.521: (14158): KLMSIntentService(): listeningToPackageRemoved().END
,E/Zygote  (14192): MountEmulatedStorage()
E/Zygote  (14192): v2
I/libpersona(14192): KNOX_SDCARD checking this for 10183
I/libpersona(14192): KNOX_SDCARD not a persona
,I/SELinux (14192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3496): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=14192 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/SELinux (14192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (14192): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/KLMS-2.4.521: (14158): KLMSIntentService(): onDestroy()
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(14176): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  (14207): MountEmulatedStorage()
E/Zygote  (14207): v2
I/libpersona(14207): KNOX_SDCARD checking this for 10101
I/libpersona(14207): KNOX_SDCARD not a persona
,I/SELinux (14207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/ActivityManager( 3496): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=14207 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (14207): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(14192): TimaSignature is unavailable
,D/ActivityThread(14192): Added TimaKeyStore provider
,D/ResourcesManager(13503): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/elm:14491(14176): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14491(14176): ELMEngine.ELMEngine( context ).
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
D/elm:14491(14176): MDMBridge.setEnterpriseBridge()
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/TimaKeyStoreProvider(14207): TimaSignature is unavailable
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ActivityThread(14207): Added TimaKeyStore provider
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,E/Zygote  (14222): MountEmulatedStorage()
E/Zygote  (14222): v2
I/libpersona(14222): KNOX_SDCARD checking this for 10052
I/libpersona(14222): KNOX_SDCARD not a persona
,I/SELinux (14222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3496): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=14222 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (14222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/SELinux (14222): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/elm:14491(14176): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/PackageManager( 3496): delete codoeFile: 
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/AASAUninstall( 3496):  com.test.thalitest not target!
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/PackageManager( 3496): result of delete: 1{586021050}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/art     ( 2895): Explicit concurrent mark sweep GC freed 8733(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 885us total 26.048ms
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/AndroidRuntime(14110): Shutting down VM
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/elm:14491(14176): ElmAgentService : onCreate()
,D/elm:14491(14176): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/elm:14491(14176): MainReceiver.listeningToPackageRemoved()
D/elm:14491(14176): MDMBridge.getInstance()
D/elm:14491(14176): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(14176): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/art     ( 2895): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 817us total 15.027ms
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(14207): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,I/ActivityManager( 3496): Killing 12712:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/TimaKeyStoreProvider(14222): TimaSignature is unavailable
,D/ActivityThread(14222): Added TimaKeyStore provider
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Music2/Music2.apk
I/art     ( 2895): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.266ms total 15.953ms
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(14192): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(14222): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager(14222): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/ResourcesManager(14222): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(14222): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(14222): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(14222): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(14222): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager(13503): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  (14239): MountEmulatedStorage()
E/Zygote  (14239): v2
I/libpersona(14239): KNOX_SDCARD checking this for 10019
I/libpersona(14239): KNOX_SDCARD not a persona
,I/SELinux (14239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/Resources( 3496): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog(14192): (284) automatic index on shooting_modes(title_id)
,I/SELinux (14239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
E/SELinux (14239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3496): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=14239 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/elm:14491(14176): ElmAgentService : onDestroy().
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ActivityManager( 3496): Killing 12633:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,I/CrashAnrDetector( 3496): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 3496): clearDefaults: com.test.thalitest
,D/TimaKeyStoreProvider(14239): TimaSignature is unavailable
,D/ActivityThread(14239): Added TimaKeyStore provider
,I/TapandpayWidget:TanpandpayAppWidgetProvider(13294): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(13294): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,I/TapandpayWidget:Utils(13294): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(13294): Widget is not attached.
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager(14239): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3496): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/ActivityManager( 3496): Killing 12851:com.osp.app.signin/u0a45 (adj 13): bgCount ##31
,D/PackageBroadcastService( 6604): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6604): Clearing selected account for com.test.thalitest
D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(14239): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(14239): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(14239): onReceive() : package name is not s health. Return !!!
,D/RCPManagerService( 3496): PackageReceiver onReceive()
I/HarmonyEASService( 3496): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3496): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3496): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/JobSchedulerService( 3496): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3496): uID is 10670
V/EnterpriseBillingPolicy( 3496): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3496): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3496): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3496): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3496): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3496): getBillingProfileForVpnEngine - end - null
,D/DocsApplication(14207): Installing DEX configuration.
,I/LocationSettingsChecker( 6604): Removing dialog suppression flag for package com.test.thalitest
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/gH_CompatibleDatabase( 6604): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6604): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 6604): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6604): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 6604): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6604): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 6604): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/ResourcesManager(13503): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/gH_CompatibleDatabase( 6604): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6604): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/Mms/MmsApp(14222): [start]    onCreate() consume time = 0.0
D/gH_CompatibleDatabase( 6604): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/TaskPersister( 3496): removeObsoleteFile: deleting file=27_task.xml
D/gH_CompatibleDatabase( 6604): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 6604): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6604): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/DexInstaller(14207): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/Mms/ArtClassLoader(14222): init before art
,D/Mms/ArtClassLoader(14222): init [DONE] art
I/PackageInfoHelper(14207): Provided clientMode=RELEASE, packageInfo=PackageInfo{29e70a6c com.google.android.apps.docs}
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/LocationWidgetApplication(13503): getLastUiLocationId() : mLastUiLocationId = -100
,D/TAG     (14207): onCreate()
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/CrossAppStateProvider(14207): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/Mms/TelephonyPermission(14222): start operation mode monitor
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager(14222): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(14222): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 6604): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6604): Module APK com.google.android.play.games already loaded
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Zygote  (14262): MountEmulatedStorage()
E/Zygote  (14262): v2
I/libpersona(14262): KNOX_SDCARD checking this for 1000
I/libpersona(14262): KNOX_SDCARD not a persona
,I/SELinux (14262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (14262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3496): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=14262 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/SELinux (14262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3496): Killing 13312:com.samsung.android.sconnect/u0a150 (adj 13): bgCount ##31
,D/ChimeraCfgMgr( 6604): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 6604): Module APK com.google.android.play.games already loaded
,D/Mms/TelephonyPermission(14222): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(14222): isDefault true
,D/Mms/MmsApp(14222): onCreate() com.android.mms
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/NetworkScheduler.SchedulerReceiver( 4638): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4638): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/TimaKeyStoreProvider(14262): TimaSignature is unavailable
,D/ActivityThread(14262): Added TimaKeyStore provider
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/Mms/MmsApp(14222): [start]    initCountryIso consume time = 139.725833
,D/CountryDetector( 3496): The first listener is added
,D/Mms/MmsApp(14222): [end]    initCountryIso consume time = 9.887084
D/Mms/MmsConfig(14222): [start]    MmsConfig.init() consume time = 0.124
,D/ResourcesManager(13503): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/Icing   ( 6604): doRemovePackageData com.test.thalitest
,E/SQLiteLog( 6604): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6604): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/Mms/MmsConfig(14222): before partial update
,D/ResourcesManager(13503): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager(14262): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/ResourcesManager(13503): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,E/AndroidRuntime( 6604): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6604): Process: com.google.android.gms, PID: 6604
E/AndroidRuntime( 6604): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
E/AndroidRuntime( 6604): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
E/AndroidRuntime( 6604): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6604): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 6604): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6604): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6604): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6604): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6604): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6604): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ResourcesManager(13503): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/PCWCLIENTTRACE_LOG(14262): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(14262): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(14262): new DMDBOpenHelper instance
,E/SQLiteLog(14262): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,D/Mms/MmsConfig(14222): Load Resize quality : 80
,E/SQLiteDatabase(14262): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(14262): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(14262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(14262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(14262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(14262): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(14262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(14262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(14262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(14262): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(14262): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(14262): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(14262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(14262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(14262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(14262): Shutting down VM
,E/AndroidRuntime(14262): FATAL EXCEPTION: main
E/AndroidRuntime(14262): Process: com.sec.pcw.device, PID: 14262
E/AndroidRuntime(14262): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(14262): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(14262): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(14262): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(14262): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(14262): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(14262): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(14262): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(14262): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(14262): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(14262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(14262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(14262): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(14262): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(14262): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(14262): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(14262): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(14262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(14262): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(14262): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(14262): 	... 11 more
D/Mms/MmsConfig(14222):  enable multiwindow = true
V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
E/Mms/MessageUtils(14222): setCountryDetector : update country detector info 
E/Mms/MessageUtils(14222): updateCountryIso : update country iso info 
D/Mms/PackageInfo(14222): com.sec.imsservice is not installed
D/Mms/MmsConfig(14222): [end]    init() consume time = 78.784125
D/Mms/Contact(14222): [start]    init() consume time = 0.460291
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3496): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3496): displayNotification : [0ah,00h,00h]
W/FileUtils( 6604): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3496): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3496): displayNotification : [0ah,00h,01h]
E/DropBoxManagerService( 3496): Can't write: system_app_crash
E/DropBoxManagerService( 3496): java.io.FileNotFoundException: /data/system/dropbox/drop195.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3496): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3496): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3496): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3496): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3496): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3496): 	... 5 more
D/UsbHostManager( 3496): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3496): displayNotification : [09h,00h,00h]
E/Icing   ( 6604): Failed to open Apps corpus file.
D/Mms/Contact(14222): [end]    init consume time = 9.550417
D/TP/MmsSmsProvider( 3978): query,matched:13, calling pid = 14222
D/Mms/DraftCache(14222): [start]    rebuildCache consume time = 1.247
E/DropBoxManagerService( 3496): Can't write: system_app_crash
E/DropBoxManagerService( 3496): java.io.FileNotFoundException: /data/system/dropbox/drop194.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3496): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3496): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3496): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3496): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3496): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3496): 	... 5 more
D/TP/MmsSmsProvider( 3978): match 13:Elapsed time : 3.003 ms
D/TP/MmsSmsProvider( 3978): query,matched:12, calling pid = 14222
D/UsbHostManager( 3496): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3496): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3496): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
E/Icing   ( 6604): Failed to open Apps corpus file.
,D/Mms/TelephonyUtils(14222): getSubId from simSlot 0, return Value = -1
E/SharedPreferencesImpl( 6604): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
D/Mms/DownloadManager(14222): roaming -> false (slotId = 0)
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(14222): auto download without roaming -> true
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/TP/MmsSmsProvider( 3978): match 12:Elapsed time : 5.037 ms
E/Mms/TelephonyUtils(14222): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(14222): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(14222): roaming -> false (slotId = 1)
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(14222): auto download without roaming -> true
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(14222): auto download during roaming secondary -> false
D/Mms/DownloadManager(14222): mAutoDownload ------> true
I/Process ( 6604): Sending signal. PID: 6604 SIG: 9
D/MtpClient(13762): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(13762): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
D/Mms/Conversation(14222): [start]    init() consume time = 17.074375
D/Mms/MmsApp(14222): [end]    onCreate() consume time = 0.340333
D/Mms/FreeMessageStatusReceiver(14222): onReceive, action : android.intent.action.PACKAGE_REMOVED
E/lowmemorykiller( 2827): Error writing /proc/6604/oom_score_adj; errno=22
D/TP/MmsSmsProvider( 3978): deleteConversation threadId: 9223372036854775807
I/Process (14262): Sending signal. PID: 14262 SIG: 9
D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/Mms/DraftCache(14222): [end]    rebuildCache consume time = 14.788334
D/UsbHostManager( 3496): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3496): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
D/Mms/DownloadManager(14222): Service state changed: Bundle[mParcelledData.dataSize=692]
D/Mms/DownloadManager(14222): roaming ------> false, mSimSlot = 0
W/ResourcesManager(12492): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/Mms/TelephonyUtils(14222): getSubId from simSlot 0, return Value = -1
W/ResourcesManager(12492): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/Mms/DownloadManager(14222): roaming -> false (slotId = 0)
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(14222): auto download without roaming -> true
D/Mms/DownloadManager(14222): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(14222): mAutoDownload ------> true
,D/Mms/FreeMessageReceiverService(14222): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(14222): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 3496): enable value -1
I/TactileAssist( 3496): internal enable value -1
I/TactileAssist( 3496): intensity value -1
I/TactileAssist( 3496): saveAppList value true
,I/TactileAssist( 3496): List of disabled apps :
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(12492): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/EventHub( 3496): Removing device '/dev/input/event10' due to inotify event
,I/ActivityManager( 3496): Process com.sec.pcw.device (pid 14262)(adj 9) has died(471,927)
,E/SQLiteLog(12526): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog(12526): (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,E/SQLiteQuery(12526): exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,I/EventHub( 3496): Removing device '/dev/input/event7' due to inotify event
W/ResourcesManager(12492): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ConnectivityService( 3496): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1c9f128e)
,D/ConnectivityService( 3496): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager( 3496): Process com.google.android.gms (pid 6604)(adj 0) has died(471,928)
,I/EventHub( 3496): Removing device '/dev/input/event8' due to inotify event
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ConnectivityService( 3496): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ResourcesManager(12492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ActivityManager( 3496): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,W/ActivityManager( 3496): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
,W/ActivityManager( 3496): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,W/ActivityManager( 3496): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager( 3496): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 10999ms
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager(12492): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/AndroidRuntime(12526): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime(12526): Process: com.sec.android.app.shealth, PID: 12526
E/AndroidRuntime(12526): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
E/AndroidRuntime(12526): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
E/AndroidRuntime(12526): 	at android.content.ContentResolver.query(ContentResolver.java:503)
E/AndroidRuntime(12526): 	at android.content.ContentResolver.query(ContentResolver.java:428)
E/AndroidRuntime(12526): 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
E/AndroidRuntime(12526): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
E/AndroidRuntime(12526): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(12526): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12526): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(12526): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/ApplicationPolicy( 3496): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
,E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3496): Removing device '/dev/input/event9' due to inotify event
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager(12492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  (14307): MountEmulatedStorage()
E/Zygote  (14307): v2
I/libpersona(14307): KNOX_SDCARD checking this for 10039
I/libpersona(14307): KNOX_SDCARD not a persona
,D/ResourcesManager(12492): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux (14307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourcesManager(12492): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/EventHub( 3496): Removing device '/dev/input/event11' due to inotify event
I/ActivityManager( 3496): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=14307 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (14307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (14307): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/DropBoxManagerService( 3496): Can't write: system_app_crash
E/DropBoxManagerService( 3496): java.io.FileNotFoundException: /data/system/dropbox/drop196.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 3496): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 3496): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 3496): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 3496): 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15098)
E/DropBoxManagerService( 3496): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 3496): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 3496): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 3496): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 3496): 	... 5 more
,W/ResourcesManager(12492): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3496): checkUser: useridlist=null, currentuser=0
,I/EventHub( 3496): Removing device '/dev/input/event12' due to inotify event
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Zygote  (14320): MountEmulatedStorage()
,E/Zygote  (14320): v2
I/libpersona(14320): KNOX_SDCARD checking this for 10059
I/libpersona(14320): KNOX_SDCARD not a persona
,I/SELinux (14320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/EventHub( 3496): Removing device '/dev/input/event13' due to inotify event
,I/SELinux (14320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3496): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=14320 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,E/SELinux (14320): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/Process (12526): Sending signal. PID: 12526 SIG: 9
,D/TimaKeyStoreProvider(14307): TimaSignature is unavailable
,D/ActivityThread(14307): Added TimaKeyStore provider
,I/EventHub( 3496): Removing device '/dev/input/event14' due to inotify event
W/ResourcesManager(12492): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(12492): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/TimaKeyStoreProvider(14320): TimaSignature is unavailable
,D/ActivityThread(14320): Added TimaKeyStore provider
,D/ResourcesManager(14307): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager(12492): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager(14320): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager(12492): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(12492): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager(14320): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/ActivityManager( 3496): Process com.sec.android.app.shealth (pid 12526)(adj 5) has died(485,928)
,W/ActivityManager( 3496): Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 20726ms

```
