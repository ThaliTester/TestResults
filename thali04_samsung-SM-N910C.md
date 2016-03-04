#### Test 614329799926788_thali04_samsung-SM-N910C Logs


```
--------- beginning of system,
D/SSRM:n  ( 3525): SIOP:: AP = 260, PST = 264, CUR = 31
I/PowerManagerService( 3525): [PWL] Off : 140s ago
--------- beginning of main
D/AndroidRuntime(11602): 
D/AndroidRuntime(11602): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11602): CheckJNI is OFF
D/AndroidRuntime(11602): readGMSProperty: start
D/AndroidRuntime(11602): readGMSProperty: already setted!!
D/AndroidRuntime(11602): readGMSProperty: end
D/AndroidRuntime(11602): addProductProperty: start
E/AffinityControl(11602): AffinityControl: registerfunction enter
D/AndroidRuntime(11602): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 3525): inState():  stateMachine is null !!
I/PersonaManagerService( 3525): PersonaId don't exist
I/ActivityManager( 3525): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 3525): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager( 3525): mDVFSHelper.acquire()
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/Zygote  (11620): MountEmulatedStorage()
E/Zygote  (11620): v2
I/libpersona(11620): KNOX_SDCARD checking this for 10668
I/libpersona(11620): KNOX_SDCARD not a persona
I/SELinux (11620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=11620 uid=10668 gids={50668, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
E/SELinux (11620): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/AndroidRuntime(11602): Shutting down VM
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
D/TimaKeyStoreProvider(11620): TimaSignature is unavailable
D/ActivityThread(11620): Added TimaKeyStore provider
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger( 2849): id=11 Removed YUIInstallC (-2/8)
D/ResourcesManager(11620): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 6166): updateVisibility : ActivityRecord{1dae4711 token=android.os.BinderProxy@1be1662a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory(11620): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager(11620): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader(11620): Loading: webviewchromium
,I/LibraryLoader(11620): Time to load native libraries: 6 ms (timestamps 4943-4949)
,I/LibraryLoader(11620): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider(11620): Binding Chromium to main looper Looper (main, tid 1) {1f5e1186}
,I/LibraryLoader(11620): Expected native library version number "",actual native library version number ""
,I/chromium(11620): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController(11620): Initializing chromium process, renderers=0
,W/art     (11620): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium(11620): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium(11620): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium(11620): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/chromium(11620): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium(11620): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     (11620): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents(11620): onDetachedFromWindow called when already detached. Ignoring
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3525): stay LED for fully charged
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5554): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5554): Disconnected process message: 10
,D/SystemWebViewEngine(11620): CordovaWebView is running on device made by: samsung
,W/art     (11620): Attempt to remove local handle scope entry from IRT, ignoring
W/art     (11620): Attempt to remove local handle scope entry from IRT, ignoring
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Activity(11620): performCreate Call secproduct feature valuefalse
D/Activity(11620): performCreate Call debug elastic valuetrue
,D/OpenGLRenderer(11620): Render dirty regions requested: true
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
,D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,W/ActivityManager( 3525): Activity pause timeout for ActivityRecord{2bbbfe53 u0 com.test.thalitest/.MainActivity t26}
,I/SurfaceFlinger( 2849): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer(11620): Initialized EGL, version 1.4
,I/OpenGLRenderer(11620): HWUI protection enabled for context ,  &this =0xaf645060 ,&mEglDisplay = 1 , &mEglConfig = -1277796080 
,D/OpenGLRenderer(11620): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 8192
D/OpenGLRenderer(11620): Enabling debug mode 0
,D/mali_winsys(11620): new_window_surface returns 0x3000,  [1440x2560]-format:1
,V/ActivityThread(11620): updateVisibility : ActivityRecord{177cfe0d token=android.os.BinderProxy@13f2f3dc {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{2bbbfe53 u0 com.test.thalitest/.MainActivity t26} time:235383
,W/IInputConnectionWrapper(11620): showStatusIcon on inactive InputConnection
,I/Timeline(11620): Timeline: Activity_idle id: android.os.BinderProxy@13f2f3dc time:235396
,I/chromium(11620): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium(11620): 
,D/JsMessageQueue(11620): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log(11620): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357426176
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2af72 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings(11620): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@142beb79 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel(11620): addListener: New listener added - the number of listeners is now 1
,D/WifiService( 3525): New client listening to asynchronous messages
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager(11620): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings(11620): setScanMode: 1 -> 2
,I/chromium(11620): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log(11620): Initializing JXcore engine
W/jxcore-log(11620): JXcore engine is ready
,E/auditd  ( 4608): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService( 3525): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService( 3525): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,W/jxcore-log(11620): Starting JXcore engine
,W/jxcore-log(11620): Platform android
W/jxcore-log(11620): 
W/jxcore-log(11620): Process ARCH arm
W/jxcore-log(11620): 
,I/jxcore-log(11620): JXcore Cordova bridge is ready!
I/jxcore-log(11620): 
W/jxcore-log(11620): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions(11620): execute: REQUEST_ACCESS_COARSE_LOCATION
,V/io.jxcore.node.JXcoreExtension(11620): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log(11620): BLE multiple advertisement supported
I/jxcore-log(11620): 
,I/jxcore-log(11620): My device name is: samsung-SM-N910C
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log(11620): 
,I/jxcore-log(11620): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log(11620): 
,I/io.jxcore.node.ConnectivityInfo(11620): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo(11620):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo(11620):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo(11620):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo(11620):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo(11620):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo(11620):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo(11620):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo(11620):     - force notify: true
D/io.jxcore.node.JXcoreExtension(11620): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log(11620): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log(11620): 
,I/jxcore-log(11620): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log(11620): 
,D/SSRM:n  ( 3525): SIOP:: AP = 290, PST = 264, CUR = 32
,D/PackageManager( 3525): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/BatteryService( 3525): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3525): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3525): online:4, current avg:-101, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-221
D/BatteryService( 3525): stay LED for fully charged
D/BatteryService( 3525): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3525): Plugged
I/MotionRecognitionService( 3525): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3691): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3691): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3691):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5554): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5554): Disconnected process message: 10
,D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3691): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log(11620): 
,W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log(11620): 
,I/jxcore-log(11620): Unit Test app is loaded
I/jxcore-log(11620): 
,I/jxcore-log(11620): INFO thaliMobileNativeWrapper networkChanged: {"blueToothLowEnergy":"on","blueTooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log(11620): 
,I/chromium(11620): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,I/jxcore-log(11620): --= Surplus to requirements =--
I/jxcore-log(11620): 
,I/jxcore-log(11620): ****TEST TOOK:  ms ****
I/jxcore-log(11620): 
,I/jxcore-log(11620): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log(11620): 
,D/AndroidRuntime(11725): 
D/AndroidRuntime(11725): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime(11725): CheckJNI is OFF
,D/AndroidRuntime(11725): readGMSProperty: start
D/AndroidRuntime(11725): readGMSProperty: already setted!!
,D/AndroidRuntime(11725): readGMSProperty: end
D/AndroidRuntime(11725): addProductProperty: start
,E/AffinityControl(11725): AffinityControl: registerfunction enter
,D/AndroidRuntime(11725): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 3525): START PACKAGE DELETE: observer{735049122}
D/PackageManager( 3525): pkg{<packageName>}
D/PackageManager( 3525): user{0}
D/PackageManager( 3525): caller{2000}
D/PackageManager( 3525): flags{3}
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 3525): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3525): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 3525): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3525): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3525): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 3525): !@killApplicatoin: 10668, uninstall pkg
I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10668 user=-1: uninstall pkg
I/ActivityManager( 3525): Killing 11620:com.test.thalitest/u0a668 (adj 0): stop com.test.thalitest
,I/ActivityManager( 3525):   Force finishing activity ActivityRecord{2bbbfe53 u0 com.test.thalitest/.MainActivity t26}
,W/ActivityManager( 3525): mDVFSHelper.acquire()
,W/PackageSettings( 3525): Skipping PackageSetting{ab94b6b com.example.hello/10656} due to missing metadata
,I/ActivityManager( 3525): Force stopping com.test.thalitest appid=10668 user=0: pkg removed
,E/JavaBinder( 3525): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager( 3525):   Force finishing activity ActivityRecord{2bbbfe53 u0 com.test.thalitest/.MainActivity t26 f}
D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
W/ActivityManager( 3525): Duplicate finish request for ActivityRecord{2bbbfe53 u0 com.test.thalitest/.MainActivity t26 f}
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
,D/WifiService( 3525): Client connection lost with reason: 4
,I/WindowState( 3525): WIN DEATH: Window{e6e6731 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (5/8)
,I/SurfaceFlinger( 2849): id=14 Removed NainActivit (-2/8)
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 8800): Explicit concurrent mark sweep GC freed 24133(1417KB) AllocSpace objects, 7(112KB) LOS objects, 37% free, 26MB/42MB, paused 1.535ms total 41.087ms
,E/SamsungIME( 4495): mOCRHelper is null
I/InputReader( 3525): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4052): Explicit concurrent mark sweep GC freed 30591(1891KB) AllocSpace objects, 0(0B) LOS objects, 21% free, 28MB/36MB, paused 15.752ms total 87.215ms
,W/GeofencerStateMachine( 4652): Ignoring removeGeofence because network location is disabled.
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/art     ( 4811): Explicit concurrent mark sweep GC freed 23131(1352KB) AllocSpace objects, 3(48KB) LOS objects, 20% free, 31MB/39MB, paused 1.132ms total 102.456ms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,E/Zygote  (11743): MountEmulatedStorage()
,E/Zygote  (11743): v2
I/libpersona(11743): KNOX_SDCARD checking this for 10063
I/libpersona(11743): KNOX_SDCARD not a persona
,I/ActivityManager( 3525): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11743 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux (11743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 6166): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,I/SELinux (11743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11743): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/talkback/talkback.apk
,W/ResourceType( 5181): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5181): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/EnterpriseDeviceManagerService( 3525): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3525): Admin package name: com.google.android.gms
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 16
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/TimaKeyStoreProvider(11743): TimaSignature is unavailable
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ActivityThread(11743): Added TimaKeyStore provider
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6166): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 16
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ResourcesManager(11743): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/DBG_DM  ( 6166): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 52537(3MB) AllocSpace objects, 53(848KB) LOS objects, 24% free, 49MB/65MB, paused 2.174ms total 178.251ms
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/art     ( 3525): WaitForGcToComplete blocked for 178.636ms for cause Explicit
,D/VRSetupWizardStub/PackageIntentReceiver(11743): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(11743): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11743): packagename:com.test.thalitest
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/SecContentProvider2( 3525): uri = 14 selection = getSealedState
D/SecContentProvider2( 3525): mCursor = null
,D/ApplicationPolicy( 3525): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/Zygote  (11759): MountEmulatedStorage()
E/Zygote  (11759): v2
I/libpersona(11759): KNOX_SDCARD checking this for 10021
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
I/libpersona(11759): KNOX_SDCARD not a persona
I/SELinux (11759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 16
,I/SELinux (11759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/SELinux (11759): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/ActivityManager( 3525): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11759 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 3525): Killing 10827:com.sec.pcw.device/1000 (adj 13): bgCount ##31
I/DBG_DM  ( 6166): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 6166): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 6166): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 6166): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
I/DBG_DM  ( 6166): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3525): post active user change for 0
D/KnoxTimeoutHandler( 3525): postActiveUserChange for user 0
,I/DBG_DM  ( 6166): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,I/SurfaceFlinger( 2849): id=15 createSurf (1440x2560),2 flag=404, YUIInstallC
,D/StatusBarManagerService( 3525): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8734(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 918us total 24.675ms
,D/SecContentProvider2( 3525): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3525): mCursor = null
,D/PointerIcon( 3525): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3525): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3525): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3525): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 6166): updateVisibility : ActivityRecord{1dae4711 token=android.os.BinderProxy@1be1662a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 890us total 20.347ms
,D/TimaKeyStoreProvider(11759): TimaSignature is unavailable
,D/ActivityThread(11759): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 415us total 12.532ms
,D/InputMethodManagerService( 3525): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ResourceType( 3525): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(11759): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/InputMethodManagerService( 3525): Got RemoteException sending setActive(false) notification to pid 11620 uid 10668
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
W/ContextImpl( 3525): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/RegisteredServicesCache( 3962): empty dynamic service
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,I/Timeline( 6166): Timeline: Activity_idle id: android.os.BinderProxy@1be1662a time:249068
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/ActivityManager( 3525): mDVFSHelper.release()
I/Timeline( 3525): Timeline: Activity_windows_visible id: ActivityRecord{2f1e7f8 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t24} time:249075
,I/KLMS-2.4.521: (11759): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 04 08:43:32 GMT+01:00 2016
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/ResourcesManager( 3525): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3525): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
I/KLMS-2.4.521: (11759): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 3525): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3525): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.facebook.katana-1/base.apk
,I/KLMS-2.4.521: (11759): KLMSIntentService(): onCreate()
,I/KLMS-2.4.521: (11759): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/KLMS-2.4.521: (11759): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.4.521: (11759): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  (11777): MountEmulatedStorage()
E/Zygote  (11777): v2
I/libpersona(11777): KNOX_SDCARD checking this for 10106
I/libpersona(11777): KNOX_SDCARD not a persona
,I/KLMS-2.4.521: (11759): KLMSIntentService(): PACKAGE_REMOVED
,I/SELinux (11777): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11777): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11777): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11777 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.4.521: (11759): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.4.521: (11759): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/art     ( 3525): Explicit concurrent mark sweep GC freed 8297(474KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 3.182ms total 183.517ms
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11777): TimaSignature is unavailable
,D/ActivityThread(11777): Added TimaKeyStore provider
,E/Zygote  (11792): MountEmulatedStorage()
E/Zygote  (11792): v2
I/libpersona(11792): KNOX_SDCARD checking this for 1000
I/libpersona(11792): KNOX_SDCARD not a persona
,I/SELinux (11792): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11792): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11792 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11792): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11792): TimaSignature is unavailable
,D/ActivityThread(11792): Added TimaKeyStore provider
I/KLMS-2.4.521: (11759): KLMSIntentService(): listeningToPackageRemoved().END
,D/ResourcesManager(11777): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,E/Zygote  (11807): MountEmulatedStorage()
I/libpersona(11807): KNOX_SDCARD checking this for 10050
E/Zygote  (11807): v2
I/libpersona(11807): KNOX_SDCARD not a persona
,I/SELinux (11807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=11807 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,E/SELinux (11807): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.4.521: (11759): KLMSIntentService(): onDestroy()
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/elm:14491(11777): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/ResourcesManager(11792): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/elm:14491(11777): ELMEngine.ELMEngine( context ).
,D/elm:14491(11777): MDMBridge.setEnterpriseBridge()
,D/TimaKeyStoreProvider(11807): TimaSignature is unavailable
,D/ActivityThread(11807): Added TimaKeyStore provider
,W/ResourcesManager(11792): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:14491(11777): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/elm:14491(11777): ElmAgentService : onCreate()
D/elm:14491(11777): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14491(11777): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11777): MDMBridge.getInstance()
D/elm:14491(11777): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14491(11777): MDMBridge.getAllLicenseInfoFromSDK()
,I/TapandpayWidget:TanpandpayAppWidgetProvider(11342): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(11342): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(11342): Clear T&P info.
,D/ResourcesManager(11807): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/TapandpayWidget:TanpandpayAppWidgetProvider(11342): Widget is not attached.
,D/RCPManager(11792):  in createShortcut() for packageName: com.test.thalitest userId0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3525):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3525): queryAllProviders():  providerCallBack is not register for 0
,W/ResourcesManager(11807): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(11807): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(11807): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager(11807): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11807): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager(11807): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(11807): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(11807): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/Zygote  (11825): MountEmulatedStorage()
I/libpersona(11825): KNOX_SDCARD checking this for 10019
E/Zygote  (11825): v2
I/libpersona(11825): KNOX_SDCARD not a persona
I/SELinux (11825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=11825 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,D/PackageManager( 3525): delete codoeFile: 
,D/elm:14491(11777): ElmAgentService : onDestroy().
E/SELinux (11825): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AASAUninstall( 3525):  com.test.thalitest not target!
,D/PackageManager( 3525): result of delete: 1{735049122}
,D/AndroidRuntime(11725): Shutting down VM
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/ActivityManager( 3525): Killing 10162:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): bgCount ##31
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/TimaKeyStoreProvider(11825): TimaSignature is unavailable
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityThread(11825): Added TimaKeyStore provider
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/PackageBroadcastService( 4811): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4811): Clearing selected account for com.test.thalitest
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Books/Books.apk
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources( 3525): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 3525): Killing 9729:com.sec.android.app.shealth/u0a36 (adj 15): bgCount ##31
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(11825): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/UsbSettingsManager( 3525): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3525): onPackageRemoved : com.test.thalitest
I/LocationSettingsChecker( 4811): Removing dialog suppression flag for package com.test.thalitest
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/gH_CompatibleDatabase( 4811): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/gH_CompatibleDatabase( 4811): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,W/ContextImpl(11119): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/gH_MetricsDatabase( 4811): 0 metrics were deleted when clearing package com.test.thalitest.
D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/gH_CompatibleDatabase( 4811): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3525): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/com.sec.android.service.health.upgrade.UninstallReceiver(11825): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11825): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11825): onReceive() : package name is not s health. Return !!!
,D/gH_CompatibleDatabase( 4811): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4811): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 4811): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/RCPManagerService( 3525): PackageReceiver onReceive()
I/HarmonyEASService( 3525): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 3525): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 3525): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3525): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3525): uID is 10668
V/EnterpriseBillingPolicy( 3525): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - enter
D/gH_CompatibleDatabase( 4811): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4811): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,V/EnterpriseBillingPolicyStorage( 3525): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3525): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - start - com.test.thalitest
D/gH_CompatibleDatabase( 4811): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
V/EnterpriseBillingPolicyStorage( 3525): getBillingProfileForVpnEngine - end - null
,D/gH_CompatibleDatabase( 4811): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
,D/gH_CompatibleDatabase( 4811): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4811): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3525): findPreferredActivity: No PreferredActivities set
,E/Zygote  (11848): MountEmulatedStorage()
,E/Zygote  (11848): v2
I/libpersona(11848): KNOX_SDCARD checking this for 10116
I/libpersona(11848): KNOX_SDCARD not a persona
,I/SELinux (11848): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11848): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3525): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=11848 uid=10116 gids={50116, 9997, 1023} abi=armeabi-v7a
,E/SELinux (11848): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ChimeraCfgMgr( 4811): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4811): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4811): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4811): Module APK com.google.android.play.games already loaded
,D/KnoxTimeoutHandler( 3525): handleActiveUserChange for user 0
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11848): TimaSignature is unavailable
,D/ActivityThread(11848): Added TimaKeyStore provider
,E/Zygote  (11866): MountEmulatedStorage()
E/Zygote  (11866): v2
I/libpersona(11866): KNOX_SDCARD checking this for 10022
I/libpersona(11866): KNOX_SDCARD not a persona
,I/SELinux (11866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3525): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=11866 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
I/SELinux (11866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Killing 10844:com.sec.android.app.soundalive/u0a59 (adj 15): bgCount ##31
E/lowmemorykiller( 2827): Error writing /proc/10844/oom_score_adj; errno=22
,D/StatusBar( 3691): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/TaskPersister( 3525): removeObsoleteFile: deleting file=26_task.xml
D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/PersonaManager( 3691): isKioskContainerExistOnDevice
D/TaskPersister( 3525): removeObsoleteFile: deleting file=24_task.xml
I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
D/PanelView( 3691): There is/are notification(s) 
,D/PanelView( 3691): There is/are notification(s) 
,D/PersonaManager( 3691): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3691): Icon Only
I/StatusBar( 3691): Icon Only
,D/PanelView( 3691): There is/are notification(s) 
,D/TimaKeyStoreProvider(11866): TimaSignature is unavailable
,D/ActivityThread(11866): Added TimaKeyStore provider
,D/ResourcesManager(11848): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,D/NearbySource(11807): Nearby Source Create!
D/NearbyContext(11807): Nearby Context Create!
,I/Icing   ( 4811): doRemovePackageData com.test.thalitest
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(11807): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource(11807): Samsung link source created
,D/ResourcesManager(11866): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(11866): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/PanelView( 3691): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/ResourcesManager(11866): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(11866): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/NetworkScheduler.SchedulerReceiver( 4652): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 4652): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog(11848): (28) failed to open "/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db" with flag (131138) and mode_t (0) due to error (30)
,I/LocationWidgetApplication(11866): onCreate() : start
,D/LocationWidgetApplication(11866): countryCode = POLAND
E/SQLiteDatabase(11848): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase(11848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase(11848): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase(11848): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteDatabase(11848): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteDatabase(11848): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase(11848): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper(11848): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper(11848): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper(11848): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteOpenHelper(11848): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper(11848): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper(11848): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper(11848): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/SQLiteOpenHelper(11848): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/SQLiteOpenHelper(11848): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper(11848): 	at android.os.Binder.execTransact(Binder.java:446)
E/Zygote  (11888): MountEmulatedStorage()
I/libpersona(11888): KNOX_SDCARD checking this for 1000
E/Zygote  (11888): v2
I/libpersona(11888): KNOX_SDCARD not a persona
,I/SELinux (11888): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/SQLiteOpenHelper(11848): Opened filter.db in read-only mode
I/SELinux (11888): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SQLiteLog(11848): (284) automatic index on titles(filter_id)
I/ActivityManager( 3525): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=11888 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11888): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ContactProvider(11807): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3525): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3525): displayNotification : [02h,02h,01h]
,D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3525): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3525): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3525): displayNotification : [0ah,00h,01h]
,D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/003
,E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
D/UsbSettingsManager( 3525): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11888): TimaSignature is unavailable
,D/LocationManagerService( 3525): getProviders()=[]
D/LocationManagerService( 3525): getProviders()=[passive]
D/LocationManagerService( 3525): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
D/LWLocationManager(11866): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(11866): getLastUiLocationId() : mLastUiLocationId = -100
,E/SQLiteLog(11866): (28) failed to open "/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db" with flag (131138) and mode_t (0) due to error (30)
D/ActivityThread(11888): Added TimaKeyStore provider
,E/Zygote  (11911): MountEmulatedStorage()
E/Zygote  (11911): v2
I/libpersona(11911): KNOX_SDCARD checking this for 10052
I/libpersona(11911): KNOX_SDCARD not a persona
,I/SELinux (11911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,E/SQLiteDatabase(11866): Failed to open database '/data/data/com.sec.android.widgetapp.locationwidget/databases/LBHWidget.db'.
E/SQLiteDatabase(11866): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11866): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/SQLiteDatabase(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/SQLiteDatabase(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/SQLiteDatabase(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/SQLiteDatabase(11866): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/SQLiteDatabase(11866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/SQLiteDatabase(11866): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/SQLiteDatabase(11866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/SQLiteDatabase(11866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11866): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11866): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11866): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11866): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime(11866): Shutting down VM
,E/AndroidRuntime(11866): FATAL EXCEPTION: main
E/AndroidRuntime(11866): Process: com.sec.android.widgetapp.locationwidget, PID: 11866
E/AndroidRuntime(11866): java.lang.RuntimeException: Unable to start receiver com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3001)
E/AndroidRuntime(11866): 	at android.app.ActivityThread.access$1800(ActivityThread.java:178)
E/AndroidRuntime(11866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1526)
E/AndroidRuntime(11866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11866): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11866): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(11866): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(11866): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(11866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(11866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(11866): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11866): 	at com.sec.android.widgetapp.locationwidget.db.LocationWidgetDBControll.<init>(LocationWidgetDBControll.java:52)
E/AndroidRuntime(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getDBList(LocationWidgetFuctionData.java:690)
E/AndroidRuntime(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.configPlaceListItems(LocationWidgetFuctionData.java:548)
E/AndroidRuntime(11866): 	at com.sec.android.widgetapp.locationwidget.data.LocationWidgetFuctionData.getPlaceListItems(LocationWidgetFuctionData.java:55)
E/AndroidRuntime(11866): 	at com.sec.android.widgetapp.locationwidget.cocktail.LocationWidgetCocktailProvider.onReceive(LocationWidgetCocktailProvider.java:277)
E/AndroidRuntime(11866): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2994)
E/AndroidRuntime(11866): 	... 9 more
I/SELinux (11911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3525): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=11911 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux (11911): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/UsbHostManager( 3525): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3525): displayNotification : [09h,00h,00h]
D/MtpClient(11807): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(11807): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
D/UsbHostManager( 3525): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3525): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SharedPreferencesImpl(11807): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/EventHub( 3525): Removing device '/dev/input/event10' due to inotify event
D/ResourcesManager(11888): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.locationwidget
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(11911): TimaSignature is unavailable
,D/ActivityThread(11911): Added TimaKeyStore provider
,W/ContextImpl(11888): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2994 
,I/EventHub( 3525): Removing device '/dev/input/event7' due to inotify event
,E/Zygote  (11927): MountEmulatedStorage()
E/Zygote  (11927): v2
I/libpersona(11927): KNOX_SDCARD checking this for 1000
I/libpersona(11927): KNOX_SDCARD not a persona
,I/SELinux (11927): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11927): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11927): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11927 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/EventHub( 3525): Removing device '/dev/input/event8' due to inotify event
,I/EventHub( 3525): Removing device '/dev/input/event9' due to inotify event
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop192.tmp: open failed: EROFS (Read-only file system)
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
,D/ResourcesManager(11911): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/EventHub( 3525): Removing device '/dev/input/event11' due to inotify event
,E/SQLiteLog(11888): (28) failed to open "/data/data/com.android.keychain/databases/grants.db" with flag (131138) and mode_t (0) due to error (30)
,W/ResourcesManager(11911): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/SQLiteDatabase(11888): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase(11888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11888): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/SQLiteDatabase(11888): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/SQLiteDatabase(11888): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase(11888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11888): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider(11927): TimaSignature is unavailable
W/ResourcesManager(11911): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ActivityThread(11927): Added TimaKeyStore provider
W/ResourcesManager(11911): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(11911): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(11911): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(11911): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/AndroidRuntime(11888): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime(11888): Process: com.android.keychain, PID: 11888
E/AndroidRuntime(11888): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11888): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11888): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11888): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11888): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:560)
E/AndroidRuntime(11888): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:554)
E/AndroidRuntime(11888): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime(11888): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11888): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11888): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/EventHub( 3525): Removing device '/dev/input/event12' due to inotify event
,I/EventHub( 3525): Removing device '/dev/input/event13' due to inotify event
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.android.keychain
,I/EventHub( 3525): Removing device '/dev/input/event14' due to inotify event
,I/ActivityManager( 3525): Killing 10860:com.policydm/1000 (adj 15): bgCount ##31
,D/ResourcesManager(11927): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3525): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_LOG(11927): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG(11927): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11927): new DMDBOpenHelper instance
,E/SQLiteLog(11927): (28) failed to open "/data/data/com.sec.pcw.device/databases/value.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase(11927): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(11927): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase(11927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/SQLiteDatabase(11927): 	,at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase(11927): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase(11927): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/SQLiteDatabase(11927): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/SQLiteDatabase(11927): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/SQLiteDatabase(11927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11927): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase(11927): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/SQLiteDatabase(11927): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase(11927): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase(11927): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase(11927): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/AndroidRuntime(11927): Shutting down VM
E/AndroidRuntime(11927): FATAL EXCEPTION: main
E/AndroidRuntime(11927): Process: com.sec.pcw.device, PID: 11927
E/AndroidRuntime(11927): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11927): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5564)
E/AndroidRuntime(11927): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5156)
E/AndroidRuntime(11927): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5096)
E/AndroidRuntime(11927): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
E/AndroidRuntime(11927): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
E/AndroidRuntime(11927): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11927): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime(11927): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/AndroidRuntime(11927): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime(11927): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime(11927): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime(11927): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime(11927): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
,E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime(11927): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1520)
E/AndroidRuntime(11927): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime(11927): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime(11927): 	at com.sec.pcw.device.contentprovider.DMProvider.onCreate(DMProvider.java:32)
E/AndroidRuntime(11927): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
E/AndroidRuntime(11927): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1692)
E/AndroidRuntime(11927): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5561)
E/AndroidRuntime(11927): 	... 11 more
,E/Zygote  (11946): MountEmulatedStorage()
,E/Zygote  (11946): v2
,I/libpersona(11946): KNOX_SDCARD checking this for 1000
I/libpersona(11946): KNOX_SDCARD not a persona
I/SELinux (11946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (11946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (11946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3525): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=11946 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/Process (11866): Sending signal. PID: 11866 SIG: 9
,I/ActivityManager( 3525): Killing 10883:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##31
,E/DropBoxManagerService( 3525): Can't write: system_app_crash
E/DropBoxManagerService( 3525): java.io.FileNotFoundException: /data/system/dropbox/drop193.tmp: open failed: EROFS (Read-only file system)
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
,V/ApplicationPolicy( 3525): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device

```
