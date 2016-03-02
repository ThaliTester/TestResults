#### Test 613623660556c10_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
I/ServiceManager(  362): Waiting for service AtCmdFwd...
D/AndroidRuntime( 6524): 
D/AndroidRuntime( 6524): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6524): CheckJNI is OFF
D/AndroidRuntime( 6524): readGMSProperty: start
D/AndroidRuntime( 6524): readGMSProperty: already setted!!
D/AndroidRuntime( 6524): readGMSProperty: end
D/AndroidRuntime( 6524): addProductProperty: start
E/AffinityControl( 6524): AffinityControl: registerfunction enter
D/AndroidRuntime( 6524): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  765): inState():  stateMachine is null !!
I/PersonaManagerService(  765): PersonaId don't exist
I/ActivityManager(  765): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  765): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  765): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  765): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  765): mDVFSHelper.acquire()
D/FocusedStackFrame(  765): Set to : 0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  765): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6539 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  765): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  765): setMouseCustomIcon IconType is same.101
D/PointerIcon(  765): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  765): setHoveringSpenCustomIcon IconType is same.1
E/Zygote  ( 6539): MountEmulatedStorage()
D/AndroidRuntime( 6524): Shutting down VM
E/Zygote  ( 6539): v2
I/libpersona( 6539): KNOX_SDCARD checking this for 10079
I/libpersona( 6539): KNOX_SDCARD not a persona
I/SELinux ( 6539): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6539): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6539): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6539): TimaSignature is unavailable
D/ActivityThread( 6539): Added TimaKeyStore provider
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  765): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/SurfaceWidgetView( 1441): destroyHardwareResources():34057252
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SurfaceFlinger(  266): id=8 Removed Mauncher (6/8)
I/SurfaceFlinger(  266): id=8 Removed Mauncher (-2/8)
D/ResourcesManager( 6539): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1772): [237392/8] Surface widget visibility changed visibility = false on instance = 1
V/ActivityThread( 1441): updateVisibility : ActivityRecord{2b5b599 token=android.os.BinderProxy@3670b7ef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1441): onTrimMemory. Level: 20
,I/WebViewFactory( 6539): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
D/ResourcesManager( 6539): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 6539): Time to load native libraries: 4 ms (timestamps 5090-5094)
I/LibraryLoader( 6539): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6539): Binding Chromium to main looper Looper (main, tid 1) {19277fde}
I/LibraryLoader( 6539): Expected native library version number "",actual native library version number ""
I/chromium( 6539): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6539): Initializing chromium process, singleProcess=true
W/art     ( 6539): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6539): ApplicationContext is null in ApplicationStatus
W/chromium( 6539): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/chromium( 6539): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 6539): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
I/chromium( 6539): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
I/Adreno-EGL( 6539): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6539): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6539): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6539): Local Branch: mybranch5813579
I/Adreno-EGL( 6539): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6539): Local Patches: NONE
I/Adreno-EGL( 6539): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
D/BluetoothAdapter( 6539): 1034402794: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  765): Activity pause timeout for ActivityRecord{2255cef2 u0 com.test.thalitest/.MainActivity t9}
W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 3
W/chromium( 6539): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
W/art     ( 6539): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6539): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6539): CordovaWebView is running on device made by: samsung
W/art     ( 6539): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6539): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 6539): performCreate Call secproduct feature valuefalse
D/Activity( 6539): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 6539): Render dirty regions requested: true
D/ActivityManager(  765): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler(  765): postActiveUserChange for user 0
I/KnoxTimeoutHandler(  765): postActiveUserChange, showWhenLocked: false
D/PersonaManagerService(  765): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler(  765): handleActiveUserChange for user 0
V/ActivityThread( 6539): updateVisibility : ActivityRecord{17fd7bc1 token=android.os.BinderProxy@3c82d4cb {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  266): id=11 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  765): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  765): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  765): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  765): setMouseCustomIcon IconType is same.101
D/PointerIcon(  765): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  765): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 6539): Initialized EGL, version 1.4
I/OpenGLRenderer( 6539): HWUI protection enabled for context ,  &this =0xa074b060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 6539): Enabling debug mode 0
D/InputMethodManagerService(  765): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/SamsungIME( 1686): getCurrentCandidateView
I/Timeline(  765): Timeline: Activity_windows_visible id: ActivityRecord{2255cef2 u0 com.test.thalitest/.MainActivity t9} time:255789
W/ActivityManager(  765): mDVFSHelper.release()
W/IInputConnectionWrapper( 6539): showStatusIcon on inactive InputConnection
I/Timeline( 6539): Timeline: Activity_idle id: android.os.BinderProxy@3c82d4cb time:255808
W/BindingManager( 6539): Cannot call determinedVisibility() - never saw a connection for the pid: 6539
D/SamsungIME( 1686): Dismiss ExpandCandiate
I/SamsungIME( 1686): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6539): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1686): getDebugLevel  : 0x4f4c
I/SamsungIME( 1686): KeybaordView init() : load resources
I/SamsungIME( 1686): getCurrentKeyboard
I/SamsungIME( 1686): getTextKeyboard
D/SamsungIME( 1686): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6539): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357928576
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6539): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@771be16 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c5b56d added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6539): addListener: New listener added - the number of listeners is now 1
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6539): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6539): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6539): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6539): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6539): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
E/SMD     (  302): DCD ON
I/chromium( 6539): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/SamsungIME( 1686): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/jxcore-log( 6539): Initializing JXcore engine
W/jxcore-log( 6539): JXcore engine is ready
,E/auditd  ( 1843): In denial and Property audit_ondenial is set to 1 
,E/audit   ( 1843): type=1400 msg=audit(1456909076.012:201): avc:  denied  { ioctl } for  pid=6616 comm="Thread-1083" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
E/audit   ( 1843):  SEPF_SM-N9005_5.0-1_0032
E/audit   ( 1843): 
,D/SecurityLogAgent:SEDenialService(  765): Got Modify Event and sending Denial Intent foraudit.log
,E/audit   ( 1843): type=1300 msg=audit(1456909076.012:201): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a8fb8d8 items=0 ppid=349 ppcomm=main pid=6616 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1083" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,E/audit   ( 1843): type=1320 msg=audit(1456909076.012:201): 
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,W/jxcore-log( 6539): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  765): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,I/ActivityManager(  765): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=6620 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6620): MountEmulatedStorage()
,E/Zygote  ( 6620): v2
I/libpersona( 6620): KNOX_SDCARD checking this for 1000
I/libpersona( 6620): KNOX_SDCARD not a persona
,I/SELinux ( 6620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6620): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 6620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6620): TimaSignature is unavailable
,W/jxcore-log( 6539): Platform android
W/jxcore-log( 6539): 
,W/jxcore-log( 6539): Process ARCH arm
W/jxcore-log( 6539): 
,D/ActivityThread( 6620): Added TimaKeyStore provider
,D/ResourcesManager( 6620): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 6620):  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 6620):  SeDenialReceiver : File path = null
,I/ActivityManager(  765): Killing 5065:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/jxcore-log( 6539): JXcore Cordova bridge is ready!
I/jxcore-log( 6539): 
,W/jxcore-log( 6539): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6539): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/Watchdog(  765): !@Sync 8
,E/SMD     (  302): DCD ON
,D/BatteryService(  765): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager(  765): waitForAlarm result :8
,E/SMD     (  302): DCD ON
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6539): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
V/io.jxcore.node.JXcoreExtension( 6539): isBleMultipleAdvertisementSupported: NOT_RESOLVED
,I/jxcore-log( 6539): BLE multiple advertisement supported
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): INFO testUtils Toggling radios to: true
I/jxcore-log( 6539): 
,D/BluetoothAdapter( 6539): enable()
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=6539, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService(  765): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService(  765): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6539, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService(  765): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23388)
W/BluetoothManagerService(  765): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
W/BluetoothManagerService(  765): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
W/BluetoothManagerService(  765): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService(  765): 	at android.os.Binder.execTransact(Binder.java:446)
E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
,D/SettingsProvider(  765): name = bluetooth_on
,E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
,I/jxcore-log( 6539): Unit Test app is loaded
I/jxcore-log( 6539): 
,I/WifiManager( 6539): packageName : com.test.thalitest
,D/SecContentProvider(  765): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  765): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2(  765): mCursor = null
,D/WifiService(  765): setWifiEnabled: true pid=6539, uid=10079
,W/ActivityManager(  765): Permission Denial: getCurrentUser() from pid=6539, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  765): Failed getting userId using ActivityManagerNative
W/WifiService(  765): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6539, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  765): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23388)
W/WifiService(  765): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2184)
W/WifiService(  765): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2172)
W/WifiService(  765): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  765): 	at android.os.Binder.execTransact(Binder.java:446)
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
D/SettingsProvider(  765): name = wifi_on
,I/WifiService(  765): disconnect: pid=6539, uid=10079
,E/WifiHW  (  765): ##################### set firmware type 0 #####################
,I/WifiHW  (  295): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,I/WifiHW  (  295): module is semco
E/WifiHW  (  295): ==========[WIFI] SEMCO MODULE ===========
I/WifiHW  (  295): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  (  295): TEMP_FAILURE_RETRY complete
D/SoftapController(  295): Softap fwReload - Ok
,I/chromium( 6539): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/CommandListener(  295): Setting iface cfg
D/CommandListener(  295): Trying to bring down wlan0
,D/CommandListener(  295): Clearing all IP addresses on wlan0
,E/WifiHW  (  765): supplicant_name : p2p_supplicant
,I/wpa_supplicant( 6661): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 6661): Successfully initialized wpa_supplicant
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  371): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6661
,I/SecureStorage(  371): [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6661): ssSupport state is = 1
I/wpa_supplicant( 6661): >>>>> GET KEY, IV <<<<<
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  371): [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6661
I/SecureStorage(  371): [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,E/Zygote  ( 6666): MountEmulatedStorage()
E/Zygote  ( 6666): v2
,I/libpersona( 6666): KNOX_SDCARD checking this for 1002
I/libpersona( 6666): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6666 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/SmartBondingService(  765): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/WifiMonitor(  765): startMonitoring(wlan0) with mConnected = false
,I/SELinux ( 6666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6666): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 6666): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=false enabledDesc:null
,D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(2)
,D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1191): onReceive : 2, 0
D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
,D/SmartBondingService(  765): getNetworkEnabled : wifi : false mobile : true
,I/ActivityManager(  765): Start proc tv.peel.samsung.app for broadcast tv.peel.samsung.app/com.peel.receiver.ConnectivityActionReceiver: pid=6682 uid=10152 gids={50152, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a,
,E/Zygote  ( 6682): MountEmulatedStorage()
E/Zygote  ( 6682): v2
I/libpersona( 6682): KNOX_SDCARD checking this for 10152
I/libpersona( 6682): KNOX_SDCARD not a persona
,I/SELinux ( 6682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6682): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/TimaKeyStoreProvider( 6666): TimaSignature is unavailable
D/ActivityThread( 6666): Added TimaKeyStore provider
E/SELinux ( 6682): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 6666): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,W/ResourcesManager( 6666): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 6666): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6682): TimaSignature is unavailable
,D/ActivityThread( 6682): Added TimaKeyStore provider
,D/ResourcesManager( 6682): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,I/BluetoothA2dpSinkServiceJni( 6666): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 6666): Adding GattService
,D/BtSettings.ProfileConfig( 6666): Adding HeadsetService
D/BtSettings.ProfileConfig( 6666): Adding A2dpService
,D/BtSettings.ProfileConfig( 6666): Adding HidService
D/BtSettings.ProfileConfig( 6666): Adding HealthService
D/BtSettings.ProfileConfig( 6666): Adding PanService
,D/BtSettings.ProfileConfig( 6666): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 6666): Adding SapService
D/BtSettings.ProfileConfig( 6666): Adding HeadsetClientService
,D/BtSettings.ProfileConfig( 6666): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 6666): Adding SapClientService
,D/BtSettings.ProfileConfig( 6666): Adding HidDevService
,I/BtSettings.ProfileConfig( 6666): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.gatt.GattService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.hdp.HealthService
,D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
,D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,I/WebViewFactory( 6682): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ResourcesManager( 6682): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  765): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/LibraryLoader( 6682): Time to load native libraries: 3 ms (timestamps 3048-3051)
,I/LibraryLoader( 6682): Expected native library version number "",actual native library version number ""
,D/BluetoothAdapterState( 6666): make
,I/bluedroid( 6666): init
,I/BluetoothAdapterState( 6666): Entering OffState
,I/bte_conf( 6666): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 6666): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 6666): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 6666): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 6666): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 6666): get_profile_interface socket
I/GKI_LINUX( 6666): gki_task_entry task_id=1 [BTIF] starting
I/bluedroid( 6666): get_profile_interface map_client
,D/BluetoothAdapterService( 6666): checkAddrForIOP: Loading from conf
,I/SecureStorage(  371): [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,D/BluetoothAdapterProperties( 6666): Address is:E0:DB:10:1F:C9:5E
,E/BluetoothServiceJni( 6666): populateRssiValuesNative
I/bluedroid( 6666): getModelRssiValues
E/BluetoothServiceJni( 6666): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6666): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider(  765): name = bluetooth_name
,D/BluetoothAdapterProperties( 6666): Name is: Note3-1
,V/WebViewChromiumFactoryProvider( 6682): Binding Chromium to main looper Looper (main, tid 1) {27b45bf}
,I/LibraryLoader( 6682): Expected native library version number "",actual native library version number ""
,I/chromium( 6682): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/bluedroid( 6666): config_hci_snoop_log
,D/BluetoothManagerService(  765): Broadcasting onBluetoothServiceUp() to 10 receivers.
,E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService(  765): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider(  765): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 6666): CURRENT_STATE=OFF, MSG = USER_TURN_ON
D/BluetoothAdapterProperties( 6666): Setting state to 11
I/BluetoothAdapterState( 6666): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 6666): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6666): updateAdapterState state is 11
D/BluetoothAdapterService( 6666): Autoconnection is available 
D/BluetoothAdapterService( 6666): updateAdapterState prevState = 10newState = 11
W/InputMethodManagerService(  765): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  765): [BT Setting State] State =11
D/BluetoothTile( 1191):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1191): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
I/SamsungIME( 1686): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothSecureManager( 6666): getInstant: null
D/StatusBarManagerService(  765): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
D/BluetoothSecureManager( 6666): calling getMethod for getService
D/BluetoothSecureManager( 6666): calling getService
D/StatusBarManagerService(  765): setIconVisibility slot=bluetooth visible=false
D/PhoneStatusBar( 1191): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
D/STATUSBAR-QSTileView( 1191): onStateChanged: Bluetooth
D/BluetoothSecureManager( 6666): getService return binder: android.os.BinderProxy@27a62db7
,D/BluetoothSecureManagerService(  765): isSecureModeEnabled
D/BluetoothSecureManagerService(  765): getSecureModeSetting, name: secure_mode_enable
D/BtConfig.SecureMode( 6666): isSecureModeOn:false
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,D/PhoneStatusBar( 1191): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6666): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 6666): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6666): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6666): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 6666): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 6666): make
,I/BluetoothBondStateMachine( 6666): StableState(): Entering Off State
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/BtGatt.JNI( 6666): classInitNative(L890): classInitNative: Success!
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.a2dp.A2dpService
,I/BrowserStartupController( 6682): Initializing chromium process, singleProcess=true
,W/art     ( 6682): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6682): ApplicationContext is null in ApplicationStatus
,D/BtGatt.DebugUtils( 6666): handleDebugAction() action=null
,D/BtGatt.GattService( 6666): Received start request. Starting profile...
D/BtGatt.GattService( 6666): start()
I/bluedroid( 6666): get_profile_interface gatt
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
D/BtGatt.AdvertiseManager( 6666): advertise manager created
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 6666): Not skipping com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 6666): Not skipping com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6666): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6666): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 6666): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/chromium( 6682): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
W/BluetoothAdapterService( 6666): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 6666): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 6666): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 6666): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/HeadsetService( 6666): Received start request. Starting profile...
,W/chromium( 6682): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6682): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50556 len=3379
I/BluetoothHeadsetServiceJni( 6666): classInitNative: succeeds
I/chromium( 6682): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:7638088 len:1165478
,D/HeadsetStateMachine( 6666): make
,E/HeadsetStateMachine( 6666): # of Max HF connection is 2
,I/Adreno-EGL( 6682): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 6682): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6682): Build Date: 11/19/14 Wed
I/Adreno-EGL( 6682): Local Branch: mybranch5813579
I/Adreno-EGL( 6682): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 6682): Local Patches: NONE
I/Adreno-EGL( 6682): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/bluedroid( 6666): get_profile_interface handsfree
,I/DualScoManager( 6666): Instantiating Dual Sco Manager
I/DualScoManager( 6666): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 6666): createCMTIContentObservers
,D/SettingsProvider(  765): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 6666): Enter Disconnected: -2
,E/HeadsetStateMachine( 6666): set to mRemoteBrsf = 0
D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,D/BluetoothA2dp(  765): Proxy object connected
,D/BluetoothA2dp( 2935): Proxy object connected
D/A2dpService( 6666): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 6666): classInitNative: succeeds
V/Avrcp   ( 6666): make
,V/Avrcp   ( 6666): Avrcp
,I/bluedroid( 6666): get_profile_interface avrcp
D/HeadsetStateMachine( 6666): map size, before remove : 0
D/HeadsetStateMachine( 6666): map size, after remove: 0
,D/HeadsetStateMachine( 6666): mNextConnectingDevice : null
,V/Avrcp   ( 6666): start
,E/RemoteController( 6666): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 6666): ++registerMediaPlayers++
,I/Avrcp   ( 6666): No of Audio players :: 2
,I/Avrcp   ( 6666): App Package name is com.google.android.music
,D/ResourcesManager( 6666): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 6666): App pkg name is Google Play Music
,I/Avrcp   ( 6666): Name::Google Play Music
,V/Avrcp   ( 6666): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 6666): App Package name is com.sec.android.app.music
,D/ResourcesManager( 6666): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,I/Avrcp   ( 6666): App pkg name is Music
,I/Avrcp   ( 6666): Name::Music
V/Avrcp   ( 6666): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 6666):  set player publishabilty with player id::2 toBePublished ::true
,I/Avrcp   ( 6666): No of Video players :: 1
,I/Avrcp   ( 6666): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 6666): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 6666): Video App pkg name is Video Player
,I/Avrcp   ( 6666): Name::Video Player
V/Avrcp   ( 6666): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 6666): Add tempPlayer
,V/Avrcp   ( 6666): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 6666): Total no of players: 4
V/Avrcp   ( 6666): swapping the samsung player with 1st player
I/Avrcp   ( 6666):  Updating now playing list upon AVRCP Start
,V/Avrcp   ( 6666): handleMessage, msg=207
,D/BluetoothMediaBrowser( 6666):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 6666): classInitNative: succeeds
,D/A2dpStateMachine( 6666): make
,I/bluedroid( 6666): get_profile_interface a2dp
,I/GKI_LINUX( 6666): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 6666): warning : media task started media_task_refcnt 1 
,D/BluetoothMediaBrowser( 6666): no now playing list
D/BluetoothMediaBrowser( 6666):  getNowPlayingId now playing id : -1
,D/Avrcp   ( 6666):  checkNowPlayingList start
D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
D/A2dpStateMachine( 6666): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 6666): classInitNative: succeeds
,D/HidService( 6666): Received start request. Starting profile...
,I/bluedroid( 6666): get_profile_interface hidhost
D/HidService( 6666): setHidService(): set to: null
D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,I/BluetoothHealthServiceJni( 6666): classInitNative: succeeds
,D/HealthService( 6666): Received start request. Starting profile...
,I/bluedroid( 6666): get_profile_interface health
,D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,I/BluetoothPanServiceJni( 6666): classInitNative(L105): succeeds
,D/BluetoothPan(  765): BluetoothPAN Proxy object connected
,D/PanService( 6666): Received start request. Starting profile...
D/BluetoothPanServiceJni( 6666): initializeNative(L110): pan
I/bluedroid( 6666): get_profile_interface pan
,D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,D/BluetoothMapService( 6666): Received start request. Starting profile...
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,W/chromium( 6682): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,E/Zygote  ( 6738): MountEmulatedStorage()
E/Zygote  ( 6738): v2
I/libpersona( 6738): KNOX_SDCARD checking this for 10186
I/libpersona( 6738): KNOX_SDCARD not a persona
,I/SELinux ( 6738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6738): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 6738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SSRM:n  (  765): SIOP:: AP = 330, PST = 290, CUR = 450
,I/ActivityManager(  765): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=6738 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6738): TimaSignature is unavailable
,D/ActivityThread( 6738): Added TimaKeyStore provider
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Processing data has been completed
,W/art     ( 6682): Attempt to remove local handle scope entry from IRT, ignoring
,D/ResourcesManager( 6738): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6738): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6738): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6738): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6738): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6738): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/AwContents( 6682): onDetachedFromWindow called when already detached. Ignoring
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  371): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6661
I/SecureStorage(  371): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6661): ssSupport state is = 1
I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 6661): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6661): SIM READ ERROR
I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6661): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6661): SIM READ ERROR
I/wpa_supplicant( 6661): Blacklist: Clear (all) 
I/wpa_supplicant( 6661): wpa_default_ap_write_once
I/wpa_supplicant( 6661): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6661): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6661): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,I/wpa_supplicant( 6661): rfkill: Cannot open RFKILL control device
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothSAPServiceJni( 6666): classInitNative(L204): succeeds
,D/SapService( 6666): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 6666): initializeNative(L209): sap
I/bluedroid( 6666): get_profile_interface sap
D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
,D/HeadsetStateMachine( 6666): Try to query the phonestate on bind
,I/Telecom ( 1404): BluetoothPhoneService: queryPhoneState
D/RCPManagerService(  765): exchangeData() failure , invalid userId
,I/Telecom ( 1404): BluetoothPhoneService: updateHeadsetWithCallState
,D/BadgeProvider( 6214): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/Telecom ( 1404): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothHeadset( 1404): Proxy not attached to service
,D/HeadsetStateMachine( 6666): Proxy object connected
D/HeadsetPhoneState( 6666): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetPhoneState( 6666): sendDeviceDataStateChanged
D/HeadsetPhoneState( 6666): Signal level : previous=0 curr=0
E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 6666): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 6666): Proxy object connected
D/BluetoothAdapterService( 6666): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 6666): Disconnected process message: 11
D/HeadsetStateMachine( 6666): Disconnected process message: 18
D/HeadsetStateMachine( 6666): Disconnected process message: 10
D/HeadsetPhoneState( 6666): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 6666): Disconnected process message: 11
,E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(422019038)( 6666): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,D/BluetoothAdapterState( 6666): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 6666): enable
,I/GKI_LINUX( 6666): gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 6666): init
,D/BadgeProvider( 6214): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1441): reloadBadges entered.
,D/BadgeProvider( 6214): sendNotify, [notify] : null
D/BadgeProvider( 6214): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6214): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6214): update, [UpdateCount] : 1
I/bt_vendor( 6666): init
I/bt_vnd_conf( 6666): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6666): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6666): userial_init
D/bt_vendor( 6666): op for 5
,D/bt_vendor( 6666): op for 0
D/bt_upio ( 6666): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6666): is_emulator_context : 0
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
,D/bt_vendor( 6666): op for 0
D/bt_upio ( 6666): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6666): is_emulator_context : 0
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
,D/bt_vendor( 6666): op for 3
I/bt_userial_vendor( 6666): userial vendor open: opening /dev/ttyHS0
,I/bt_userial_vendor( 6666): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6666): device fd = 65 open
,D/bt_vendor( 6666): op for 1
D/bt_userial( 6666): Entering userial_read_thread()
,E/bt_hwcfg( 6666): Start CFG HW, HCI reset
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,I/ActivityManager(  765): Killing 5347:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,I/art     (  765): Explicit concurrent mark sweep GC freed 39308(2MB) AllocSpace objects, 59(944KB) LOS objects, 30% free, 36MB/52MB, paused 1.249ms total 91.511ms
,E/SignOutReceiver( 6353): WIFI_STATE_CHANGED_ACTION
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6620): StateMachine : Current State = 1
,D/SecurityLogAgent( 6620): StateMachine : Changed Current State = 1
,I/ActivityManager(  765): Killing 5387:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6781): MountEmulatedStorage()
,E/Zygote  ( 6781): v2
I/libpersona( 6781): KNOX_SDCARD checking this for 10140
I/libpersona( 6781): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6781 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 6781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6781): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 6781): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6781): TimaSignature is unavailable
,D/ActivityThread( 6781): Added TimaKeyStore provider
,W/ActivityManager(  765): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ResourcesManager( 6781): creating new AssetManager and set to /system/app/Maps/Maps.apk
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StrictMode( 6781): StrictMode policy violation; ~duration=217 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6781): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 6781): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 6781): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 6781): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 6781): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 6781): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,D/StrictMode( 6781): StrictMode policy violation; ~duration=204 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6781): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 6781): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 6781): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 6781): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 6781): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=156 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6781): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6781): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6781): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
D/StrictMode( 6781): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
D/StrictMode( 6781): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
D/StrictMode( 6781): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Hand,ler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=155 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 6781): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 6781): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 6781): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
D/StrictMode( 6781): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 6781): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 6781): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 6781): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
D/StrictMode( 6781): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at a,ndroid.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 6781): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 6781): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 6781): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 6781): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 6781): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 6781): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 6781): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 6781): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 6781): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 6781): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 6781): 	at com.google.r.e.b(PG:170)
D/StrictMode( 6781): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 6781): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 6781): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( ,6781): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 6781): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 6781): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 6781): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 6781): 	at com.google.r.k.c(PG:583)
D/StrictMode( 6781): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 6781): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 6781): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 6781): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 6781): 	at com.google.r.e.b(PG:170)
D/StrictMode( 6781): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6781): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6781): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6781): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
D/StrictMode( 6781): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
D/StrictMode( 6781): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
D/StrictMode( 6781): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at androi,d.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 6781): StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 6781): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 6781): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 6781): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 6781): 	at java.io.File.exists(File.java:363)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 6781): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 6781): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 6781): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 6781): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 6781): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 6781): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 6781): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 6781): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 6781): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 6781): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 6781): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
I/ActivityManager(  765): Killing 5745:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): bgCount ##41
,D/AuthorizationBluetoothService( 1749): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/com.google.a.a.b.d.a( 6781): Application name is not set. Call Builder#setApplicationName.
,E/Tethering(  765): No numeric data
,D/Tethering(  765): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime(  765): forceRefresh() from cache miss
,D/HotspotTile( 1191): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/NtpTrustedTime(  765): forceRefresh Fail.
,V/NetworkStats(  765): performPollLocked(flags=0x1)
D/HotspotTile( 1191): updateTetherState():false, false
,D/NetworkStatsFactory(  765): UpdateStatsForKnox
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/NetworkStats(  765): performPollLocked() took 3ms
,D/NtpTrustedTime(  765): forceRefresh() from cache miss
,D/NtpTrustedTime(  765): forceRefresh Fail.
,I/wpa_supplicant( 6661): wlan0: Setting scan request: 0 sec 100000 usec
,I/wpa_supplicant( 6661): wlan0: State: DISCONNECTED -> DISCONNECTED
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  371): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6661
I/SecureStorage(  371): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6661): ssSupport state is = 1
,I/SecureStorage( 6661): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  371): [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6661
I/SecureStorage(  371): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 6661): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 6661): ssSupport state is = 1
I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6661): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6661): SIM READ ERROR
I/wpa_supplicant( 6661): wpa_default_ap_write_once
I/wpa_supplicant( 6661): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 6661): rfkill: Cannot open RFKILL control device
,I/wpa_supplicant( 6661): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6661): p2p0: State: INACTIVE -> DISCONNECTED
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,E/WifiStateMachine(  765): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative-HAL(  765): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 6661): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 6661): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 6661): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 6661): SIM READ ERROR
I/wpa_supplicant( 6661): Blacklist: Clear (all) 
,I/wpa_supplicant( 6661): Skip scan - bUseNetwork false
,D/WifiNative-HAL(  765): callSECApiInt - ID [210]
,D/WifiConfigStore(  765): Loading config and enabling all networks 
D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/SmartBondingService(  765): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1191): Wifi onReceive(3)
,D/STATUSBAR-QSTileView( 1191): onStateChanged: Wi-Fi
,D/HotspotTile( 1191): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/SmartBondingService(  765): getNetworkEnabled : wifi : true mobile : true
,D/HotspotTile( 1191): onReceive : 3, 0
,D/WifiCredService( 1309): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/WifiConfigStore(  765): Not a HS20
,E/SignOutReceiver( 6353): WIFI_STATE_CHANGED_ACTION
,E/WifiConfigStore(  765): Not a HS20
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiConfigStore(  765): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
D/SecurityLogAgent( 6620): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6620): StateMachine : Current State = 1
,D/SecurityLogAgent( 6620): StateMachine : Changed Current State = 1
,D/WifiNative-HAL(  765): callSECApiInt - ID [65]
,D/WifiNative-HAL(  765): callSECApiBoolean - ID [13]
I/wpa_supplicant( 6661): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6661): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6661): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6661): P2P: Current p2p state = IDLE
I/wpa_supplicant( 6661): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 6661): First Scan Start
,I/wpa_supplicant( 6661): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-HAL(  765): Setting external_sim to 1
W/Settings( 5165): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  765): Setting OUI to DA-A1-19
I/WifiNative-HAL(  765): startHal
E/wifi    (  765): getStaticLongField sWifiHalHandle 0x933dd86c
D/wifi    (  765): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xa01e0a
I/WifiNative-HAL(  765): Could not start hal
,E/native  (  765): do suspend true
,E/WifiStateMachine(  765): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
D/WifiScanningService(  765): SCAN_AVAILABLE : 3
D/RttService(  765): SCAN_AVAILABLE : 3
D/WifiScanningService(  765): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiNative-HAL(  765): startHal
D/WifiP2pService(  765): P2pDisabledState{ what=131203 }
E/wifi    (  765): getStaticLongField sWifiHalHandle 0x9b04f99c
D/RttService(  765): DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/wifi    (  765): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501de2
I/WifiNative-HAL(  765): Could not start hal
E/WifiScanningService(  765): could not start HAL
,D/CommandListener(  295): Setting iface cfg
D/CommandListener(  295): Trying to bring up p2p0
,D/WifiMonitor(  765): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine(  765): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  765): callSECStringApiVoid - ID [215]
,E/WifiNative-HAL(  765): invaild command id : 215
,D/WifiP2pService(  765): P2pEnablingState
,D/WifiP2pService(  765): P2pEnablingState{ what=147457 }
D/WifiP2pService(  765): P2p socket connection successful
D/WifiP2pService(  765): P2pEnabledState
,D/WifiDisplayController(  765): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController(  765): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
E/WifiStateMachine(  765): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayController(  765): disconnect
D/WifiDisplayController(  765): updateConnection
D/WifiDisplayController(  765): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
D/WifiP2pService(  765): sending p2p connection changed broadcast: IDLE
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/wpa_supplicant( 6661): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/Zygote  ( 6811): MountEmulatedStorage()
E/Zygote  ( 6811): v2
I/wpa_supplicant( 6661): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
I/libpersona( 6811): KNOX_SDCARD checking this for 10192
,I/libpersona( 6811): KNOX_SDCARD not a persona
D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  765): mCursor = null
I/ActivityManager(  765): Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=6811 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  765): mCursor = null
D/WifiDisplayController(  765): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/WifiP2pService(  765): create mNetworkAgent
I/SELinux ( 6811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/AllShareCastTile( 1191): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/SELinux ( 6811): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/AllShareCastTile( 1191): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
E/SELinux ( 6811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  765): Got NetworkAgent Messenger
D/ConnectivityService(  765): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  765): updateNetworkInfo()
,D/ConnectivityService(  765): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  765): NetworkAgent connected
E/CSLegacyTypeTracker(  765): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiNative-HAL(  765): p2pGetDeviceAddress
,D/WifiNative-HAL(  765): p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,D/WifiDisplayController(  765): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
D/WifiDisplayController(  765):  deviceAddress: ea:50:8b:de:28:a3
D/WifiDisplayController(  765):  primary type: 10-0050F204-5
D/WifiDisplayController(  765):  secondary type: null
D/WifiDisplayController(  765):  wps: 0
D/WifiDisplayController(  765):  grpcapab: 0
D/WifiDisplayController(  765):  devcapab: 0
D/WifiDisplayController(  765):  status: 3
D/WifiDisplayController(  765):  wfdInfo: null
D/WifiDisplayController(  765):  groupownerAddress: null
D/WifiDisplayController(  765):  GOdeviceName: null
D/WifiDisplayController(  765):  interfaceAddress: 
D/WifiDisplayController(  765):  SConnectInfo : null
D/WifiP2pService(  765): DeviceAddress: ea:28:a3
,D/TimaKeyStoreProvider( 6811): TimaSignature is unavailable
,D/ActivityThread( 6811): Added TimaKeyStore provider
,D/WifiP2pService(  765): sending p2p persistent groups changed broadcast
D/WifiP2pService(  765): InactiveState
,D/WifiP2pService(  765): InactiveState{ what=143376 }
D/WifiP2pService(  765): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 6661): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/ResourcesManager( 6811): creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,E/ConnectivityService(  765): updateNetworkInfo()
D/ConnectivityService(  765): ignoring duplicate network state non-change. WIFI_P2P, state = UNKNOWN
D/WifiP2pService(  765): InactiveState{ what=143376 }
D/WifiP2pService(  765): P2pEnabledState{ what=143376 }
,D/WifiDirectBR( 6811): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,I/ActivityManager(  765): Killing 5765:flipboard.app/u0a125 (adj 15): bgCount ##41
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6827): MountEmulatedStorage()
,E/Zygote  ( 6827): v2
,I/libpersona( 6827): KNOX_SDCARD checking this for 10088
,I/libpersona( 6827): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6827 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6827): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 6827): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 6827): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6827): TimaSignature is unavailable
D/ActivityThread( 6827): Added TimaKeyStore provider
,D/ResourcesManager( 6827): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 6827): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/WifiDirectBR( 6811): WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDirectBR( 6811): WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,W/ContextImpl( 6811): Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,D/WifiDirectBR( 6811): stopServiceTest : false
,I/ActivityManager(  765): Killing 5273:com.google.android.music:main/u0a144 (adj 15): bgCount ##41
,I/wpa_supplicant( 6661): nl80211: Received scan results (18 BSSes)
I/wpa_supplicant( 6661): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6661): Trying to associate with F4.99.3E (SSID='4E47373030' freq=2437 MHz)
I/wpa_supplicant( 6661): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,I/WifiNative-HAL(  765): startHal
,E/wifi    (  765): getStaticLongField sWifiHalHandle 0x933dd88c
,D/wifi    (  765): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x202146
,I/WifiNative-HAL(  765): Could not start hal
,E/SMD     (  302): DCD ON
,D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  765): mCursor = null
,I/wpa_supplicant( 6661): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 6661): Associated with F4.99.3E
I/wpa_supplicant( 6661): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  765): mCursor = null
,D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  765): mCursor = null
,I/wpa_supplicant( 6661): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 6661): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,I/wpa_supplicant( 6661): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 6661): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 6661): CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
I/wpa_supplicant( 6661): Blacklist: Clear (temp) 
I/wpa_supplicant( 6661): CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,D/WifiNative-HAL(  765): callSECApiVoid - ID [50]
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  765): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService(  765): Got NetworkAgent Messenger
D/ConnectivityService(  765): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService(  765): updateNetworkInfo()
D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  765): NetworkAgent connected
,E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  765): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  295): Setting iface cfg
,E/Zygote  ( 6868): MountEmulatedStorage()
,E/Zygote  ( 6868): v2
,I/libpersona( 6868): KNOX_SDCARD checking this for 10038
,I/libpersona( 6868): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=6868 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/WifiStateMachine(  765): Start Dhcp Watchdog 1
,I/SELinux ( 6868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 6868): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  765): mCursor = null
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,E/SELinux ( 6868): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/TimaKeyStoreProvider( 6868): TimaSignature is unavailable
,D/ActivityThread( 6868): Added TimaKeyStore provider
,E/native  (  765): do suspend false
,D/ResourcesManager( 6868): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/SecContentProvider2(  765): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  765): InactiveState{ what=143375 }
D/SecContentProvider2(  765): mCursor = null
,D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,W/ResourcesManager( 6868): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/VlingoApplication( 6868): VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,E/dhcpcd  ( 6888): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6888): version 5.5.6 starting
,E/dhcpcd  ( 6888): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6888): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6888): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6888): if(wlan0) info get Success. (MAC : F4.99.3E)
,I/dhcpcd  ( 6888): bssid match
,I/dhcpcd  ( 6888): wlan0: rebinding lease of 192.168.1.104
,I/dhcpcd  ( 6888): wlan0: acknowledged 192.168.1.104 from 192.168.1.1
,E/BluetoothHeadset( 6868): BTStateChangeCB is registed
,E/BluetoothHeadset( 6868): BluetoothHeadset service is binded
,I/ActivityManager(  765): Killing 5165:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,D/SettingsProvider(  765): name = driving_mode_on
,D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 10038
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,D/BluetoothManager( 6868): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6353): NETWORK_STATE_CHANGED_ACTION
,I/dhcpcd  ( 6888): wlan0: leased 192.168.1.104 for 172800 seconds
,D/ConnectivityService(  765): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/native  (  765): do suspend true
,D/WifiP2pService(  765): InactiveState{ what=143375 }
,D/WifiP2pService(  765): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  765): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  765): Update of LinkProperties for NetworkAgentInfo [WIFI () - 502]; created=false
,E/WifiStateMachine(  765): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine(  765): VerifyingLinkState enter
,D/WifiNative-HAL(  765): callSECApiInt - ID [210]
,E/ConnectivityService(  765): updateNetworkInfo()
,D/ConnectivityService(  765): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  765): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine(  765): updateDnsLinkProperty: enter
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.DnsPinger(  765): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver(  765): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker(  765): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  765): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,D/ConnectivityService(  765): Adding Route [fe80::/64 -> :: wlan0] to network 502
,D/ConnectivityService(  765): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,E/WifiStateMachine(  765): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService(  765): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 502
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1191): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:null
,E/ConnectivityService(  765): Unexpected mtu value: 0, wlan0
,D/ConnectivityService(  765): updateSourceRoutes : add source routing for type : 1
,D/ConnectivityService(  765): updateSourceRoutes : add src route for:192.168.1.104
,V/        (  295): QcRouteController
,I/WifiTrafficPoller(  765): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  765): mBoosterFLAG : 0
,I/WifiTrafficPoller(  765): current booster mode : FullMode
D/WifiNative-HAL(  765): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,E/WifiStateMachine(  765): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,V/        (  295): QcRouteController
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
,V/        (  295): QcRouteController
,V/        (  295): QcRouteController
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6353): NETWORK_STATE_CHANGED_ACTION
,V/        (  295): QcRouteController
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1309): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1309): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1309): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1309): MountReceiver.mPrefHandler - 7002
,V/        (  295): QcRouteController
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6353): NETWORK_STATE_CHANGED_ACTION
,D/NearbySettings( 1309): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1309): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  765): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,V/        (  295): QcRouteController
,V/        (  295): QcRouteController
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6353): NETWORK_STATE_CHANGED_ACTION
,I/SurfaceFlinger(  266): id=12 createSurf (1x1),1 flag=4, Uoast
,V/        (  295): QcRouteController
,D/PowerManagerService(  765): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765
,D/ConnectivityService(  765): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  295): QcRouteController
,V/        (  295): QcRouteController
,W/NetworkManagementService(  765): route cmd failed: 
W/NetworkManagementService(  765): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '50 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 50 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  765): '
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  765): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  765): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5631)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5443)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.updateNetworkInfo(ConnectivityService.java:6206)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService.access$2500(ConnectivityService.java:229)
W/NetworkManagementService(  765): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2399)
W/NetworkManagementService(  765): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  765): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  765): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  765): Setting Dns servers for network 502 to [/192.168.1.1]
,D/ConnectivityService(  765): LTETest block dns file not exists
,V/Nat464Xlat(  765): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/ConnectivityService(  765): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  765): calling update connectivity
,D/ConnectivityService(  765): ignoring duplicate network state non-change. WIFI, state = CONNECTING
,E/ConnectivityService(  765): updateNetworkInfo()
D/ConnectivityService(  765): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  765): updateNetworkInfo()
,D/EntConnectivity(  765): Not allowed due to - mEnabled false
,D/ConnectivityService(  765): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  765): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  765): calling update connectivity
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Checking http://clients3.google.com/generate_204 on "NG700"
,D/ConnectivityService(  765): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  765):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  765):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  765):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  765): currentScore = 0, newScore = 60
,D/ConnectivityService(  765):    accepting network in place of null
D/ConnectivityService(  765): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  765): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,D/TelephonyNetworkFactory( 1425): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  765): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker(  765): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  765): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  765): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NtpTrustedTime(  765): forceRefresh() from cache miss
,D/SmartBondingService(  765): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  765): getSBEnabled() enabled =false
D/SmartBondingService(  765): getSBEnabled() enabled =false
D/SmartBondingService(  765): getSBEnabled() enabled =false
,I/System.out(  765): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(  765): (HTTPLog)-Static: isShipBuild true
V/NetworkStats(  765): updateIfacesLocked()
V/NetworkStats(  765): performPollLocked(flags=0x1)
,I/System.out(  765): (HTTPLog)-Thread-181-833545912: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/SmartBondingService(  765): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  765): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.104/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  765): MasterInitialState.processMessage what=3
,I/System.out(  765): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkStatsFactory(  765): UpdateStatsForKnox
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/EntConnectivity(  765): Not allowed due to - mEnabled false
,D/ConnectivityService(  765): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  765): calling update connectivity
D/ConnectivityService(  765):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/ConnectivityService(  765):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,W/BugLogger( 1622): Bug [16132553]
,D/ConnectivityService(  765): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
,V/NetworkStats(  765): performPollLocked() took 13ms
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1191): applyOpen
D/StatusBar.NetworkController( 1191): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1191): applyOpen
,I/System.out(  765): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime(  765): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1456909086049 mCachedNtpElapsedRealtime : 267036 mCachedNtpCertainty : 18
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
V/NetworkStats(  765): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 02 Mar 2016 08:58:06 GMT], X-Android-Received-Millis=[1456909085641], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1456909085616]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  765): Validated
,D/ConnectivityService(  765): Validated NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  765): rematching NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  765):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService(  765):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  765): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,D/ConnectivityService(  765): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService(  765): calling update connectivity
D/ConnectivityService(  765):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  765):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  765): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1191): CM callback handler got msg 524290
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1191): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1191): updateDataNetType()
D/StatusBar.NetworkController( 1191): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1191): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1191): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1191): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1191): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1191): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/ConnectivityService(  765): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  765): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  765): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/SmartBondingService(  765): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  765): SmartBondingReceiver: wifi ap is changed, init speed ratio
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  765): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  765): getSBEnabled() enabled =false
D/SmartBondingService(  765): getSBEnabled() enabled =false
,D/SmartBondingService(  765): getSBEnabled() enabled =false
,D/SmartBondingService(  765): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/NtpTrustedTime(  765): currentTimeMillis() cache hit
,D/AlarmManagerService(  765): Setting time of day to sec=1456909086
,D/AlarmManagerService(  765): Trying to open a file
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AlarmManagerService(  765): File Open Success
,D/AlarmManagerService(  765): File Close Success
I/AlarmManagerService(  765): DRM_TIME_PATH CHMOD 666 for resetState done 
,W/AlarmManagerService(  765): Unable to set rtc to 1456909086: Invalid argument
V/AlarmManager(  765): waitForAlarm result :65536
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiStateMachine(  765): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,I/DowntimeConditions(  765): android.intent.action.TIME_SET ignored because schedule turned off.
,W/Settings(  765): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.TIME_SET
,D/KeyguardEffectViewController( 1191): onReceive action : android.intent.action.TIME_SET
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/StatusBar-DoNotDistrub( 1191): Received intent with android.intent.action.TIME_SET action
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar-DoNotDistrub( 1191): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DrmEventService(  765):  no response from SecureClock 
,D/accuweather( 1772): [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
D/accuweather( 1772): [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,D/accuweather( 1772): [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/PCWCLIENTTRACE_PushUtil( 6114): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6114): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6114): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6114): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 7005): MountEmulatedStorage()
,E/Zygote  ( 7005): v2
I/libpersona( 7005): KNOX_SDCARD checking this for 10014
I/libpersona( 7005): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7005 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/StatusBar-DoNotDistrub( 1191): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/art     (  349): Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 438us total 17.563ms
,I/SELinux ( 7005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7005): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7005): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/AudioPolicyManager(  309): getOutputsForDevice device 0002 -> 0002
I/AudioService(  765): getStreamVolume 5 index 0
,D/StatusBar-DoNotDistrub( 1191): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  765): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,D/KeyguardUpdateMonitor( 1191): handleTimeUpdate
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 386us total 14.350ms
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1191): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 546us total 13.452ms
,D/TimaKeyStoreProvider( 7005): TimaSignature is unavailable
,D/ActivityThread( 7005): Added TimaKeyStore provider
,I/jxcore-log( 6539): My device name is: samsung-SM-N9005
I/jxcore-log( 6539): 
,E/Zygote  ( 7022): MountEmulatedStorage()
,E/Zygote  ( 7022): v2
I/libpersona( 7022): KNOX_SDCARD checking this for 10144
I/libpersona( 7022): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7022 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7022): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7022): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7022): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7005): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7035): MountEmulatedStorage()
E/Zygote  ( 7035): v2
I/libpersona( 7035): KNOX_SDCARD checking this for 10209
I/libpersona( 7035): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService: pid=7035 uid=10209 gids={50209, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7035): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7035): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7035): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7022): TimaSignature is unavailable
,D/ActivityThread( 7022): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 7035): TimaSignature is unavailable
,D/ActivityThread( 7035): Added TimaKeyStore provider
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,D/ResourcesManager( 7022): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 7035): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7035): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7035): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7035): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 7062): MountEmulatedStorage()
,E/Zygote  ( 7062): v2
I/libpersona( 7062): KNOX_SDCARD checking this for 10023
I/libpersona( 7062): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7062 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7062): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7062): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7062): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/JNIHelp ( 7035): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/TimaKeyStoreProvider( 7062): TimaSignature is unavailable
,D/ActivityThread( 7062): Added TimaKeyStore provider
,W/ActivityThread( 7035): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7035): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1773d8c6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,E/SMD     (  302): DCD ON
I/ProviderInstaller( 7035): Installed default security provider GmsCore_OpenSSL
,I/MusicStore( 7022): Database version: 108
,D/ResourcesManager( 7062): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.511: ( 7062): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/GpsLocationProvider(  765): No APN found to select.
,I/KLMS-2.4.511: ( 7062): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1456909087216
,I/KLMS-2.4.511: ( 7062): MainReciver(): TIME_CHANGED
,I/KLMS-2.4.511: ( 7062): StateImplV2(): dateTimeChanged().START : Wed Mar 02 09:58:07 GMT+01:00 2016
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7062): StateImplV2(): dateTimeChanged().END
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/System.err( 6129): android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,W/System.err( 6129): 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
W/System.err( 6129): 	at android.provider.Settings$System.getLong(Settings.java:1669)
,W/System.err( 6129): 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
W/System.err( 6129): 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
W/System.err( 6129): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 6129): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,W/System.err( 6129): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 6129): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6129): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6129): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 6129): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 6129): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6129): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 6129): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7096): MountEmulatedStorage()
,E/Zygote  ( 7096): v2
I/libpersona( 7096): KNOX_SDCARD checking this for 10042
I/libpersona( 7096): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=7096 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7096): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7096): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityThread( 3838): Failed to find provider info for com.android.contacts.metadata
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7096): TimaSignature is unavailable
,D/ActivityThread( 7096): Added TimaKeyStore provider
,D/SyncManager(  765): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 23529, reason: UserStart, SyncResult: databaseError: true stats []
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  765): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 301321, reason: UserStart
,D/ResourcesManager( 7096): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7096): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,I/SA      ( 6170): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/SecContentProvider2(  765): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  765): mCursor = null
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7022): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 7116): MountEmulatedStorage()
I/ActivityManager(  765): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7116 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7116): v2
I/libpersona( 7116): KNOX_SDCARD checking this for 10076
I/libpersona( 7116): KNOX_SDCARD not a persona
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7116): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7116): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 5878:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7116): TimaSignature is unavailable
,D/ActivityThread( 7116): Added TimaKeyStore provider
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,V/JNIHelp ( 7022): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/ResourcesManager( 7116): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,E/Auth.Api.Credentials( 3838): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityThread( 7022): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/System  ( 7022): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@644bb52: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7022): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7022): GMSCore installation verified
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/ Time Manager ( 7116): Time Difference not stored. TIME_DIFFERENCE
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1749): Tagging socket 71 with tag 1000120300000000{268440067,0} uid -1, pid: 1749, getuid(): 10015
,E/Zygote  ( 7142): MountEmulatedStorage()
,E/Zygote  ( 7142): v2
I/libpersona( 7142): KNOX_SDCARD checking this for 10106
I/libpersona( 7142): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7142 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/dex2oat ( 7136): ----------------------------------------------------
I/dex2oat ( 7136): <SS>: S T A R T I N G . . .
I/dex2oat ( 7136): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 7136): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1088130079.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-1088130079.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/qtaguid ( 1749): Tagging socket 76 with tag 1000120300000000{268440067,0} uid -1, pid: 1749, getuid(): 10015
,I/dex2oat ( 7136): dex2oat took 42.958ms (threads: 4)
,I/SELinux ( 7142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  765): Killing 6062:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
I/SELinux ( 7142): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7142): TimaSignature is unavailable
,D/ActivityThread( 7142): Added TimaKeyStore provider
,D/ResourcesManager( 7142): creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,W/ResourcesManager( 7142): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7142): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7142): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/System.err( 7035): YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ConfigStore( 7022): Config Database version: 1
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7035): YouTube MDX: MDX video stage moved to NEW
,I/System.out( 7035): YouTube MDX: MDX video player state moved to UNSTARTED
,I/System.out( 7035): YouTube MDX: MDX ad player state moved to UNSTARTED
,D/SettingsProvider(  765): name = next_alarm_formatted
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 10106
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ConnectivityChangeReceiver( 3838): Ignoring connectivity change
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7035): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  765): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  765): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  765): apparently satisfied.  currentScore=60
,D/ConnectivityService(  765): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  765): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
D/ConnectivityManager.CallbackHandler( 3838): CM callback handler got msg 524290
,E/Zygote  ( 7188): MountEmulatedStorage()
,E/Zygote  ( 7188): v2
I/libpersona( 7188): KNOX_SDCARD checking this for 10116
I/libpersona( 7188): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7188 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/ActivityManager(  765): Killing 6080:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
I/SELinux ( 7188): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7188): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7188): TimaSignature is unavailable
,D/ActivityThread( 7188): Added TimaKeyStore provider
,D/ResourcesManager( 7188): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,I/PhenotypeConfigurator( 1749): Scheduling Phenotype for one-off execution 5020 seconds from now (1456909088245)
,D/elm:14491( 7188): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14491( 7188): ELMEngine.ELMEngine( context ).
,D/elm:14491( 7188): MDMBridge.setEnterpriseBridge()
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/elm:14491( 7188): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14491( 7188): ElmAgentService : onCreate()
,D/elm:14491( 7188): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/elm:14491( 7188): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,I/AudioService(  765): getStreamVolume 3 index 0
,D/elm:14491( 7188): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14491( 7188): ModuleBase.ModifySetAlarm()
D/elm:14491( 7188): MDMBridge.getInstance()
D/elm:14491( 7188): MDMBridge.getAllLicenseInfoFromSDK()
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/elm:14491( 7188): ElmAgentService : onDestroy().
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService(  765): getStreamVolume 3 index 0
,I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,I/MediaRouter( 7022): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,E/Zygote  ( 7208): MountEmulatedStorage()
E/Zygote  ( 7208): v2
I/libpersona( 7208): KNOX_SDCARD checking this for 10172
I/libpersona( 7208): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7208 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 7208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7208): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  765): Killing 6097:com.sec.android.service.health/u0a21 (adj 15): bgCount ##41
,V/MusicLeanback( 7022): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7208): TimaSignature is unavailable
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7022): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ActivityThread( 7208): Added TimaKeyStore provider
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7035): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/ResourcesManager( 7208): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 7208): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7208): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7035): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7035): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/bt-btif ( 6666): ...preload_wait_timeout (retried:0/max-retry:1)...
,D/bt_userial( 6666): RX termination
W/bt_userial( 6666): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 6666): Leaving userial_read_thread()
,D/bt_vendor( 6666): op for 4
I/bt_userial_vendor( 6666): device fd = 65 close
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_vendor( 6666): op for 0
,D/bt_upio ( 6666): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6666): is_emulator_context : 0
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
,D/bt_vendor( 6666): cleanup
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6620): StateMachine : Current State = 1
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PicasaService( 5362): start picasa sync
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/PicasaService( 5362): end picasa sync
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 7022): type=WIFI subType= reason=null isConnected=true
,E/Zygote  ( 7262): MountEmulatedStorage()
,E/Zygote  ( 7262): v2
I/libpersona( 7262): KNOX_SDCARD checking this for 10051
I/libpersona( 7262): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7262 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/bt_hci_bdroid( 6666): init
,I/bt_vendor( 6666): init
I/bt_vnd_conf( 6666): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 6666): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 6666): userial_init
D/bt_vendor( 6666): op for 5
,E/Zygote  ( 7268): MountEmulatedStorage()
,E/Zygote  ( 7268): v2
I/libpersona( 7268): KNOX_SDCARD checking this for 1000
I/libpersona( 7268): KNOX_SDCARD not a persona
,I/SELinux ( 7262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 7262): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7262): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/bt_vendor( 6666): op for 0
D/bt_upio ( 6666): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 6666): is_emulator_context : 0
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
D/bt_vendor( 6666): op for 0
D/bt_upio ( 6666): upio_set_bluetooth_power(on: 1)
D/bt_upio ( 6666): is_emulator_context : 0
D/bt_upio ( 6666): is_rfkill_disabled ? [0]
D/bt_vendor( 6666): op for 3
I/bt_userial_vendor( 6666): userial vendor open: opening /dev/ttyHS0
,I/ActivityManager(  765): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/bt_userial_vendor( 6666): userial_vendor_open():UART is setup
I/bt_userial_vendor( 6666): device fd = 65 open
,D/bt_vendor( 6666): op for 1
E/bt_hwcfg( 6666): Start CFG HW, HCI reset
D/bt_userial( 6666): Entering userial_read_thread()
,I/SELinux ( 7268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7268): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7262): TimaSignature is unavailable
,D/ActivityThread( 7262): Added TimaKeyStore provider
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7268): TimaSignature is unavailable
,D/ActivityThread( 7268): Added TimaKeyStore provider
,E/bt_hwcfg( 6666): Read Local Name after HCI reset
,E/Zygote  ( 7294): MountEmulatedStorage()
,E/Zygote  ( 7294): v2
I/libpersona( 7294): KNOX_SDCARD checking this for 10004
I/libpersona( 7294): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7294 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/bt_hwcfg( 6666): Chipset BCM4335C0
,D/bt_hwcfg( 6666): Target name = [BCM4335C0]
,I/bt_hwcfg( 6666): module_type[semco].
I/bt_hwcfg( 6666): not ZERO...
I/bt_hwcfg( 6666): module_type[semco] is invalid.
,E/bt_hwcfg( 6666): patchram path ORG . BCM4335C0
,E/bt_hwcfg( 6666): patchram path ORG .. BCM4335C0
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
E/bt_hwcfg( 6666): patchram path ORG bcm4335_V0105.0467.hcd BCM4335C0
,E/bt_hwcfg( 6666): patchram path ORG bcm4335_V0105.0467_wisol.hcd BCM4335C0
E/bt_hwcfg( 6666): fw ver (org)0.0
E/bt_hwcfg( 6666): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 6666): Remove module rev, try again BCM4335
D/bt_hwcfg( 6666): Target name = [BCM4335]
I/bt_hwcfg( 6666): module_type[semco].
,I/bt_hwcfg( 6666): not ZERO...
I/bt_hwcfg( 6666): module_type[semco] is invalid.
E/bt_hwcfg( 6666): patchram path ORG . BCM4335
E/bt_hwcfg( 6666): patchram path ORG .. BCM4335
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB4_firmware.ncd BCM4335
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
,E/bt_hwcfg( 6666): patchram path ORG bcm2079xB5_firmware.ncd BCM4335
E/bt_hwcfg( 6666): patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
E/bt_hwcfg( 6666): patchram path ORG bcm4335_V0105.0467.hcd BCM4335
I/bt_hwcfg( 6666): patch(org) : bcm4335_V0105.0467.hcd
I/bt_hwcfg( 6666): Found patchfile: /vendor/firmware/bcm4335_V0105.0467.hcd
E/bt_hwcfg( 6666): ORG patchram base 0105
E/bt_hwcfg( 6666): ORG patchram minor 0467
,E/bt_hwcfg( 6666): fw ver (org)105.467
E/bt_hwcfg( 6666): Final Patchram is /vendor/firmware/bcm4335_V0105.0467.hcd
I/art     (  349): Explicit concurrent mark sweep GC freed 8739(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 310us total 15.207ms
,I/SELinux ( 7294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7294): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,I/bt_hwcfg( 6666): Axi patch failure or not include AXI patching
,E/SELinux ( 7294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 10.606ms
,I/bt_hwcfg( 6666): bt vendor lib: set UART baud 3000000
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.458ms
,D/TimaKeyStoreProvider( 7294): TimaSignature is unavailable
,D/ActivityThread( 7294): Added TimaKeyStore provider
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7312): MountEmulatedStorage()
,E/Zygote  ( 7312): v2
I/libpersona( 7312): KNOX_SDCARD checking this for 10128
I/libpersona( 7312): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=7312 uid=10128 gids={50128, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/System.out( 7035): Thread-1159(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7035): Thread-1159(ApacheHTTPLog):isShipBuild true
,I/art     (  765): Explicit concurrent mark sweep GC freed 94019(4MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 36MB/52MB, paused 1.836ms total 130.743ms
,I/SELinux ( 7312): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7312): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,I/System.out( 7035): Thread-1159(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/SELinux ( 7312): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 7268): creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,I/GHttpClientFactory( 7022): Using the GMSCore's GoogleHttpClient
,E/WifiStateMachine(  765): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/WifiDisplayAdapter(  765): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ResourcesManager( 7262): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 7262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimeService( 7268): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1456909089035
D/        ( 7268): TimeServiceNative: User Time to be set is 1456909089036
D/QC-time-services( 7268): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 7268): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 7268): Lib:time_genoff_operation: pargs->ts_val = 1456909089036
,D/QC-time-services(  368): Daemon: Connection accepted:time_genoff
,D/QC-time-services( 7268): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  368): Daemon:Received base = 2, unit = 1, operation = 0,value = 1456909089036
D/QC-time-services(  368): Daemon:genoff_opr: Base = 2, val = 1456909089036, operation = 0
,D/QC-time-services(  368): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS6/10/70 15:46:39
D/QC-time-services(  368): Daemon:Value read from RTC seconds = 16472799000
D/QC-time-services(  368): Daemon:new time 1456909089036 
D/QC-time-services(  368): Daemon: delta 1440436290036 genoff 1440436290036 
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440436290036 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/TimaKeyStoreProvider( 7312): TimaSignature is unavailable
,D/ActivityThread( 7312): Added TimaKeyStore provider
,D/QC-time-services(  368): Updating the TOD offset
D/QC-time-services(  368): Daemon:genoff_persistent_update: Writing genoff = 1440436290036 to memory
D/QC-time-services(  368): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  368): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  368): Daemon:Update to modem bit set
D/QC-time-services(  368): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  368): Daemon: Base = 2, Value being sent to MODEM = 1124471490036
,E/QC-time-services( 7268): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/BatteryService(  765): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4290, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  765): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  765): stay LED for fully charged
E/QC-time-services(  368): Daemon: Time-services: Waiting to acceptconnection
,I/qtaguid ( 7035): Tagging socket 53 with tag ff44265f00000000{4282656351,0} uid -1, pid: 7035, getuid(): 10209
,D/ResourcesManager( 7294): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  765): Killing 5483:sstream.app/u0a25 (adj 15): bgCount ##41
,D/ResourcesManager( 7312): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/comdaemonstockapp( 3401): [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
D/comdaemonstockapp( 3401): [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
,D/comdaemonstockapp( 3401): [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,D/comdaemonstockapp( 3401): [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
,I/MotionRecognitionService(  765): Plugged
I/MotionRecognitionService(  765): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
I/qtaguid ( 7035): Tagging socket 54 with tag 0{0,0} uid -1, pid: 7035, getuid(): 10209
,D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/HeadsetService( 6666): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 6666): Disconnected process message: 10
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 3401): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3401): [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
D/comsamsunglog( 3401): [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3401): [MSC_Accu_Daemon]>>> ====================================================================================================================
D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/daemonapp( 3401): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3401): [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,E/QC-time-services(  368): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,I/rmt_storage(  290): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
I/rmt_storage(  290): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  290): wakelock acquired: 1, error no: 42
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,I/CalendarProvider2( 7262): CalendarProvider2.onCreate() called
,I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  290): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 0
I/rmt_storage(  290): 
,I/rmt_storage(  290): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,I/dhcpcd  ( 6888): wlan0: sending IPv6 Router Solicitation
,I/CheckinService( 3838): Checkin interval check for package: unspecified last checkin: 1456600421639 min interval config: 0 actual interval: 308667590
,D/ChimeraCfgMgr( 3838): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3838): Module APK com.google.android.play.games already loaded
,W/ActivityManager(  765): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/GamesSyncServiceMain( 3838): Found unexpected GCM tag when scheduling; aborting
W/GamesSyncServiceMain( 3838): Failed to execute periodic sync, missing client context - aborting
,I/bt_hwcfg( 6666): bt vendor lib: set UART baud 115200
,I/bt_hwcfg( 6666): FW Download delta = 502527
D/bt_hwcfg( 6666): Settlement delay -- 100 ms
I/bt_hwcfg( 6666): Setting fw settlement delay to 100 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  266): id=12 Removed Uoast (8/9)
,I/SurfaceFlinger(  266): id=12 Removed Uoast (-2/9)
,D/PowerManagerService(  765): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 765) eventTime = 270336
,D/PowerManagerService(  765): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765 (0x0)
,D/PowerManagerService(  765): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=765, ws=WorkSource{10067}) (elapsedTime=3480)
,I/ActivityManager(  765): Killing 5531:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_hwcfg( 6666): bt vendor lib: set UART baud 3000000
,W/GAV2    ( 7312): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/bt_hwcfg( 6666): vendor lib fwcfg completed
,I/        ( 6666): BTE_InitTraceLevels -- TRC_HCI
I/        ( 6666): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 6666): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 6666): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 6666): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 6666): BTE_InitTraceLevels -- TRC_A2D
I/        ( 6666): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 6666): BTE_InitTraceLevels -- TRC_BTM
I/        ( 6666): BTE_InitTraceLevels -- TRC_GAP
I/        ( 6666): BTE_InitTraceLevels -- TRC_PAN
I/        ( 6666): BTE_InitTraceLevels -- TRC_SAP
I/        ( 6666): BTE_InitTraceLevels -- TRC_SDP
I/        ( 6666): BTE_InitTraceLevels -- TRC_GATT
I/        ( 6666): BTE_InitTraceLevels -- TRC_SMP
I/        ( 6666): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 6666): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 6666): BTE_InitTraceLevels -- TRC_PROTOCOL
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/DefaultRequestDirector( 7035): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 7035): Untagging socket 54
,I/System.out( 7035): Thread-1169 calls detatch()
,E/Volley  ( 7035): [1169] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,I/qtaguid ( 7035): Tagging socket 54 with tag 0{0,0} uid -1, pid: 7035, getuid(): 10209
,I/qtaguid ( 7035): Tagging socket 65 with tag 0{0,0} uid -1, pid: 7035, getuid(): 10209
,E/Zygote  ( 7366): MountEmulatedStorage()
E/Zygote  ( 7366): v2
I/libpersona( 7366): KNOX_SDCARD checking this for 1000
I/libpersona( 7366): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7366 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/DefaultRequestDirector( 7035): Authentication error: Unable to respond to any of these challenges: {bearer=WWW-Authenticate: Bearer realm="https://accounts.google.com/"}
,I/qtaguid ( 7035): Untagging socket 54
,I/System.out( 7035): Thread-1169 calls detatch()
E/Volley  ( 7035): [1169] abz.a: Unexpected response code 401 for https://www.googleapis.com/youtubei/v1/account/get_setting_categories?key=AIzaSyA8eiZmM1FaDVjRy-df2KTyQ_vz_yYM39w
,E/YouTube ( 7035): apps.youtube.app.task.YouTubeNetworkTaskService.a:124 Failed to fetch settings
E/YouTube ( 7035): gss: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 7035): 	at gsl.a(SourceFile:102)
E/YouTube ( 7035): 	at gsm.b(SourceFile:158)
E/YouTube ( 7035): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:4046)
E/YouTube ( 7035): 	at com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService.a(SourceFile:54)
E/YouTube ( 7035): 	at dyr.run(Unknown Source)
E/YouTube ( 7035): Caused by: java.util.concurrent.ExecutionException: aaw
E/YouTube ( 7035): 	at acv.a(SourceFile:117)
E/YouTube ( 7035): 	at acv.get(SourceFile:88)
E/YouTube ( 7035): 	at hoz.get(SourceFile:69)
E/YouTube ( 7035): 	at gsl.a(SourceFile:98)
E/YouTube ( 7035): 	... 4 more
E/YouTube ( 7035): Caused by: aaw
E/YouTube ( 7035): 	at abz.a(SourceFile:159)
E/YouTube ( 7035): 	at hoh.a(SourceFile:72)
E/YouTube ( 7035): 	at abf.run(SourceFile:112)
,I/SELinux ( 7366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7366): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7366): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7366): TimaSignature is unavailable
,D/ActivityThread( 7366): Added TimaKeyStore provider
I/qtaguid ( 7035): Untagging socket 53
,I/System.out( 7035): Thread-1159 calls detatch()
,W/ActivityManager(  765): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  765): Killing 4606:com.sec.spp.push/u0a43 (adj 15): bgCount ##41
,E/Gmail   ( 7312): Error finding the version of the Email provider.....
E/Gmail   ( 7312): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7312): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 7312): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
E/Gmail   ( 7312): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 7312): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7312): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7312): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 7312): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7312): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7312): getAccountsCursor
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager(  765): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/ResourcesManager( 7366): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/bt-l2cap( 6666): l2c_link_processs_ble_num_bufs 15
,I/ActivityManager(  765): Killing 6145:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,E/bt-btm  ( 6666): BTM_SecRegister:p_cb_info->p_le_callback == 0xaf918b05 
E/bt-btm  ( 6666): BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf918b05 
,W/Gmail   ( 7312): Sync started for account: account:61035162
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7312): Observing account changes for notifications
,I/System.out( 7035): Thread-1179 calls detatch()
,W/ActivityManager(  765): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 7366): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/Gmail   ( 7312): getAccountsCursor
,I/DIAGMON_AGENT( 7366): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 7312): (283) recovered 68 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  765): Killing 5997:com.android.defcontainer/u0a7 (adj 13): bgCount ##41
,W/DriveInitializer( 3838): Awaiting to be initialized
,D/BluetoothAdapterProperties( 6666): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,E/bt-btif ( 6666): Calling BTA_HhEnable
,E/bt-btif ( 6666): btif_storage_get_adapter_property service_mask:0x2120048
,D/BluetoothAdapterProperties( 6666): Address is:E0:DB:10:1F:C9:5E
E/BluetoothServiceJni( 6666): populateRssiValuesNative
I/bluedroid( 6666): getModelRssiValues
,E/BluetoothServiceJni( 6666): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 6666): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 6666): Name is: Note3-1
,D/SettingsProvider(  765): name = bluetooth_name
,D/BluetoothAdapterProperties( 6666): Scan Mode:20
,D/BluetoothAdapterProperties( 6666): Discoverable Timeout:120
D/BluetoothAdapterProperties( 6666): LE Address is:E0:B7:20:3E:93:BC
E/bt-btif ( 6666): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,D/bt_vendor( 6666): op for 2
D/bt_vendor( 6666): op for 6
D/bt_vendor( 6666): op for 7
,D/bt_upio ( 6666): proc btwrite assertion
E/bt-btif ( 6666): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 6666): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 6666): btif_sock_init: !vhci_init
D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/IOP_DB_BT( 6666): db_open: file /etc/bluetooth/iop_bt.db
D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/IOP_DB_BT( 6666): db_open: db_open : handle 3013795856l, read 14063 bytes onto local cache
,D/IOP_DB_BT( 6666): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 6666): db_query: result 1
I/        ( 6666): iop_db_open: iop_db_open status 0
,W/DriveInitializer( 3838): Background init thread started
,D/bte_conf( 6666): Device ID record 1 : primary
,D/bte_conf( 6666):   vendorId            = 0075
D/bte_conf( 6666):   vendorIdSource      = 0001
D/bte_conf( 6666):   product             = 0100
D/bte_conf( 6666):   version             = 0200
D/bte_conf( 6666):   clientExecutableURL = 
D/bte_conf( 6666):   serviceDescription  = 
,D/bte_conf( 6666):   documentationURL    = 
D/bte_conf( 6666): bte_load_did_conf no section named DID2.
,D/BluetoothPanServiceJni( 6666): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 6666): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 6666): ScanMode =  20
D/BluetoothAdapterProperties( 6666): State =  11
,D/SecContentProvider(  765): uri = 3 selection = isDiscoverableEnabled
D/BluetoothAdapterProperties( 6666): Setting state to 12
I/BluetoothAdapterState( 6666): Bluetooth adapter state changed: 11-> 12
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,E/bt_h4   ( 6666): vendor lib postload completed
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
D/BluetoothAdapterProperties( 6666): Scan Mode:21
D/BluetoothAdapterProperties( 6666): Discoverable Timeout:120
,D/SettingsProvider(  765): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 1002
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
,D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
,D/bt_upio ( 6666): BT_WAKE is asserted already
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/BluetoothAdapterService( 6666): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 6666): updateAdapterState state is 12
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,E/File    ( 7312): fail readDirectory() errno=2
W/ContextImpl( 3838): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,I/Gmail   ( 7312): notifyAccountChanged
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/BluetoothAdapterService( 6666): Autoconnection is available 
D/BluetoothAdapterService( 6666): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 6666): starting service from this receiver
,D/BluetoothA2dp(  765): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 2935): onBluetoothStateChange: up=true
,I/BluetoothAdapterState( 6666): Entering On State from state = 11
,D/BluetoothA2dp( 6666): onBluetoothStateChange: up=true
,I/Gmail   ( 7312): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,W/InputMethodManagerService(  765): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  765): [BT Setting State] State =12
,I/InputMethodManagerService(  765): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,D/BluetoothManager( 6868): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,I/SamsungIME( 1686): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1191):  onBluetoothStateChange:
,I/Gmail   ( 7312): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/BluetoothTile( 1191):  onBluetoothPairedDevicesChanged:
D/BluetoothTile( 1191): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothHeadset( 1404): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@37d8a4b5, true
,D/BluetoothTile( 1191):  handleUpdatestate:false name:null
,I/BluetoothPbapService( 6666): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/STATUSBAR-QSTileView( 1191): onStateChanged: Bluetooth
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothHeadset( 1404): registerMessageListener
,I/Gmail   ( 7312): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/StatusBarManagerService(  765): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,D/HeadsetService( 6666): registerMessageListener
,D/HeadsetService( 6666): registerMessageListener
D/HeadsetStateMachine( 6666): Disconnected process message: 70
,D/HeadsetStateMachine( 6666): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@103294ab
,I/BluetoothPbapService( 6666): Handler(): got msg=1
D/StatusBarManagerService(  765): setIconVisibility slot=bluetooth visible=true
,D/BluetoothManagerService(  765): Broadcasting onBluetoothServiceUp() to 0 receivers.
I/Telecom ( 1404): BluetoothPhoneService: updateHeadsetWithCallState
D/SecContentProvider(  765): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
I/Telecom ( 1404): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,I/Gmail   ( 7312): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneStatusBar( 1191): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,D/HeadsetStateMachine( 6666): Disconnected process message: 9
,D/HeadsetStateMachine( 6666): mNumActive: 0 mNumHeld: 0 mCallState: 6
,V/BluetoothPbapService( 6666): PBAP Service initSocket try: 0
,D/audio_hw_primary(  309): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  309): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  309): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  309): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  309): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  309): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  309): adev_set_parameters: exit
E/HeadsetStateMachine( 6666): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/BluetoothAdapter( 6666): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 6666): set MAP SDP message type : 1
,W/BluetoothAdapter( 6666): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6666): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 6666): bindListen(), new LocalSocket 
D/BluetoothSocket( 6666): bindListen(), new LocalSocket.getInputStream() 
D/bt_vendor( 6666): op for 7
D/BluetoothSocket( 6666): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36179708
D/bt_upio ( 6666): BT_WAKE is asserted already
D/BluetoothSocket( 6666): channel: 5
,D/BluetoothSocket( 6666): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 6666): bindListen(), new LocalSocket 
D/BluetoothSocket( 6666): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6666): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@103feea1
D/BluetoothSocket( 6666): channel: 19
D/BluetoothPbapService( 6666): PBAP Socket is BluetoothServerSocket
,D/bt_vendor( 6666): op for 7
D/bt_upio ( 6666): BT_WAKE is asserted already
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7312): notifyAccountChanged
,W/DriveInitializer( 3838): Background init thread ended
,I/DIAGMON_AGENT( 7366): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7366): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7366): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7366): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1749): Tagging socket 55 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
I/qtaguid ( 1749): Tagging socket 66 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,D/ResourcesManager( 7312): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 7312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7312): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1749): Tagging socket 79 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,I/Gmail   ( 7312): getAccountsCursor
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/qtaguid ( 1749): Tagging socket 82 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,E/SMD     (  302): DCD ON
,V/JNIHelp ( 7312): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/FOTA_Client( 7005): [lIIIIlIlIlIlllllllll(200/lllIlIlIIIllIIlIllIl)] Polling time is not vaild
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaUpdaterReceiver(112/onReceive)] Polling time is already passed. Start device init Immediately
,I/KLMS-2.4.511: ( 7062): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7062): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1456909090212
,I/KLMS-2.4.511: ( 7062): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7062): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7062): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7062): NetworkChangeOperations(): uploadRequestLog().START 
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(104/handleMessage)] Update State: Check condition to decide next state: 1
,I/KLMS-2.4.511: ( 7062): StateImplV2(): networkChangeListener().END
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(121/handleMessage)] Update State: Initialize polling update: 1
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7005): [lllllllIlllIIlllIlIl(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,W/ActivityThread( 7312): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7312): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bcee67b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7312): Installed default security provider GmsCore_OpenSSL
,E/Zygote  ( 7422): MountEmulatedStorage()
E/Zygote  ( 7422): v2
I/libpersona( 7422): KNOX_SDCARD checking this for 10036
I/libpersona( 7422): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7422 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/SELinux ( 7422): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7422): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7422): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 7422): TimaSignature is unavailable
,D/ActivityThread( 7422): Added TimaKeyStore provider
,E/Zygote  ( 7435): MountEmulatedStorage()
E/Zygote  ( 7435): v2
I/libpersona( 7435): KNOX_SDCARD checking this for 1000
I/libpersona( 7435): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.wssyncmldm for content provider com.wssyncmldm/.db.sql.XDMDbContentProvider: pid=7435 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7435): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7435): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7435): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7435): TimaSignature is unavailable
,D/ActivityThread( 7435): Added TimaKeyStore provider
,D/ResourcesManager( 7422): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7422): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7422): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7422): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/art     (  765): Explicit concurrent mark sweep GC freed 26330(1464KB) AllocSpace objects, 2(32KB) LOS objects, 30% free, 36MB/52MB, paused 1.384ms total 86.670ms
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7435): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7096): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA    ( 7435): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,I/ActivityManager(  765): Killing 6230:com.sec.android.app.soundalive/u0a64 (adj 13): bgCount ##41
,I/FOTA_Client( 7005): [lIlIIIlllIlIlIlIIIll(31/llIIIIlllllIIllIIllI)] Request Network Connection
,I/System.out( 7312): Thread-1179(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/FOTA_Client( 7005): [lllllllIlllIIlllIlIl(88/llllIIIllIlIIIIllllI)] WiFi Network is connected
,I/DBG_POLICYDM( 3232): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_POLICYDM( 3232): [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 3232): [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 3232): [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 3232): [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaInitUpdateService(352/llllIIIllIlIIIIllllI)] Request NetActionGetPolling
,I/DBG_POLICYDM( 3232): [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 3232): [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/System.out( 7312): Thread-1179(ApacheHTTPLog):isShipBuild true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 7312): Thread-1179(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/DBG_POLICYDM( 3232): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/qtaguid ( 7312): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 7312, getuid(): 10128
,W/art     ( 5645): Attempt to remove local handle scope entry from IRT, ignoring
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(363/IllIlIIIIlIIlIIIllIl)] Voice : true
,E/Zygote  ( 7466): MountEmulatedStorage()
E/Zygote  ( 7466): v2
I/libpersona( 7466): KNOX_SDCARD checking this for 10043
I/libpersona( 7466): KNOX_SDCARD not a persona
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(364/IllIlIIIIlIIlIIIllIl)] SMS : true
,I/DBG_POLICYDM( 3232): [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 3232): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(82/llIIIIlllllIIllIIllI)] Server time is zero
,I/ActivityManager(  765): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7466 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(365/IllIlIIIIlIIlIIIllIl)] isDataOnly : false
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(111/llllIIIllIlIIIIllllI)] Request ServerTime
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,I/System.out( 7005): Thread-1108(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7005): Thread-1108(ApacheHTTPLog):isShipBuild true
,I/SELinux ( 7466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7466): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7466): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/System.out( 7005): Thread-1108(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/DBG_POLICYDM( 3232): [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 7
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMApplication(44/onCreate)] myUserId : 0
,D/TimaKeyStoreProvider( 7466): TimaSignature is unavailable
,D/ActivityThread( 7466): Added TimaKeyStore provider
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
,I/qtaguid ( 7312): Tagging socket 63 with tag 1010000000000000{269484032,0} uid -1, pid: 7312, getuid(): 10128
,I/CalendarProvider2( 7262): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 5050:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##41
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,I/ActivityManager(  765): Killing 5596:com.sec.chaton/u0a102 (adj 13): bgCount ##41
,I/DBG_POLICYDM( 3232): [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,I/DBG_POLICYDM( 3232): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2712/llIlIIIIlIIIIIlIlIII)] xdbsqlGetDownloadPostponeStatus : 0
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 3232): [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,D/ResourcesManager( 7466): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/DBG_POLICYDM( 3232): [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 3232): [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 3232): [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/03/02/15:29:46
I/DBG_POLICYDM( 3232): [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 3232): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/03/02/09:58:10
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 3232): [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1504/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMApplication(107/onCreate)] DMApplication NOT Start !
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 3232): [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,E/SPPClientService( 7466): ============PushLog. commonIsShipBuild. stop!
,I/System.out( 7005): AsyncTask #1 calls detatch()
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,E/SPPClientService( 7466): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 7466): PushLog.txt file is not deleted.
,D/SPPClientService( 7466): PushLog.txt file is not deleted.
,D/SPPClientService( 7466): ============PushLog. stop!
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.time.llIIIIlllllIIllIIllI(139/llllIIIllIlIIIIllllI)] Receive result: success in ServerTime
,I/DBG_POLICYDM( 3232): [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,E/SPPClientService( 7466): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.http.RestClient(264/llIIIIlllllIIllIIllI)] =====================================================================
,I/dex2oat ( 7483): ----------------------------------------------------
I/dex2oat ( 7483): <SS>: S T A R T I N G . . .
I/dex2oat ( 7483): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 7483): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/cache/ads-1088130079.jar --oat-fd=104 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/cache/ads-1088130079.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/FOTA_Client( 7005): [com.sec.android.fota.osp.http.RestClient(277/llIIIIlllllIIllIIllI)] =====================================================================
,I/SA      ( 6170): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOI6 PSS = 5.701607447389803  ]
,I/SA      ( 6170): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6170): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 3232): [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/SA      ( 6170): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/SA      ( 6170): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6170): [OR] == isSIMCardReady false ==
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6170): [SCU] == networkStateCheck == true
,I/SA      ( 6170): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6170): isChinaCountryCode : false
I/SA      ( 6170): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6170): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/SA      ( 6170): [OR] GetMyCountryZoneTask
,I/SA      ( 6170): [OR] onReceive END
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6268:com.wsomacp/u0a29 (adj 13): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dex2oat ( 7483): dex2oat took 89.821ms (threads: 4)
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6170): [SRS] prepareGetMyCountryZone
,I/SA      ( 6170): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6170): [SSP] query invoked
,I/SA      ( 6170): [TPMU] GetMccFromDB : null
,I/SA      ( 6170): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6170): [TPM] isNoProxy(default) : true
,E/File    ( 6170): fail readDirectory() errno=2
,E/Zygote  ( 7503): MountEmulatedStorage()
I/libpersona( 7503): KNOX_SDCARD checking this for 10074
E/Zygote  ( 7503): v2
I/libpersona( 7503): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7503 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7503): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7503): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7503): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7503): TimaSignature is unavailable
,D/ActivityThread( 7503): Added TimaKeyStore provider
,I/art     ( 3838): Explicit concurrent mark sweep GC freed 45447(3MB) AllocSpace objects, 30(480KB) LOS objects, 39% free, 22MB/38MB, paused 760us total 57.611ms
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7503): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/art     ( 1749): Explicit concurrent mark sweep GC freed 111343(6MB) AllocSpace objects, 45(1271KB) LOS objects, 40% free, 22MB/37MB, paused 717us total 53.522ms
,I/System.out( 7005): AsyncTask #1 calls detatch()
,I/FOTA_Client( 7005): [IlIIlIIlIllllIlllIII(97/llIIIIlllllIIllIIllI)] result is success
,I/FOTA_Client( 7005): [IIIlIllIlIIIIIlIIIll(78/llIIIIlllllIIllIIllI)] Response Network Connection
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.llIIIIlllllIIllIIllI(304/llIIIIlllllIIllIIllI)] Receive result: success in NetActionGetPolling
,D/SettingsProvider(  765): name = FOTA_CLIENT_HEARTBEAT_PERIOD
,D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 10014
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  765): ret = -1
,D/SettingsProvider(  765): name = FOTA_CLIENT_HEARTBEAT_ADD
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 10014
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=10014
,I/FOTA_Client( 7005): [lIIIIlIlIlIlllllllll(157/llllIIIllIlIIIIllllI)] Calculate next polling time
,D/SettingsProvider(  765): name = FOTA_CLIENT_POLLING_TIME
D/SettingsProvider(  765): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  765): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  765): selectionArgs: false
D/SettingsProvider(  765): selectionArgs: 10014
D/SecContentProvider(  765): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  765): ret = -1
,I/PhenotypeFlagCommitter( 1749): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/BackupManagerService(  765): dataChanged but no participant pkg='com.android.providers.settings' uid=10014
,I/FOTA_Client( 7005): [IlIIlIIlIllllIlllIII(194/llIIllllIIlllIIIIlll)] Find Firmware version in Version List
,I/GoogleURLConnFactory( 1749): Using platform SSLCertificateSocketFactory
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(131/handleMessage)] Update State: Need to polling update: 1
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.FotaInitUpdateService(359/lllIlIlIIIllIIlIllIl)] request Polling
,I/FOTA_Client( 7005): [com.sec.android.fotaclient.llllIIIllIlIIIIllllI(137/handleMessage)] Update State: Finish update init: 1
,I/ActivityManager(  765): Killing 6251:com.google.android.apps.docs/u0a112 (adj 13): bgCount ##41
,I/sCloudBackupApp( 7503): sCloudBackupApp Version Info : 3.13.7.KK_APP
,I/SCloudBackupReceiver( 7503): Other Intent
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,E/Zygote  ( 7524): MountEmulatedStorage()
I/libpersona( 7524): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7524): v2
I/libpersona( 7524): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7524 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/bt_vendor( 6666): op for 7
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6539): 
,I/SELinux ( 7524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7524): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7524): TimaSignature is unavailable
,D/ActivityThread( 7524): Added TimaKeyStore provider
,I/ActivityManager(  765): Killing 6299:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##41
,D/ResourcesManager( 7524): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7524): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6114): mConnectivityHandler : connected
,I/KnoxUsageLogPro( 7524): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KnoxUsageLogPro( 7524): premStatus:2
,W/PCWCLIENTTRACE_AccountUtil( 6114): [hasSamungAccount] - No Samsung Account
,I/KnoxUsageLogPro( 7524): isEulaShown : false
I/KnoxUsageLogPro( 7524): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6114): [GetString-S]
,E/art     ( 6114): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6114): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6114): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 6114): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6114): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6114): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6114): [ensureRegistration] - No Samsung account
,E/Zygote  ( 7541): MountEmulatedStorage()
I/libpersona( 7541): KNOX_SDCARD checking this for 10102
E/Zygote  ( 7541): v2
I/libpersona( 7541): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.NetStateReceiver: pid=7541 uid=10102 gids={50102, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7541): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7541): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7541): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7541): TimaSignature is unavailable
,D/ActivityThread( 7541): Added TimaKeyStore provider
,I/qtaguid ( 7312): Untagging socket 59
,I/System.out( 7312): SyncAdapterThread-1 calls detatch()
,D/ResourcesManager( 7541): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/ActivityManager(  765): Killing 6320:com.samsung.android.app.watchmanagerstub/u0a126 (adj 13): bgCount ##41
,W/ResourcesManager( 7541): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7312): Explicit concurrent mark sweep GC freed 40689(2MB) AllocSpace objects, 12(215KB) LOS objects, 24% free, 19MB/25MB, paused 774us total 69.289ms
,D/bt_upio ( 6666): ..proc_btwrite_timeout..
,D/PushModule( 7541): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 7541): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 7541): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ChatON  ( 7541): [1][isApplicationInstalled] com.android.mms was installed
,I/Gmail   ( 7312): getStartSyncRequest: handledServerOpId: 17665, upperFetchedConvoId: 0, lowerFetchedConvoId: 0, ackedClientOp: 0
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 3838): (HTTPLog)-Static: isShipBuild true
I/System.out( 3838): (HTTPLog)-Thread-657-954253438: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager( 7312): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ContextImpl( 7541): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  765): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,W/ResourcesManager( 7312): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7312): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/System.out( 3838): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 3838): Tagging socket 97 with tag 1000010400000000{268435716,0} uid -1, pid: 3838, getuid(): 10015
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7312): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 7312, getuid(): 10128
,D/ChatON  ( 7541): [1][a] ChatONV isn't installed.
,D/ChatON  ( 7541): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7564): MountEmulatedStorage()
E/Zygote  ( 7564): v2
I/libpersona( 7564): KNOX_SDCARD checking this for 10104
I/libpersona( 7564): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7564 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SA      ( 6170): [RC New] Execute method=[GET] start
,I/SELinux ( 7564): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7564): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7564): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6335:com.samsung.helphub/1000 (adj 13): bgCount ##41
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/ActivityManager(  765): Killing 6371:com.samsung.android.snote:provider/u0a168 (adj 13): bgCount ##41
,D/TimaKeyStoreProvider( 7564): TimaSignature is unavailable
,D/ActivityThread( 7564): Added TimaKeyStore provider
,I/SA      ( 6170): [RC New] Security=[true]
,I/System.out( 6170): Thread-1001(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6170): Thread-1001(ApacheHTTPLog):isShipBuild true
,I/System.out( 6170): Thread-1001(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ResourcesManager( 7564): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6539): 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7312): Untagging socket 59
I/System.out( 7312): SyncAdapterThread-1 calls detatch()
,I/Gmail   ( 7312): StartSyncInfoProto: Personal inbox enabled: true
,I/qtaguid ( 3838): Untagging socket 97
,I/qtaguid ( 1749): Tagging socket 90 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,I/Gmail   ( 7312): StartSyncInfoProto: Personal inbox android config: com.google.c.c.a.a@2abda9f3
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:n  (  765): SIOP:: AP = 390, PST = 300, CUR = 450
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 6539): 
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/jxcore-log( 6539): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6539): 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/io.jxcore.node.ConnectivityInfo( 6539): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 6539):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6539):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6539):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6539):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 6539):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6539):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6539):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6539):     - force notify: true
,D/io.jxcore.node.JXcoreExtension( 6539): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 6539): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6539): 
,E/Zygote  ( 7587): MountEmulatedStorage()
,E/Zygote  ( 7587): v2
I/libpersona( 7587): KNOX_SDCARD checking this for 10131
I/libpersona( 7587): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7587 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 7587): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7587): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7587): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7587): TimaSignature is unavailable
,D/ActivityThread( 7587): Added TimaKeyStore provider
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ResourcesManager( 7587): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 7587): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,I/Gmail   ( 7312): checkLabelsSets changed the label sets to: included([^^out, ^r]), partial([^f]), all([^b, userlabel:90242001, userlabel:93982, userlabel:2914615, userlabel:90242029, userlabel:2914456, ^iim, ^k, ^p_aunsub, userlabel:3025, ^sq_ig_i_promo, userlabel:-1492276993, ^smartlabel_notification, userlabel:-1508083783, userlabel:382548592, ^imn, userlabel:90241997, userlabel:1680828287, ^all, userlabel:94101, ^imi, ^f, userlabel:-1492383895, userlabel:94076, userlabel:-1492276994, userlabel:-1492276990, userlabel:3026, userlabel:-1492276991, ^u, ^t, ^s, ^smartlabel_group, userlabel:-812318908, ^smartlabel_personal, ^smartlabel_social, ^p_mtunsub, userlabel:2914593, ^sq_ig_i_personal, ^g, ^punsub, ^r, ^i, ^smartlabel_promo, ^io_im, userlabel:2896756, userlabel:614875005, userlabel:-1492276992, userlabel:90242014, userlabel:-1711782184, userlabel:93692, userlabel:-244132349, ^sq_ig_i_social, userlabel:3011, userlabel:90241971, userlabel:1123230114, userlabel:-1497466235])
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6391:com.sec.kidsplat.installer/u0a189 (adj 13): bgCount ##41
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7312): MainSyncRequestProto: lowestBkwdConvoId: 1527679908579377153, highestHandledServerOp: 17665, normalSync: true
,I/PeopleSync( 3838): onPerformSync() [5005f081]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 7312): Tagging socket 59 with tag 1010000000000000{269484032,0} uid -1, pid: 7312, getuid(): 10128
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ResourcesManager( 7587): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/Babel   ( 7587): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 7587): MmsConfig.loadMmsSettings
I/Babel   ( 7587): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
I/Babel   ( 7587): MmsConfig.loadFromDatabase
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Babel   ( 7587): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 7587): MmsConfig.loadFromResources
,E/Babel   ( 7587): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 7587): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 7587): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,I/SA      ( 6170): [RC New] [v2liruge] api execute + 738
I/SA      ( 6170): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6170): AsyncTask #1 calls detatch()
,I/SA      ( 6170): [TPMU] getNetworkMcc : 
,I/Babel_StickerModule( 7587): App launched.
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/SA      ( 6170): [SCU] saveMccToPreferece Start
I/SA      ( 6170): [SCU] RegionMCC : 260
I/SA      ( 6170): [SSP] query invoked
,I/SA      ( 6170): [TPMU] GetMccFromDB : null
,I/SA      ( 6170): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6170): [SCU] saveMccToPreferece End
,I/SA      ( 6170): [RC New] executeRequest [v2liruge] end. 841
,I/SA      ( 6170): [RC New] Execute end
,I/SA      ( 6170): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6170): [OR] GetMyCountryZoneTask Success
,E/Zygote  ( 7614): MountEmulatedStorage()
I/libpersona( 7614): KNOX_SDCARD checking this for 10146
E/Zygote  ( 7614): v2
I/libpersona( 7614): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7614 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PeopleSync( 3838): Setting subscription: result=true [5005f081]
,I/PeopleSync( 3838): Starting sync, feed=null [5005f081]
,I/art     (  349): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 295us total 25.883ms
,I/SELinux ( 7614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7614): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 7614): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/QCamera2Factory(  309): getCameraInfo: E, camera_id = 0
W/QCamera2HWI(  309): __dbg: info->orientation : 90 rc = 0
W/QCamera2Factory(  309): getCameraInfo: X
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 12.949ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 9.784ms
,W/QCamera2Factory(  309): getCameraInfo: E, camera_id = 1
W/QCamera2HWI(  309): __dbg: info->orientation : 90 rc = 0
W/QCamera2HWI(  309): __dbg: info->orientation : 270 rc = 0
W/QCamera2Factory(  309): getCameraInfo: X
,D/TimaKeyStoreProvider( 7614): TimaSignature is unavailable
,D/ActivityThread( 7614): Added TimaKeyStore provider
,W/AudioCapabilities( 7587): Unsupported mime audio/evrc
,W/AudioCapabilities( 7587): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7587): Unrecognized profile 2130706433 for video/avc
,D/ResourcesManager( 7614): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/AudioCapabilities( 7587): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 7587): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 7587): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7587): Unsupported mime audio/x-ima
,W/AudioCapabilities( 7587): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7587): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7587): Unsupported mime audio/evrc
,W/VideoCapabilities( 7587): Unsupported mime video/wvc1
,W/VideoCapabilities( 7587): Unsupported mime video/x-ms-wmv
,I/qtaguid ( 7312): Untagging socket 59
,W/VideoCapabilities( 7587): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 7587): Unsupported mime video/wvc1
,I/System.out( 7312): SyncAdapterThread-1 calls detatch()
,W/VideoCapabilities( 7587): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 7587): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 7587): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 7587): Unsupported mime video/mp43
,W/VideoCapabilities( 7587): Unsupported mime video/sorenson
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 7587): Unsupported mime video/mp4v-esdp
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD ON
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,I/VideoCapabilities( 7587): Unsupported profile 4 for video/mp4v-es
,I/dhcpcd  ( 6888): wlan0: sending IPv6 Router Solicitation
,I/Gmail   ( 7312): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 17852, normalSync: true
,I/Gmail   ( 7312): lowestBackward conversation id 0
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ActivityManager(  765): Killing 6416:com.sec.android.app.samsungapps/u0a45 (adj 13): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/Gmail   ( 7312): notifyAccountChanged
,I/ServiceManager(  362): Waiting for service AtCmdFwd...
,I/PeopleSync( 3838): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,I/Gmail   ( 7312): getAccountsCursor
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7312): notifyAccountChanged
,W/Gmail   ( 7312): Sync complete for account: account:61035162
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 7312): getAccountsCursor
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  765): Killing 5667:com.android.vending/u0a33 (adj 13): bgCount ##41
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7614): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  765): Explicit concurrent mark sweep GC freed 39615(2MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.398ms total 91.439ms
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1749): Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1749): Tagging socket 93 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,I/System.out( 1719): Thread-148(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 1719): Thread-148(ApacheHTTPLog):isShipBuild true
,I/System.out( 1719): Thread-148(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1719): Tagging socket 35 with tag 1244000400000000{306446340,0} uid -1, pid: 1719, getuid(): 10015
,I/WebViewFactory( 7614): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ResourcesManager( 7614): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/LibraryLoader( 7614): Time to load native libraries: 5 ms (timestamps 4771-4776)
,I/LibraryLoader( 7614): Expected native library version number "",actual native library version number ""
,I/qtaguid ( 1719): Tagging socket 41 with tag 1244000400000000{306446340,0} uid -1, pid: 1719, getuid(): 10015
,V/WebViewChromiumFactoryProvider( 7614): Binding Chromium to main looper Looper (main, tid 1) {1c70c211}
,I/LibraryLoader( 7614): Expected native library version number "",actual native library version number ""
,I/chromium( 7614): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1749): Tagging socket 94 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,I/BrowserStartupController( 7614): Initializing chromium process, singleProcess=true
,W/art     ( 7614): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7614): ApplicationContext is null in ApplicationStatus
,W/chromium( 7614): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 7614): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 7614): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 7614): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7614): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7614): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7614): Local Branch: mybranch5813579
I/Adreno-EGL( 7614): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7614): Local Patches: NONE
I/Adreno-EGL( 7614): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,I/qtaguid ( 1749): Tagging socket 97 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,W/AudioManagerAndroid( 7614): Requires BLUETOOTH permission
,I/NSApplication( 7614): Starting up...
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7678): MountEmulatedStorage()
E/Zygote  ( 7678): v2
I/libpersona( 7678): KNOX_SDCARD checking this for 10158
I/libpersona( 7678): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 3232): [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,I/ActivityManager(  765): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7678 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3232): [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/SELinux ( 7678): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7678): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7678): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 3232): [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 3232): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,D/TimaKeyStoreProvider( 7678): TimaSignature is unavailable
,D/ActivityThread( 7678): Added TimaKeyStore provider
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1719): Untagging socket 35
I/System.out( 1719): GDataFeedFetcher calls detatch()
,I/DBG_POLICYDM( 3232): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ResourcesManager( 7678): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7678): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7678): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7678): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/Mms/Contact( 6190): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 6190): performUpdate:widgetCount=0
,D/ContactProvider( 5362): getAllContactInfoList Start
,I/qtaguid ( 1719): Tagging socket 35 with tag 1144000400000000{289669124,0} uid -1, pid: 1719, getuid(): 10015
,I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
,D/QuickConnect( 7678): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/ContactProvider( 5362): getAllContactInfoList End
,I/System.out( 3838): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/QuickConnect( 7678): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/qtaguid ( 3838): Tagging socket 108 with tag 1000150000000000{268440832,0} uid 10015, pid: 3838, getuid(): 10015
,I/QuickConnect( 7678): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/RCPManagerService(  765): exchangeData() failure , invalid userId
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6620): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6620): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6620): StateMachine : Current State = 1
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 6620): StateMachine : Changed Current State = 1
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6214:com.sec.android.provider.badge/u0a92 (adj 13): bgCount ##41
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 3838): Tagging socket 111 with tag 1000150000000000{268440832,0} uid 10015, pid: 3838, getuid(): 10015
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7697): MountEmulatedStorage()
,E/Zygote  ( 7697): v2
I/libpersona( 7697): KNOX_SDCARD checking this for 10200
I/libpersona( 7697): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7697 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7697): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7697): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7697): TimaSignature is unavailable
,D/ActivityThread( 7697): Added TimaKeyStore provider
,I/qtaguid ( 1719): Untagging socket 35
,I/System.out( 1719): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 6190): sContactsObserver.onChange(),selfUpdate=false
,E/SQLiteLog( 1607): (284) automatic index on sqlite_sq_AD4EA1F0(STAT_DATA_ID)
,E/SQLiteLog( 1607): (284) automatic index on sqlite_sq_AD4EA380(STAT_DATA_ID)
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ContactProvider( 5362): getAllContactInfoList Start
,D/ResourcesManager( 7697): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,D/ContactProvider( 5362): getAllContactInfoList End
,I/Icing   ( 3838): Indexing E78F5CBEB57D2B0FC1D839F8E1139AA0E96FD1EC from com.google.android.gm
,I/ActivityManager(  765): Killing 6781:com.google.android.apps.maps/u0a140 (adj 13): bgCount ##41
,E/SQLiteLog( 1607): (284) automatic index on sqlite_sq_A1102600(STAT_DATA_ID)
,E/SQLiteLog( 1607): (284) automatic index on sqlite_sq_A1151970(STAT_DATA_ID)
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/iu.SyncManager( 3838): SYNC; picasa accounts
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Icing   ( 3838): Indexing done E78F5CBEB57D2B0FC1D839F8E1139AA0E96FD1EC
,I/qtaguid ( 3838): Untagging socket 108
,W/Atfwd_Sendcmd(  362): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Zygote  ( 7717): MountEmulatedStorage()
,E/Zygote  ( 7717): v2
I/libpersona( 7717): KNOX_SDCARD checking this for 10129
I/libpersona( 7717): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=7717 uid=10129 gids={50129, 9997, 3003} abi=armeabi-v7a
,D/NetworkLogImpl( 3838): Loaded NetworkSpeedPredictor
,I/SELinux ( 7717): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7717): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SELinux ( 7717): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/iu.Environment( 3838): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3838): num queued entries: 0
,I/iu.UploadsManager( 3838): num updated entries: 0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/iu.SyncManager( 3838): NEXT; no task
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 7717): TimaSignature is unavailable
,D/ActivityThread( 7717): Added TimaKeyStore provider
,I/GAV2    ( 7312): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  765): Killing 6827:com.samsung.android.app.FileShareServer/u0a88 (adj 13): bgCount ##41
,D/ResourcesManager( 7717): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 7735): MountEmulatedStorage()
I/ActivityManager(  765): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7735 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 7735): v2
I/libpersona( 7735): KNOX_SDCARD checking this for 10045
I/libpersona( 7735): KNOX_SDCARD not a persona
,I/SELinux ( 7735): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7735): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7735): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/AbstractGoogleClient( 7717): Application name is not set. Call Builder#setApplicationName.
,D/TimaKeyStoreProvider( 7735): TimaSignature is unavailable
,D/ActivityThread( 7735): Added TimaKeyStore provider
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7735): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7735): notifyNetworkActivated
,I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3838): Tagging socket 108 with tag 1000190000000000{268441856,0} uid 10015, pid: 3838, getuid(): 10015
,D/LocationManagerService(  765): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/ContextImpl( 7735): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  765): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 87 with tag 1000120100000000{268440065,0} uid -1, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 1749): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/GCM     ( 1749): GCM config loaded
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 3838): Untagging socket 108
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 86 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7735): AutoUpdateManager:IDLE:execute
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7735): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7735): exit::IDLE
D/InitializeManagerStateMachine( 7735): entry::NETWORK_CHECK
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7735): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7735): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7735): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7735): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7735): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7735): entry::SUCCESS
,D/hcjo    ( 7735): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/hcjo    ( 7735): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7735): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7735): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/InitializeManagerStateMachine( 7735): exit::SUCCESS
D/InitializeManagerStateMachine( 7735): entry::IDLE
,D/LocalBluetoothProfileManager( 1309): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 1309): Adding local HEADSET profile
,E/BluetoothHeadset( 1309): BTStateChangeCB is registed
,E/BluetoothHeadset( 1309): BluetoothHeadset service is binded
,W/ContextImpl( 1309): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,D/Bluetoothsap( 1309): bindService called to Bluetooth SAP Service
,I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 3838): Tagging socket 108 with tag 1000150000000000{268440832,0} uid 10015, pid: 3838, getuid(): 10015
,D/LocalBluetoothProfileManager( 1309): PANU : true
D/LocalBluetoothProfileManager( 1309): Adding local MAP profile
,D/BluetoothMap( 1309): Create BluetoothMap proxy object
,W/LocalBluetoothProfileManager( 1309): Warning: SAP profile was previously added.
,D/LocalBluetoothProfileManager( 1309): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1309): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1309): onReceive
,D/BluetoothA2dp( 1309): Proxy object connected
,D/BluetoothAdapterService( 6666): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@19277fde
D/BtConfig.SecureMode( 6666): isSecureModeOn:false
,D/A2dpProfile( 1309): Bluetooth service connected
,D/HeadsetProfile( 1309): Bluetooth service connected
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7766): MountEmulatedStorage()
E/Zygote  ( 7766): v2
I/libpersona( 7766): KNOX_SDCARD checking this for 10140
I/libpersona( 7766): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7766 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7766): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7766): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,D/Bluetoothsap( 1309): BluetoothSAP Proxy object connected
,E/SELinux ( 7766): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SecContentProvider(  765): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
D/SapProfile( 1309): Bluetooth service connected
D/Bluetoothsap( 1309): getConnectedDevices()
,W/BluetoothAdapter( 6666): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6666): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,D/BluetoothSocket( 6666): bindListen(), new LocalSocket 
D/BluetoothSocket( 6666): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6666): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@fc2ee23
,D/BluetoothInputDevice( 1309): Proxy object connected
,D/HidProfile( 1309): Bluetooth service connected
,D/bt_vendor( 6666): op for 7
D/BluetoothSocket( 6666): channel: 12
,I/BtOppRfcommListener( 6666): Accept thread started.
D/bt_upio ( 6666): proc btwrite assertion
,D/BluetoothPan( 1309): BluetoothPAN Proxy object connected
,D/PanProfile( 1309): Bluetooth service connected
D/TimaKeyStoreProvider( 7766): TimaSignature is unavailable
,D/ActivityThread( 7766): Added TimaKeyStore provider
,D/BluetoothMap( 1309): Proxy object connected
,D/MapProfile( 1309): Bluetooth service connected
D/BluetoothPbap( 1309): Proxy object connected
D/PbapServerProfile( 1309): Bluetooth service connected
,D/ResourcesManager( 7766): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/System.out( 7717): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7717): (HTTPLog)-Static: isShipBuild true
I/System.out( 7717): (HTTPLog)-Thread-1231-730758666: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7717): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7717): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 7717): Tagging socket 28 with tag 1100000000000000{285212672,0} uid -1, pid: 7717, getuid(): 10129
,I/qtaguid ( 3838): Untagging socket 108
,I/PeopleSync( 3838): Sync finished, successful=true, took 1885ms
,I/PeopleContactsSync( 3838): CP2 sync start [5005f081]
,I/PeopleContactsSync( 3838): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 3838): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PeopleContactsSync( 3838): CP2 cleanup done, kept= duration=71 ms
,I/PeopleContactsSync( 3838): ===CP2 sync finished, success=true, time=81,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 3838): ***Sync finished***, duration: 2648 [5005f081]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6811:com.samsung.shareshot/u0a192 (adj 13): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StrictMode( 7766): StrictMode policy violation; ~duration=234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 7766): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 7766): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 7766): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 7766): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 7766): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 7766): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=220 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 7766): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 7766): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 7766): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 7766): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 7766): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): ,	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7766): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7766): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7766): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
D/StrictMode( 7766): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
D/StrictMode( 7766): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
D/StrictMode( 7766): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 7766): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 7766): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7766): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
D/StrictMode( 7766): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 7766): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 7766): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 7766): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
D/StrictMode( 7766): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7766): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7766): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7766): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7766): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7766): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 7766): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 7766): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 7766): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 7766): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 7766): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 7766): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7766): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 7766): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 7766): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 7766): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 7766): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 7766): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 7766): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 7766): 	at com.google.r.k.c(PG:583)
D/StrictMode( 7766): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 7766): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 7766): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 7766): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 7766): 	at com.google.r.e.b(PG:170)
D/StrictMode( 7766): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7766): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7766): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7766): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
D/StrictMode( 7766): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
D/StrictMode( 7766): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
D/StrictMode( 7766): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/StrictMode( 7766): StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 7766): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 7766): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 7766): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 7766): 	at java.io.File.exists(File.java:363)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 7766): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 7766): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 7766): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
D/StrictMode( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
D/StrictMode( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
D/StrictMode( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 7766): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 7766): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
D/StrictMode( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/AuthorizationBluetoothService( 1749): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/GoogleURLConnFactory( 3838): Using platform SSLCertificateSocketFactory
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/qtaguid ( 7717): Untagging socket 28
W/ActivityThread( 7766): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
E/Zygote  ( 7798): MountEmulatedStorage()
E/Zygote  ( 7798): v2
I/libpersona( 7798): KNOX_SDCARD checking this for 10171
I/libpersona( 7798): KNOX_SDCARD not a persona
I/ActivityManager(  765): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7798 uid=10171 gids={50171, 9997} abi=armeabi-v7a
I/System.out( 7766): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7766): (HTTPLog)-Static: isShipBuild true
I/System.out( 7766): (HTTPLog)-Thread-1249-674655061: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7766): (HTTPLog)-Static: isSBSettingEnabled false
,I/SELinux ( 7798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7798): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7798): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7766): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 7798): TimaSignature is unavailable
,D/ActivityThread( 7798): Added TimaKeyStore provider
,W/com.google.a.a.b.d.a( 7766): Application name is not set. Call Builder#setApplicationName.
,I/System.out( 3838): (HTTPLog)-Static: isSBSettingEnabled false
,D/ResourcesManager( 7798): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 7798): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7798): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/System.out( 3838): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 3838): Tagging socket 116 with tag 1000210100000000{268443905,0} uid -1, pid: 3838, getuid(): 10015
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 3838): Tagging socket 119 with tag 1000210100000000{268443905,0} uid -1, pid: 3838, getuid(): 10015
,I/art     (  765): Explicit concurrent mark sweep GC freed 27491(1611KB) AllocSpace objects, 1(16KB) LOS objects, 30% free, 36MB/52MB, paused 1.387ms total 99.032ms
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 0
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/art     ( 1719): Explicit concurrent mark sweep GC freed 21218(999KB) AllocSpace objects, 3(71KB) LOS objects, 24% free, 16MB/22MB, paused 374us total 19.734ms
,D/btif_config_util( 6666): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(261/llIlIIIIlIIIIIlIlIII)] SD Card memory Path : /storage/emulated/0
,I/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(115/onReceive)] DM service start!
,W/ContextImpl( 7435): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssyncmldm.DMSecBroadcastReceiver.onReceive:117 android.app.ActivityThread.handleReceiver:2989 
,I/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(194/onReceive)] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(556/llllIIIllIlIIIIllllI)] nMode : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(580/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(592/lllIlIlIIIllIIlIllIl)] m_nSavedNfcMode : 0
,E/DBG_DM  ( 7435): [com.wssyncmldm.DMSecBroadcastReceiver(495/llIIIIlllllIIllIIllI)] DM Not Init
,D/CalendarSyncAdapter( 7717): Found 0 events marked dirty & lastSynced
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1682/llllIllIIIIIlIIllIII)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1687/llllIllIIIIIlIIllIII)] m_WakeLock is acquire!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1547/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 7435): [IIIlllIlIIlllIIIIllI(222/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1590/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 7435): [IIIlllIlIIlllIIIIllI(251/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1675/llIIllllIIlllIIIIlll)] 0
,I/DBG_DM  ( 7435): [IIIlllIlIIlllIIIIllI(283/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1632/IllIlIIIIlIIlIIIllIl)] 0
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [IIIlllIlIIlllIIIIllI(264/lllllllIlllIIlllIlIl)] SSL Check On
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(187/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 7435): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI:72 com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI:112 llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI:191 
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(109/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(459/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(166/lllIlIlIIIllIIlIllIl)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 7435): [IIlllIlIIlIllIlllIll(167/lllIlIlIIIllIIlIllIl)] bExternalSDStorageAvailable [false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1708/IIllIlIIIIlIIIllIllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1713/IIllIlIIIIlIIIllIllI)] m_WakeLock is release!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(186/onStartCommand)] 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 7435): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
,E/DBG_DM  ( 7435): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(49/onServiceConnected)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(1962/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WearableService( 1749): callingUid 10015, callindPid: 1749
,D/Mms/Contact( 6190): performUpdate:widgetCount=0
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(197/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,E/GmsUtils( 7022): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 7022): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/MusicLeanback( 7022): Conditions not met for autocaching.
I/MusicLeanback( 7022): Stop autocaching.
,I/ActivityManager(  765): Killing 6353:com.samsung.android.snote/u0a168 (adj 13): bgCount ##41
,E/SMD     (  302): DCD ON
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1504/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,I/DBG_DM  ( 7435): [IIllIIllIIIlllIlIIll(403/llllllIllIlIlllIIlIl)] Check completed.
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.test.thalitest.MainActivity
I/DBG_DM  ( 7435): [IIIlllIlIIlllIIIIllI(73/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,D/ChimeraCfgMgr( 3838): Loading module com.google.android.gms.games from APK com.google.android.play.games
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/ChimeraModuleLdr( 3838): Module APK com.google.android.play.games already loaded
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 0
,I/DBG_DM  ( 7435): [IIllIIllIIIlllIlIIll(102/lllIlIlIIIllIIlIllIl)] nStatus [0]
,I/art     ( 3838): Explicit concurrent mark sweep GC freed 41619(2MB) AllocSpace objects, 29(919KB) LOS objects, 24% free, 23MB/31MB, paused 876us total 52.425ms
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(280/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1907/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMBroadcastReceiver(332/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1949/lllIlIlIIIllIIlIllIl)] Start resumecase for FotaClient Polling
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,W/PlaySystemBroadcastReceiver( 3838): Processed handlePeopleChanged at 277242
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,D/ChimeraCfgMgr( 3838): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3838): Module APK com.google.android.play.games already loaded
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(210/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,W/DataBroker( 3838): No player ID found and calling context is not the dest app
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,V/Herrevad( 3838): NQAS connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(235/llIIIIlllllIIllIIllI)] bWifiOnly flag : true
,I/RemindersSync( 3838): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=687:priority=5:group=main]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(41/llIIIIlllllIIllIIllI)] nDmUiMode : 0
D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 0
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1854/lllIlIlIIIllIIlIllIl)] HttpCookieClear!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6023/lIllIlllIIllllIlIlIl)] Initiated Type: 2
,I/ConfigService( 1749): onCreate
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(124/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(496/llIIIIlllllIIllIIllI)] Set bUpdateReport = false
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1865/lllIlIlIIIllIIlIllIl)] flag is : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(51/llIIIIlllllIIllIIllI)] nDmUiMode : 3
,E/SQLiteLog( 3838): (284) automatic index on invitations(external_inviter_id)
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(305/llIIIIlllllIIllIIllI)] XEVENT_DM_CONNECT
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1865/lllIlIlIIIllIIlIllIl)] flag is : false
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [IIIlIllIlIIIIIlIIIll(111/llIlIIIIlIIIIIlIlIII)] nAgentStatus = [0]
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(317/llIIIIlllllIIllIIllI)] xfotaDlAgentIsStatus :true
,I/PowerManagerService(  765): [PWL] Off : 225s ago
I/PowerManagerService(  765): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  765): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  765): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/subscribedfeeds/com.google/eM_ADDR' (uid=1000, pid=765, ws=WorkSource{10015}) (elapsedTime=1003)
I/PowerManagerService(  765): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.location.reporting/com.google/eM_ADDR' (uid=1000, pid=765, ws=WorkSource{10015}) (elapsedTime=149)
,W/BaseAppContext( 1749): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(330/llIIIIlllllIIllIIllI)] server index : 1
,E/BaseAppContext( 1749): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1749): Tagging socket 94 with tag 1000040100000000{268436481,0} uid 10015, pid: 1749, getuid(): 10015
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(116/llIIIIlllllIIllIIllI)] xtpAdpInit
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(242/llIIIIlllllIIllIIllI)] there is no enabled apn in PREFERAPN_URI!!!!!!!
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(307/llIIIIlllllIIllIIllI)] there is no enabled apn!!!!!!!
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1415/llllllIllIlIlllIIlIl)] XTP_SSL_TUNNEL_MODE_DEACTIVE
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4235/IllIlIIIIlIIlIIIllIl)] CheckRooting Type: true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4195/llIlIIIIlIIIIIlIlIII)] WifiOnlyDownload Type: false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4352/llIIllllIIlllIIIIlll)] BigDeltaDownload Type: false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4454/IlIlIlIlIlIIlllllIlI)] DeltaHash : 
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(879/llIIIIlllllIIllIIllI)] XEVENT_DM_TCPIP_OPEN
,D/bt_vendor( 6666): op for 7
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 1 / Notification IndicatorState : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(363/llIIIIlllllIIllIIllI)] XDMService is Foreground!!
,D/WindowManager(  765): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(698/llIIIIlllllIIllIIllI)] XEVENT_DM_START
,D/ResourcesManager( 1191): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 1
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(123/llIIIIlllllIIllIIllI)] dm_ws is NULL
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(211/llIIIIlllllIIllIIllI)] !ws WARNING
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(219/llIIIIlllllIIllIIllI)] XEVENT_DM_START nAgentType : 0
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(33/llllIllIIIIIlIIllIII)] 
D/KnoxNotification( 1191): ----- inflateViews : modified publicViewLocal -----
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(123/llIIIIlllllIIllIIllI)] dm_ws is NULL
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(560/llllllIllIlIlllIIlIl)] 
,D/KnoxNotification( 1191): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1191): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1191): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2e6098aa
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1191): Icon Only
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(682/lllIlIlIIIllIIlIllIl)] nEvent :0
,I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
,D/PanelView( 1191): There is/are notification(s) 
,I/System.out( 1749): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1749): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1749): Tagging socket 68 with tag 1000060200000000{268436994,0} uid 10015, pid: 1749, getuid(): 10015
,I/qtaguid ( 1749): Tagging socket 102 with tag 1000060200000000{268436994,0} uid 10015, pid: 1749, getuid(): 10015
,I/qtaguid ( 3838): Untagging socket 116
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 6114:com.sec.pcw.device/1000 (adj 13): bgCount ##41
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SyncAdapterService( 7614): Ignoring sync request for non-current account
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  765): Killing 4247:com.sec.android.app.shealth/u0a40 (adj 13): bgCount ##41
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(347/lIlIIlIlIIlIlIIIIlll)] version name is 4.21.141212
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4407/IIIIllIlIIlIIlIlIllI)] DownloadConnType : WIFI
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(8841/lIIIIIIllIIllIlIllII)] nAgentType = 0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1573/IlIlllIIlIlIIIlIlIll)] xdmAgentMakeFwUpdateNode Initialize
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1597/IlIlllIIlIlIIIlIlIll)] pFUMOPackageNode :./FUMO/COMMONPkg
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1640/IlIlllIIlIlIIIlIlIll)] 0
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1689/IIlIlIIlIlIIlIlllIIl)] 
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(1815/llllIIIllIlIIIIllllI)] Not Exist
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(658/IIIlIIllIlIIllIlllII)] XDM_STATE_GENERIC_ALERT
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(2011/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(682/lllIlIlIIIllIIlIllIl)] nEvent :0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(2320/llIIIIlllllIIllIIllI)] xdmOmRead failed
,W/BaseAppContext( 3838): Using Auth Proxy for data requests.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(3033/llllIIIllIlIIIIllllI)] 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 1749): Untagging socket 68
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 7435): [IIlIIIlllllIIlIIIlII(166/llllIIIllIlIIIIllllI)] ALERT_TYPE_DEV_INIT
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/dhcpcd  ( 6888): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6888): wlan0: no IPv6 Routers available
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [llIlIIlIIIlllIIlIllI(81/run)] == Connect Timer[0]
I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,D/bt_upio ( 6666): ..proc_btwrite_timeout..
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/GCoreUlr( 1749): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,I/GCoreUlr( 1749): DispatchingService.onCreate()
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GCoreUlr( 1749): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1749): Unbound from all location providers
,I/GCoreUlr( 1749): Place inference reporting - stopped
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7022): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/GCoreUlr( 1749): DispatchingService.onDestroy()
I/GCoreUlr( 1749): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1749): Unbound from all location providers
,I/GCoreUlr( 1749): Place inference reporting - stopped
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 7022): Using the GMSCore's GoogleHttpClient
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Auth.Api.Credentials( 3838): [CredentialSyncAdapter] Unknown sync event.
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 7022): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 7022): (HTTPLog)-Static: isShipBuild true
I/System.out( 7022): (HTTPLog)-Thread-1132-428501042: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 7022): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 7717): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 7717): Tagging socket 28 with tag 1000000400000000{268435460,0} uid -1, pid: 7717, getuid(): 10129
I/qtaguid ( 7717): Tagging socket 32 with tag 1000000400000000{268435460,0} uid -1, pid: 7717, getuid(): 10129
,I/System.out( 7022): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,V/CalendarSyncAdapter( 7717): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-03-25T00:00:00.000Z, updatedMin=2016-02-15T23:58:22.671Z}
,I/qtaguid ( 7717): Untagging socket 28
,I/DBG_DM  ( 7435): [lllIllIIlIIllllIIlIl(2232/handshakeCompleted)] Handshake finished!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [lIIIlllIIIlllIIlllll(45/llllIIIllIlIIIIllllI)] == endTimer(connect)
,D/CalendarSyncAdapter( 7717): Found 0 events marked dirty & lastSynced
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(78/llllIllIIIIIlIIllIII)] nRet : 0
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(704/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(233/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =390
I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =628
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(60/llIIllllIIlllIIIIlll)] xdmParParse
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =1
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =0
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =SyncHdr
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =401
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =1
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Alert
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =401
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =3
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =2
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Replace
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =401
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =4
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =3
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Alert
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =401
I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(329/llIlIllllllllllllllI)] xdmParParseSyncbody end tmp = 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] SyncHdr
I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(278/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5524/llIIIIlllllIIllIIllI)] Client invalid credential(401)
,V/GLSActivity( 1749): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5524/llIIIIlllllIIllIIllI)] Client invalid credential(401)
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5524/llIIIIlllllIIllIIllI)] Client invalid credential(401)
I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5524/llIIIIlllllIIllIIllI)] Client invalid credential(401)
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 6539): 
,E/DBG_DM  ( 7435): [IIlIIIlllllIIlIIIlII(568/lllIlIlIIIllIIlIllIl)] java.lang.NumberFormatException: Invalid int: "dms.ospserver.net"
,I/System.out( 7022): (HTTPLog)-Static: isSBSettingEnabled false
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(658/IIIlIIllIlIIllIlllII)] XDM_STATE_GENERIC_ALERT
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
I/jxcore-log( 6539): 
I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(2011/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 1
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 1
I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = SyncHdr
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 6539): 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(682/lllIlIlIIIllIIlIllIl)] nEvent :0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(2320/llIIIIlllllIIllIIllI)] xdmOmRead failed
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(3033/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 7435): [IIlIIIlllllIIlIIIlII(166/llllIIIllIlIIIIllllI)] ALERT_TYPE_DEV_INIT
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(704/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(233/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
I/jxcore-log( 6539): 
,W/MusicApiClient( 7022): No content in 'data' field in GET sync response for Track
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =389
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =779
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,E/Zygote  ( 7875): MountEmulatedStorage()
E/Zygote  ( 7875): v2
I/libpersona( 7875): KNOX_SDCARD checking this for 10033
I/libpersona( 7875): KNOX_SDCARD not a persona
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(60/llIIllllIIlllIIIIlll)] xdmParParse
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =0
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =SyncHdr
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =212
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =2
,I/ActivityManager(  765): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.ConsumptionAppDataChangedReceiver: pid=7875 uid=10033 gids={50033, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Alert
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =200
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =3
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =3
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Replace
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =200
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =4
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =2
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =4
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =Alert
I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =200
,I/SELinux ( 7875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7875): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 7875): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(329/llIlIllllllllllllllI)] xdmParParseSyncbody end tmp = 1
I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] SyncHdr
,I/MusicSyncAdapter( 7022): Will attempt periodic sync for account: Account {name=thalitester@gmail.com, type=com.google}
,I/MusicSyncAdapter( 7022): Periodic update
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,D/TimaKeyStoreProvider( 7875): TimaSignature is unavailable
,D/ActivityThread( 7875): Added TimaKeyStore provider
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Get
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(3513/llIIIIlllllIIllIIllI)] item.target = ./DevDetail/FwV
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Get
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(3513/llIIIIlllllIIllIIllI)] item.target = ./DevInfo/Ext/DevNetworkConnType
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(4903/IIllIlIIIIlllIIlIIll)] total action commands = 2
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(654/IIIlIIllIlIIllIlllII)] XDM_STATE_PROCESSING
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 1
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 2
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = SyncHdr
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 2
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 2
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Get
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 4
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 2
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Get
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(704/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/art     (  765): Explicit concurrent mark sweep GC freed 43899(2MB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 36MB/52MB, paused 1.416ms total 107.114ms
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(233/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,I/GAV4    ( 7614): Thread[GAThread,5,main]: No campaign data found.
,D/ResourcesManager( 7875): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 7875): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7875): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,W/Settings( 7875): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7875): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =390
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =1008
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 0
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(60/llIIllllIIlllIIIIlll)] xdmParParse
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =3
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =0
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =SyncHdr
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =200
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,D/Ads     ( 7875): Skipping gmscore version check
I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,E/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(865/IlIlllIIlIlIIIlIlIll)] WBXML_ERR_ZEROBIT_TAG
,I/DBG_DM  ( 7435): [llllIllIllIIIllllIIl(30/llIIIIlllllIIllIIllI)] xdmParParsePcdata
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(329/llIlIllllllllllllllI)] xdmParParseSyncbody end tmp = 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] SyncHdr
,D/Finsky  ( 7875): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7875): [1] Libraries$2.run: Finished loading 1 libraries.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5548/llIIIIlllllIIllIIllI)] Client Authrization Accepted (Catch 200)
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/File    ( 7022): fail readDirectory() errno=2
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Replace
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7267/llIIIIlllllIIllIIllI)] 178
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7434/llIIIIlllllIIllIIllI)] else
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,D/Finsky  ( 7875): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7875): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MusicLeanback( 7022): Conditions not met for autocaching.
I/MusicLeanback( 7022): Stop autocaching.
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7619/llIIIIlllllIIllIIllI)] 178
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7620/llIIIIlllllIIllIIllI)] 178
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Exec
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1504/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5854/llIIIIlllllIIllIIllI)] ./FUMO/DownloadAndUpdate
,I/DBG_DM  ( 7435): [lIllIIIllIIIllIIIlll(354/llIIIIlllllIIllIIllI)] strnodename :., ptr :FUMO/DownloadAndUpdate
,I/DBG_DM  ( 7435): [lIllIIIllIIIllIIIlll(410/llIIIIlllllIIllIIllI)] strnodename :FUMO, ptr :DownloadAndUpdate
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6079/IllIIlllIllIIIIIllII)] AgentType=1
,E/GmsUtils( 7022): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4115/llllIIIllIlIIIIllllI)] OptionalUpdate Type: false
,E/GmsUtils( 7022): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7022): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/ActivityManager(  765): Killing 6190:com.android.mms/u0a55 (adj 13): bgCount ##41
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5200/lIllIllllIIIlllIlllI)] Set Cache Margin : 60
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5160/llllIlIIIllllIIlIlll)] Set Data Margin : 180
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5681/llIIIIlllllIIllIIllI)] Mechanism is XDM_FOTA_MECHANISM_ALTERNATIVE
,E/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5713/llIIIIlllllIIllIIllI)] Node Parsing Error
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Replace
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7267/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7434/llIIIIlllllIIllIIllI)] else
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7787/llllIIIllIlIIIIllllI)] szPath : ./FUMO/Ext/DoCheckingRooting, szData : T
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7822/llllIIIllIlIIIIllllI)] ROOTINGCHECK : T
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4235/IllIlIIIIlIIlIIIllIl)] CheckRooting Type: true
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7619/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7620/llIIIIlllllIIllIIllI)] 1
,D/CountryDetector(  765): No listener is left
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Replace
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7267/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7434/llIIIIlllllIIllIIllI)] else
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7787/llllIIIllIlIIIIllllI)] szPath : ./FUMO/Ext/Priority, szData : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5120/llIllIIllIIlIIlIIIII)] Set Priority : 0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7619/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7620/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Replace
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7267/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7434/llIIIIlllllIIllIIllI)] else
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7787/llllIIIllIlIIIIllllI)] szPath : ./FUMO/Ext/Postpone, szData : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4959/IIllIlIIIIlIIIllIllI)] Set Postpone Max Count : 0
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7619/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7620/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Replace
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7267/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7434/llIIIIlllllIIllIIllI)] else
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7787/llllIIIllIlIIIIllllI)] szPath : ./FUMO/Ext/ForceInstall, szData : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5040/lllllllIlllIIlllIlIl)] Set Force status : 0
,D/BatteryService(  765): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  765): level:100, scale:100, status:5, health:2, present:true, voltage: 4275, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  765): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  765): stay LED for fully charged
D/BatteryService(  765): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService(  765): Plugged
I/MotionRecognitionService(  765): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1191): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1191): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1191):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1191): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 6666): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 6666): Disconnected process message: 10
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7619/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(7620/llIIIIlllllIIllIIllI)] 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(4903/IIllIlIIIIlllIIlIIll)] total action commands = 6
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(654/IIIlIIllIlIIllIlllII)] XDM_STATE_PROCESSING
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 1
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,E/DataBuffer( 3838): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@235f06d6)
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = SyncHdr
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 2
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Replace
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Exec
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 4
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Replace
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 5
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Replace
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 6
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Replace
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(824/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmdid = 7
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(825/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.msgref = 3
,I/DBG_DM  ( 7435): [llIlllIIIIlIllIIlIIl(826/llIIIIlllllIIllIIllI)] xdmEncAddStatus cmd.cmd = Replace
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,E/SMD     (  302): DCD ON
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(704/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(233/llIIIIlllllIIllIIllI)] XEVENT_DM_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =389
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =452
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(60/llIIllllIIlllIIIIlll)] xdmParParse
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(64/llIIIIlllllIIllIIllI)] xdmParParseStatus WBXML_END
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(146/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDID cmdid =1
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(147/llIIIIlllllIIllIIllI)] WBXML_TAG_MSGREF msgref =4
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(148/llIIIIlllllIIllIIllI)] WBXML_TAG_CMDREF cmdref =0
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(149/llIIIIlllllIIllIIllI)] WBXML_TAG_Cmd cmd =SyncHdr
,I/DBG_DM  ( 7435): [IIlllIlIlIIIlIIllIII(150/llIIIIlllllIIllIIllI)] WBXML_TAG_DATA data =200
,I/DBG_DM  ( 7435): [lIIIlIllllIllIIllIII(329/llIlIllllllllllllllI)] xdmParParseSyncbody end tmp = 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] SyncHdr
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5182/IIIIlIlIIIIIIIlIIlll)] Status
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(5548/llIIIIlllllIIllIIllI)] Client Authrization Accepted (Catch 200)
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(4903/IIllIlIIIIlllIIlIIll)] total action commands = 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(4913/IIllIlIIIIlllIIlIIll)] nStatus :10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4269/IlIIIlIIllllIIIIIIII)] CheckRooting Type: true
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(4927/IIllIlIIIIlllIIlIIll)] Now Download Start
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(331/llIIIIlllllIIllIIllI)] XDM_RET_EXEC_ALTERNATIVE
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(332/llIIIIlllllIIllIIllI)] Connect to the Contents Server
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(851/llIIIIlllllIIllIIllI)] XEVENT_DM_FINISH
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1311/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(207/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(633/llIIIIlllllIIllIIllI)] nStatus [10]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1383/lIIIIIIlIlllIIlllIIl)] 
,D/SettingsProvider(  765): name = SOFTWARE_UPDATE_LAST_CHECKED_DATE
,W/ContextImpl( 7435): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.XDMService.lIIIIIIlIlllIIlllIIl:1402 IIIIlIllIlllIlIIIIlI.llIIIIlllllIIllIIllI:671 llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI:855 
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(162/llIIIIlllllIIllIIllI)] Set bServerInitiatedStatus = false
,I/DBG_DM  ( 7435): [IIIIlIllIlllIlIIIIlI(673/llIIIIlllllIIllIIllI)] Case XEVENT_DM_FINISH XDL_STATE_IDLE_START
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(229/IllIlIIIIlIIlIIIllIl)] inDMSync = 1
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(241/IllIlIIIIlIIlIIIllIl)] workspace save
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(925/llIIIIlllllIIllIIllI)] XEVENT_DL_CONNECT
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.IlIIIIlIllllIIIllIIl(236/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(116/llIIIIlllllIIllIIllI)] xtpAdpInit
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(242/llIIIIlllllIIllIIllI)] there is no enabled apn in PREFERAPN_URI!!!!!!!
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(307/llIIIIlllllIIllIIllI)] there is no enabled apn!!!!!!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1415/llllllIllIlIlllIIlIl)] XTP_SSL_TUNNEL_MODE_DEACTIVE
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 1
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1554/llIIIIlllllIIllIIllI)] XEVENT_DL_TCPIP_OPEN
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 1 / Notification IndicatorState : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(363/llIIIIlllllIIllIIllI)] XDMService is Foreground!!
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [llIlIIlIIIlllIIlIllI(81/run)] == Connect Timer[0]
,D/StatusBar( 1191): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
I/StatusBar( 1191): Icon Only
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/PanelView( 1191): There is/are notification(s) 
,D/PanelView( 1191): There is/are notification(s) 
I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [lllIllIIlIIllllIIlIl(2232/handshakeCompleted)] Handshake finished!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
I/DBG_DM  ( 7435): [lIIIlllIIIlllIIlllll(45/llllIIIllIlIIIIllllI)] == endTimer(connect)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1586/llIIIIlllllIIllIIllI)] XEVENT_DL_START
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1417/IIIIllIlIIlIIIIlllIl)] nEvent [116] nAgentStatus[10]
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3759/lllIIIlllIllIlIllIIl)] nFUMOStatus :10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1599/llIIIIlllllIIllIIllI)] XEVENT_DL_CONTINUE!!
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1417/IIIIllIlIIlIIIIlllIl)] nEvent [120] nAgentStatus[10]
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1510/IIIIllIlIIlIIIIlllIl)] XEVENT_DL_CONTINUE
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1514/IIIIllIlIIlIIIIlllIl)] XEVENT_DL_CONTINUE  & XDL_STATE_IDLE_START
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(852/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,D/ConnectivityService(  765): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =391
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =1281
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 10
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(902/lllIlIlIIIllIIlIllIl)] DD check success. nRet = [0]
,I/DBG_DM  ( 7435): [IlllllllIllIlIllIlIl(23/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlllllllIllIlIllIlIl(51/llIIIIlllllIIllIIllI)] Parsing DownloadDescriptor is Complete
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(616/llIIIIlllllIIllIIllI)] nObjectSize : 59186579, nCacheMarginSize : 104857600, nDataMarginSize : 524288000
,W/ContextImpl( 7435): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI:624 IIIlIllIlIIIIIlIIIll.llIIIIlllllIIllIIllI:372 IIIlIllIlIIIIIlIIIll.llIIIIlllllIIllIIllI:227 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1617/llIIIIlllllIIllIIllI)] XEVENT_DL_FINISH
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1311/IllIlIIIIlIIlIIIllIl)] 
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1627/llIIIIlllllIIllIIllI)] xdbGetFUMOStatus nStatus200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4149/IIIllIIllIllIlIIlIIl)] OptionalUpdate Type: false
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1650/llIIIIlllllIIllIIllI)] nEvent : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 7435): [IIllIlIIlIlllIIllIII(367/llIIIIlllllIIllIIllI)] XUI_DL_DOWNLOAD_YES_NO
,I/DBG_DM  ( 7435): [IlIlllIlllllIlIllllI(160/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4189/IIllllIIlIIllIIIIlll)] OptionalCancel Type: false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6055/IIIlIllIlIIIIIlIIIll)] Initiated Type: 2
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4149/IIIllIIllIllIlIIlIIl)] OptionalUpdate Type: false
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(501/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [lIlIIIlllIlIlIlIIIll(55/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(50/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:59186579
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5194/IIIIlIllIlllIlIIIIlI)] Cache Margin : 100
,I/DBG_DM  ( 7435): [lIlIIIlllIlIlIlIIIll(156/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 7435): [lIlIIIlllIlIlIlIIIll(186/llllIIIllIlIIIIllllI)] Cache memory >>> XDB_FS_OK...
,I/DBG_DM  ( 7435): [lIlIIIlllIlIlIlIIIll(187/llllIIIllIlIIIIllllI)] Remain size : 304197632, Total size : 309616640 and Delta Size : 164044179 bytes
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(204/llIIIIlllllIIllIIllI)] Cache memory >>> XDB_FS_OK...
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(205/llIIIIlllllIIllIIllI)] Remain size : 304197632, Total size : 309616640 and Delta Size : 164044179 bytes
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1764/llIIIIlllllIIllIIllI)] Check memory space for delta split
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5154/lIIIIIIIlllllllIIlll)] Data Margin : 500
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(925/llIIIIlllllIIllIIllI)] XEVENT_DL_CONNECT
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.IlIIIIlIllllIIIllIIl(236/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(116/llIIIIlllllIIllIIllI)] xtpAdpInit
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(242/llIIIIlllllIIllIIllI)] there is no enabled apn in PREFERAPN_URI!!!!!!!
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(307/llIIIIlllllIIllIIllI)] there is no enabled apn!!!!!!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 1
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1554/llIIIIlllllIIllIIllI)] XEVENT_DL_TCPIP_OPEN
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 1 / Notification IndicatorState : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(363/llIIIIlllllIIllIIllI)] XDMService is Foreground!!
,D/StatusBar( 1191): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1191): Icon Only
I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3786/IllIIlllIllIIIIIllII)] Wifi_Only_flag : true
,I/DBG_DM  ( 7435): [llIlIIlIIIlllIIlIllI(81/run)] == Connect Timer[0]
D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
I/jxcore-log( 6539): 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [llIlIIIIIIIIlllIllII(255/IlIlllIIlIlIIIlIlIll)] return true
,I/jxcore-log( 6539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6539): 
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4229/IlllllIIIIIIIIllIIIl)] WifiOnlyDownload Type: false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [lIIIlllIIIlllIIlllll(45/llllIIIllIlIIIIllllI)] == endTimer(connect)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1586/llIIIIlllllIIllIIllI)] XEVENT_DL_START
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1417/IIIIllIlIIlIIIIlllIl)] nEvent [116] nAgentStatus[200]
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4407/IIIIllIlIIlIIlIlIllI)] DownloadConnType : WIFI
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4415/IIIlIIllIlIIllIlllII)] DownloadConnType : WIFI
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(562/lllllIIlIIIlIlIIIllI)] 
,I/DBG_DM  ( 7435): [IIIlIllIlIIIIIlIIIll(145/IllIlIIIIlIIlIIIllIl)] 
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(339/IllIlIIIIlIIlIIIllIl)] java.io.FileNotFoundException: /cache/fota/update.zip: open failed: ENOENT (No such file or directory)
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(339/IllIlIIIIlIIlIIIllIl)] java.io.FileNotFoundException: /cache/fota/update.zip: open failed: ENOENT (No such file or directory)
,I/jxcore-log( 6539): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 6539): 
,I/DBG_DM  ( 7435): [IIIlIllIlIIIIIlIIIll(183/llllIIIllIlIIIIllllI)] nOffset = 0 nTotalObjectSize = 59186579
,I/DBG_DM  ( 7435): [IIIlIllIlIIIIIlIIIll(198/llllIIIllIlIIIIllllI)] offset = 0, TotalSize = 59186579
I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(584/llllIIIllIlIIIIllllI)] 
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3759/lllIIIlllIllIlIllIIl)] nFUMOStatus :200
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 200
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(579/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(486/llllIIIllIlIIIIllllI)] xtpAdpHttpPsrMakeHeader
,I/DBG_DM  ( 7435): [llIIIllllIIIlIIIlIIl(45/llllIIIllIlIIIIllllI)] == endTimer(send)
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(539/llIlIIIIlIIIIIlIlIII)] 
,W/ContextImpl( 7435): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.llIlIIIIlIIIIIlIlIII:552 IIlIlIllIlIIIIIIllll.llllIIIllIlIIIIllllI:749 IIlIlIllIlIIIIIIllll.lllllIIlIIIlIlIIIllI:571 
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1599/llIIIIlllllIIllIIllI)] XEVENT_DL_CONTINUE!!
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1417/IIIIllIlIIlIIIIlllIl)] nEvent [120] nAgentStatus[30]
I/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(1510/IIIIllIlIIlIIIIlllIl)] XEVENT_DL_CONTINUE
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(862/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1667/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1706/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHttpReturnStatusValue=206
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1769/llIIIIlllllIIllIIllI)] chunked = 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1770/llIIIIlllllIIllIIllI)] pHttpObj[appId].nHeaderLength =513
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1771/llIIIIlllllIIllIIllI)] pHttpObj[appId].nContentLength =59186579
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1791/llIIIIlllllIIllIIllI)] szHMAC null
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1797/llIIIIlllllIIllIIllI)] pContentRangebytes 0-59186578/59186579
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [IIllIlIIlIlllIIllIII(489/llIIIIlllllIIllIIllI)] XUI_DL_DOWNLOAD_IN_PROGRESS
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(1776/lIlIIIlllIIlIIIlIlII)] java.io.FileNotFoundException: /cache/fota/update.zip: open failed: ENOENT (No such file or directory)
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(819/IllIlIIIIlIIlIIIllIl)] Idle Screen : false
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(51/llIIIIlllllIIllIIllI)] nDmUiMode : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 11 / Notification IndicatorState : 11
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(41/llIIIIlllllIIllIIllI)] nDmUiMode : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(41/llIIIIlllllIIllIIllI)] nDmUiMode : 2
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(363/llIIIIlllllIIllIIllI)] XDMService is Foreground!!
,D/LightsService(  765): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 765) 
,D/LightsService(  765): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,E/LightSensor(  765): Light old sensor_state 0, new sensor_state : 512 en : 1
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(41/llIIIIlllllIIllIIllI)] nDmUiMode : 2
,D/SensorManager(  765): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/WindowManager(  765): showStatusBarByNotification() mOpenByNotification=false
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
,D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
,I/StatusBar( 1191): Icon Only
,D/PanelView( 1191): There is/are notification(s) 
,D/PanelView( 1191): There is/are notification(s) 
,D/KnoxNotification( 1191): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1191): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1191): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1191): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2e6098aa
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
,I/StatusBar( 1191): Icon Only
,D/PanelView( 1191): There is/are notification(s) 
D/PanelView( 1191): There is/are notification(s) 
,I/jxcore-log( 6539): --= Surplus to requirements =--
I/jxcore-log( 6539): 
,I/jxcore-log( 6539): ****TEST TOOK:  ms ****
I/jxcore-log( 6539): 
I/jxcore-log( 6539): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6539): 
,I/ConfigService( 1749): onDestroy
,D/LightsService(  765): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  765): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  765): unregisterListener ::   
D/LightsService(  765): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AndroidRuntime( 7955): 
D/AndroidRuntime( 7955): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7955): CheckJNI is OFF
,D/AndroidRuntime( 7955): readGMSProperty: start
D/AndroidRuntime( 7955): readGMSProperty: already setted!!
,D/AndroidRuntime( 7955): readGMSProperty: end
,D/AndroidRuntime( 7955): addProductProperty: start
,E/AffinityControl( 7955): AffinityControl: registerfunction enter
,D/AndroidRuntime( 7955): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  765): START PACKAGE DELETE: observer{301549309}
D/PackageManager(  765): pkg{<packageName>}
D/PackageManager(  765): user{0}
D/PackageManager(  765): caller{2000}
D/PackageManager(  765): flags{3}
D/PersonaManagerService(  765): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  765): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  765): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager(  765): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  765): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager(  765): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  765): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  765): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  765): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  765): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  765): !@killApplicatoin: 10079, uninstall pkg
I/ActivityManager(  765): Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,I/ActivityManager(  765): Killing 6539:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest
,W/PackageSettings(  765): Skipping PackageSetting{1fe65e2b com.example.hello/10078} due to missing metadata
,I/WindowState(  765): WIN DEATH: Window{3884e208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  266): id=11 Removed NainActivit (6/8)
,I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  266): id=11 Removed NainActivit (-2/8)
D/PointerIcon(  765): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  765): setMouseCustomIcon IconType is same.101
D/PointerIcon(  765): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  765): setHoveringSpenCustomIcon IconType is same.1
,E/libprocessgroup(  765): failed to kill 1 processes for processgroup 6539
,I/ActivityManager(  765):   Force finishing activity ActivityRecord{2255cef2 u0 com.test.thalitest/.MainActivity t9}
,D/FocusedStackFrame(  765): Set to : 0
,I/ActivityManager(  765): Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,I/ActivityManager(  765):   Force finishing activity ActivityRecord{2255cef2 u0 com.test.thalitest/.MainActivity t9 f}
,W/ActivityManager(  765): Duplicate finish request for ActivityRecord{2255cef2 u0 com.test.thalitest/.MainActivity t9 f}
,I/art     ( 1622): Explicit concurrent mark sweep GC freed 889(47KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 19MB/32MB, paused 728us total 27.864ms
,W/ActivityManager(  765): Spurious death for ProcessRecord{3f727ff2 6539:com.test.thalitest/u0a79}, curProc for 6539: null
,D/ConnectivityService(  765): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  765): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 5192): Explicit concurrent mark sweep GC freed 9805(468KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 312us total 24.493ms
,I/InputReader(  765): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1441): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,E/SamsungIME( 1686): mOCRHelper is null
,W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 1749): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager( 1441): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,W/ResourcesManager( 1441): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1441): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/RegisteredServicesCache( 1410): empty dynamic service
,I/art     ( 5325): Explicit concurrent mark sweep GC freed 36620(1987KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 15MB/26MB, paused 9.895ms total 39.011ms
,W/ResourcesManager( 1441): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 1441): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/KLMS-2.4.511: ( 7062): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,E/SMD     (  302): DCD ON
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/KLMS-2.4.511: ( 7062): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456909102174
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/KLMS-2.4.511: ( 7062): MainReciver(): PACKAGE_REMOVED
,I/KLMS-2.4.511: ( 7062): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,D/SecContentProvider2(  765): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  765): mCursor = null
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/elm:14491( 7188): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/EnterpriseDeviceManagerService(  765): Package has changed for user 0
D/EnterpriseDeviceManagerService(  765): Admin package name: com.google.android.gms
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/elm:14491( 7188): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/AASAservice-UpdateReceiver( 3327): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/System.err( 3327): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3327): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
W/System.err( 3327): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 3327): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
W/System.err( 3327): 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
W/System.err( 3327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
W/System.err( 3327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3327): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3327): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
W/System.err( 3327): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3327): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
W/System.err( 3327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/elm:14491( 7188): ElmAgentService : onCreate()
,D/elm:14491( 7188): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491( 7188): MainReceiver.listeningToPackageRemoved()
D/elm:14491( 7188): MDMBridge.getInstance()
D/elm:14491( 7188): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491( 7188): MDMBridge.getAllLicenseInfoFromSDK()
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RCPManagerService(  765): PackageReceiver onReceive()
I/HarmonyEASService(  765): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/SSRM:n  (  765): SIOP:: AP = 390, PST = 310, CUR = 450
,D/KnoxMUMContainerPolicy(  765): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  765): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  765): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  765): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  765): uID is 10079
V/EnterpriseBillingPolicy(  765): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  765): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  765): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  765): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  765): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  765): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  765): getBillingProfileForVpnEngine - end - null
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,E/Zygote  ( 7992): MountEmulatedStorage()
,E/Zygote  ( 7992): v2
I/libpersona( 7992): KNOX_SDCARD checking this for 10021
I/libpersona( 7992): KNOX_SDCARD not a persona
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/ActivityManager(  765): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7992 uid=10021 gids={50021, 9997} abi=armeabi-v7a
W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,D/TaskPersister(  765): removeObsoleteFile: deleting file=9_task.xml
D/SSRM:aV (  765): MSG_TYPE_APP_REMOVED::
,V/AlarmManagerEXT(  765): com.test.thalitest(10079) is removed.
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 7992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7992): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,D/elm:14491( 7188): ElmAgentService : onDestroy().
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 7992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     (  765): Explicit concurrent mark sweep GC freed 30966(2MB) AllocSpace objects, 9(144KB) LOS objects, 30% free, 37MB/53MB, paused 4.522ms total 276.614ms
,D/TimaKeyStoreProvider( 7992): TimaSignature is unavailable
,D/ActivityThread( 7992): Added TimaKeyStore provider
D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 7992): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,D/SurfaceWidgetView( 1441): destroyHardwareResources():34057252
,V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  765): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  765): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/Launcher( 1441): onRestart, Launcher: 1034402794
,D/Launcher( 1441): onStart, Launcher: 1034402794
D/Launcher.HomeView( 1441): onStart
,V/ActivityThread( 1441): updateVisibility : ActivityRecord{2b5b599 token=android.os.BinderProxy@3670b7ef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1772): [237392/8] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 1772): [237392/8] SurfaceWidget drawing first frame
D/accuweather( 1772): [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,I/SurfaceFlinger(  266): id=13 createSurf (1080x1920),1 flag=4, Mauncher
,D/StatusBarManagerService(  765): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService(  765): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon(  765): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  765): setMouseCustomIcon IconType is same.101
D/com.sec.android.service.health.upgrade.UninstallReceiver( 7992): onReceive()
D/PointerIcon(  765): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  765): setHoveringSpenCustomIcon IconType is same.1
I/com.sec.android.service.health.upgrade.UninstallReceiver( 7992): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
,W/ResourcesManager(  765): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  765): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  765): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 7992): onReceive() : package name is not s health. Return !!!
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  765): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/InputMethodManagerService(  765): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  765): Got RemoteException sending setActive(false) notification to pid 6539 uid 10079
,W/ContextImpl(  765): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager(  765): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,E/Zygote  ( 8016): MountEmulatedStorage()
I/libpersona( 8016): KNOX_SDCARD checking this for 10025
E/Zygote  ( 8016): v2
I/libpersona( 8016): KNOX_SDCARD not a persona
,I/ActivityManager(  765): Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8016 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/ActivityManager(  765): Killing 7116:com.samsung.android.scloud.sync/u0a76 (adj 13): bgCount ##41
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/PackageManager(  765): delete codoeFile: 
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,D/AASAuninstall(  765): userId = 0, info.removedAppID = -1, info.uid = 10079, packageName = com.test.thalitest
,I/AASA_removePackage(  765): UID=10079 Target=com.test.thalitest
D/PackageManager(  765): result of delete: 1{301549309}
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux ( 8016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8016): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,E/SELinux ( 8016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  765): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/AndroidRuntime( 7955): Shutting down VM
,I/Timeline(  765): Timeline: Activity_windows_visible id: ActivityRecord{e36e73b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:283634
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  765): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  765): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 8016): TimaSignature is unavailable
,D/ActivityThread( 8016): Added TimaKeyStore provider
,D/UsbSettingsManager(  765): clearDefaults: com.test.thalitest
,I/CrashAnrDetector(  765): onPackageRemoved : com.test.thalitest
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/linker  ( 8016): libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/MVFD_interface( 8016): <<<  caMVFace_FaceInit
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,E/Vold    (  265): Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
W/Vold    (  265): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,D/HockeyApp( 8016): Current handler class = sstream.app.util.Log$1
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,D/ApplicationCompatibleReceiver( 8016): com.sec.chaton Already existed in setting table , SKIP!!!
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,D/ApplicationCompatibleReceiver( 8016): com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
,W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8016): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 8016): Asset path '/system/framework/svi.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ApplicationCompatibleReceiver( 8016): com.sec.pcw Already existed in setting table , SKIP!!!
,D/ApplicationCompatibleReceiver( 8016): com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,W/ResourcesManager( 8016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SQLiteLog( 8016): (1299) abort at 20 in [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,?,?,?,?,?
,E/SQLiteDatabase( 8016): Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131690540 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
E/SQLiteDatabase( 8016): android.database.sqlite.SQLiteConstraintException: NOT NULL constraint failed: config.stream_id (code 1299)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 8016): ,	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
E/SQLiteDatabase( 8016): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
E/SQLiteDatabase( 8016): 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
E/SQLiteDatabase( 8016): 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
E/SQLiteDatabase( 8016): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 8016): 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
E/SQLiteDatabase( 8016): 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
E/SQLiteDatabase( 8016): 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
E/SQLiteDatabase( 8016): 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
E/SQLiteDatabase( 8016): 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,D/ApplicationCompatibleReceiver( 8016): com.sec.android.gallery3d Already existed in setting table , SKIP!!!
,D/ResourcesManager( 8016): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/ApplicationCompatibleReceiver( 8016): com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
,W/FileUtils( 7435): Failed to chmod(/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/ApplicationCompatibleReceiver( 8016): com.samsung.android.snote Already existed in setting table , SKIP!!!
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:540)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java,:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:540)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lIlIIIlllIIlIIIlIlII(llIIIIlllllIIllIIllI:1769)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1725)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.lIlIIIlllIIlIIIlIlII(llIIIIlllllIIllIIllI:1769)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1725)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:1810)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1744)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOp,enHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:1810)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1744)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:538)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
I/libpersona( 8063): KNOX_SDCARD checking this for 1000
E/Zygote  ( 8063): MountEmulatedStorage()
I/libpersona( 8063): KNOX_SDCARD not a persona
E/Zygote  ( 8063): v2
W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(1828/lllIlIlIIIllIIlIllIl)] java.io.FileNotFoundException: /cache/fota/update.zip: open failed: EROFS (Read-only file system)
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(1751/llllIIIllIlIIIIllllI)] Append FAILED
I/ActivityManager(  765): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8063 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager(  765): Killing 5192:com.samsung.android.sm/1000 (adj 13): bgCount ##41
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:540)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:540)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1234)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:134)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/DBG_DM  ( 7435): [IIlIlIllIlIIIIIIllll(548/llIIIIlllllIIllIIllI)] FFS WRITE FAILED
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2176)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1906)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:202)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:802)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2559)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:481)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIIIIlllIIlllIIlIIl(llIIIIlllllIIllIIllI:3901)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIlIIllIlIIllIlllII(llIIIIlllllIIllIIllI:2018)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2176)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1906)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:202)
E/SQLiteOpenHelper( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(593/IIIIllIlIIlIIIIlllIl)] delete is failed
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1206)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2396)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1310)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:4297)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:204)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4301/llIlIllllllllllllllI)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 20
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1206)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2396)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1310)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIIIIlllllIIllllllI(llIIIIlllllIIllIIllI:3660)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IlIlIlIlIlIIlllllIlI(llIIIIlllllIIllIIllI:205)
E/SQLiteDatabase( 7435): 	at IIlIlIllIlIIIIIIllll.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:1520)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1609)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3664/llIIIIlllllIIllllllI)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,I/SELinux ( 8063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 8063): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3666/llIIIIlllllIIllllllI)] xdbSetFUMOStatus db write was failed
E/SELinux ( 8063): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 7435): [IIllIlIIlIlllIIllIII(142/llIIIIlllllIIllIIllI)] 131
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6023/lIllIlllIIllllIlIlIl)] Initiated Type: 0
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1617/llIIIIlllllIIllIIllI)] XEVENT_DL_FINISH
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1206)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2396)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1310)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lIllIlllIIllllIlIlIl(llIIIIlllllIIllIIllI:6026)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:154)
E/SQLiteDatabase( 7435): 	at llIllllIlllIIIllIIIl.handleMessage(llIIIIlllllIIllIIllI:63)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.run(llIIIIlllllIIllIIllI:68)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1311/IllIlIIIIlIIlIIIllIl)] 
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(6030/lIllIlllIIllllIlIlIl)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(162/llIIIIlllllIIllIIllI)] Set bServerInitiatedStatus = false
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1627/llIIIIlllllIIllIIllI)] xdbGetFUMOStatus nStatus30
,I/EventHub(  765): Removing device '/dev/input/event6' due to inotify event
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:750)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2371)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1235)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lllIIIIllIlIlllllllI(llIIIIlllllIIllIIllI:5528)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1682)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5532/lllIIIIllIlIlllllllI)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(925/llIIIIlllllIIllIIllI)] XEVENT_DL_CONNECT
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(1859/llIlIIIIlIIIIIlIlIII)] flag is : false
,D/TimaKeyStoreProvider( 8063): TimaSignature is unavailable
,D/ActivityThread( 8063): Added TimaKeyStore provider
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.IlIIIIlIllllIIIllIIl(236/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 7435): [IlIlIlllIIlllIlIlIIl(116/llIIIIlllllIIllIIllI)] xtpAdpInit
,I/System.out( 8016): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 8016): (HTTPLog)-Static: isShipBuild true
I/System.out( 8016): (HTTPLog)-Thread-1267-710077581: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 8016): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 8016): (HTTPLog)-Static: isSBSettingEnabled false
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,D/LightsService(  765): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 765) 
D/LightsService(  765): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/System.out( 8016): (HTTPLog)-Static: isSBSettingEnabled false
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:541)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:158)
E/SQLiteDatabase( 7435): 	at llIllllIlllIIIllIIIl.handleMessage(llIIIIlllllIIllIIllI:63)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.run(llIIIIlllllIIllIIllI:68)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
E/SensorService(  765): Error activating sensor 6 (Operation not permitted)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1373)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2587)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:541)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IlIllIIIIllllllIlIIl(llIIIIlllllIIllIIllI:5285)
E/SQLiteOpenHelper( 7435): 	at IIllIlIIlIlllIIllIII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:158)
E/SQLiteOpenHelper( 7435): 	at llIllllIlllIIIllIIIl.handleMessage(llIIIIlllllIIllIIllI:63)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at IIllIlIIlIlllIIllIII.run(llIIIIlllllIIllIIllI:68)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
D/PersonaManager( 1191): isKioskContainerExistOnDevice
D/PersonaManager( 1191): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1191): Icon Only
,I/StatusBar( 1191): Icon Only
D/PanelView( 1191): There is/are notification(s) 
,D/PanelView( 1191): There is/are notification(s) 
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(242/llIIIIlllllIIllIIllI)] there is no enabled apn in PREFERAPN_URI!!!!!!!
,D/ResourcesManager( 8063): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/ContextImpl( 8063): Unable to create files subdir /data/data/com.sec.pcw.device/cache
E/ActivityThread( 8063): Unable to setupGraphicsSupport due to missing cache directory
,E/DBG_DM  ( 7435): [llllIIlIlIIIIllIlIIl(307/llIIIIlllllIIllIIllI)] there is no enabled apn!!!!!!!
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4334/lIIIIIIllIIllIlIllII)] Set CurrentDownloadMode : 0
,I/EventHub(  765): Removing device '/dev/input/event7' due to inotify event
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:533)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2579)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:488)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lIllIllllIIIlllIlllI(llIIIIlllllIIllIIllI:3503)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.XDMService.IIIIIIlIIIllllllIlII(llIIIIlllllIIllIIllI:1039)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:121)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:533)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2579)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:488)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.lIllIllllIIIlllIlllI(llIIIIlllllIIllIIllI:3503)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.XDMService.IIIIIIlIIIllllllIlII(llIIIIlllllIIllIIllI:1039)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:121)
E/SQLiteOpenHelper( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:1206)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2396)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1310)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lIIIIIIllIIllIlIllII(llIIIIlllllIIllIIllI:4337)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:160)
E/SQLiteDatabase( 7435): 	at llIllllIlllIIIllIIIl.handleMessage(llIIIIlllllIIllIIllI:63)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at IIllIlIIlIlllIIllIII.run(llIIIIlllllIIllIIllI:68)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:616)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1239)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:3521)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.XDMService.IIIIIIlIIIllllllIlII(llIIIIlllllIIllIIllI:1059)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:121)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:616)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1239)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:3521)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.XDMService.IIIIIIlIIIllllllIlII(llIIIIlllllIIllIIllI:1059)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:121)
E/SQLiteOpenHelper( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(4341/lIIIIIIllIIllIlIllII)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,D/AndroidRuntime( 8063): Shutting down VM
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:58)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:488)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2391)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIlIIIIlIIIIIlIlIII(llIIIIlllllIIllIIllI:1241)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:3521)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.XDMService.IIIIIIlIIIllllllIlII(llIIIIlllllIIllIIllI:1059)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:121)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/AndroidRuntime( 8063): FATAL EXCEPTION: main
E/AndroidRuntime( 8063): Process: com.sec.pcw.device, PID: 8063
E/AndroidRuntime( 8063): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.DMProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
E/AndroidRuntime( 8063): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8063): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.main(ActivityThread.java:5938)
E/AndroidRuntime( 8063): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8063): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8063): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
E/AndroidRuntime( 8063): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
E/AndroidRuntime( 8063): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.pcw.device.contentprovider.DMProvider" on path: DexPathList[[zip file "/system/priv-app/PCWClientS18/PCWClientS18.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/AndroidRuntime( 8063): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/AndroidRuntime( 8063): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/AndroidRuntime( 8063): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/AndroidRuntime( 8063): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
E/AndroidRuntime( 8063): 	... 11 more
E/AndroidRuntime( 8063): 	Suppressed: java.io.IOException: Zip archive '/system/priv-app/PCWClientS18/PCWClientS18.apk' doesn't contain classes.dex (error msg: Entry not found)
E/AndroidRuntime( 8063): 		at dalvik.system.DexFile.openDexFileNative(Native Method)
E/AndroidRuntime( 8063): 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
E/AndroidRuntime( 8063): 		at dalvik.system.DexFile.<init>(DexFile.java:80)
E/AndroidRuntime( 8063): 		at dalvik.system.DexFile.<init>(DexFile.java:59)
E/AndroidRuntime( 8063): 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
E/AndroidRuntime( 8063): 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
E/AndroidRuntime( 8063): 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
E/AndroidRuntime( 8063): 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
E/AndroidRuntime( 8063): 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
E/AndroidRuntime( 8063): 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
E/AndroidRuntime( 8063): 		at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8063): 		at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8063): 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
E/AndroidRuntime( 8063): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
E/AndroidRuntime( 8063): 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
E/AndroidRuntime( 8063): 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
E/AndroidRuntime( 8063): 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
E/AndroidRuntime( 8063): 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
E/AndroidRuntime( 8063): 	,	... 9 more
E/AndroidRuntime( 8063): 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/PCWClientS18/PCWClientS18.apk'
E/AndroidRuntime( 8063): 		... 27 more
E/AndroidRuntime( 8063): 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/PCWClientS18/arm/PCWClientS18.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
E/AndroidRuntime( 8063): 		... 27 more
E/AndroidRuntime( 8063): 	Caused by: java.io.IOException: 
E/AndroidRuntime( 8063): 		... 27 more
E/AndroidRuntime( 8063): 	Suppressed: java.lang.ClassNotFoundException: com.sec.pcw.device.contentprovider.DMProvider
E/AndroidRuntime( 8063): 		at java.lang.Class.classForName(Native Method)
E/AndroidRuntime( 8063): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/AndroidRuntime( 8063): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/AndroidRuntime( 8063): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/AndroidRuntime( 8063): 		... 13 more
E/AndroidRuntime( 8063): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,V/ApplicationPolicy(  765): isApplicationStateBlocked userId 0 pkgname com.sec.pcw.device
,E/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3525/llIIIIlllllIIllIIllI)] java.lang.NullPointerException: Attempt to invoke virtual method 'int android.database.sqlite.SQLiteDatabase.update(java.lang.String, android.content.ContentValues, java.lang.String, java.lang.String[])' on a null object reference
,E/AndroidRuntime(  765): *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
E/AndroidRuntime(  765): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  765): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  765): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  765): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  765): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  765): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  765): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  765): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  765): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  765): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  765): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  765): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  765): 	... 5 more
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  765): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:535)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIlIlIIIIIIIlIIlll(llIIIIlllllIIllIIllI:3003)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:640)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1387)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:535)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIlIlIIIIIIIlIIlll(llIIIIlllllIIllIIllI:3003)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:640)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1387)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteOpenHelper( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,I/EventHub(  765): Removing device '/dev/input/event8' due to inotify event
,E/android.os.Debug(  765): ro.product_ship = true
E/android.os.Debug(  765): ro.debug_level = 0x4f4c
,E/AndroidRuntime(  765): Error reporting crash
E/AndroidRuntime(  765): java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
E/AndroidRuntime(  765): 	at android.os.StatFs.doStat(StatFs.java:46)
E/AndroidRuntime(  765): 	at android.os.StatFs.restat(StatFs.java:56)
E/AndroidRuntime(  765): 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
E/AndroidRuntime(  765): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
E/AndroidRuntime(  765): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/AndroidRuntime(  765): 	at com.android.server.am.ActivityManagerService$23.run(ActivityManagerService.java:15135)
E/AndroidRuntime(  765): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15142)
E/AndroidRuntime(  765): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14730)
E/AndroidRuntime(  765): 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14714)
E/AndroidRuntime(  765): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime(  765): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime(  765): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/AndroidRuntime(  765): Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
E/AndroidRuntime(  765): 	at libcore.io.Posix.statvfs(Native Method)
E/AndroidRuntime(  765): 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
E/AndroidRuntime(  765): 	at android.system.Os.statvfs(Os.java:473)
E/AndroidRuntime(  765): 	at android.os.StatFs.doStat(StatFs.java:44)
E/AndroidRuntime(  765): 	... 11 more
I/Process (  765): Sending signal. PID: 765 SIG: 9
,I/System.out( 8016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out( 8016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/System.out( 8016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 8016): Tagging socket 50 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8016, getuid(): 10025
,I/qtaguid ( 8016): Tagging socket 53 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8016, getuid(): 10025
,I/qtaguid ( 8016): Tagging socket 54 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8016, getuid(): 10025
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:535)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lllllIlIlIIIIIIIIlIl(llIIIIlllllIIllIIllI:3145)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1434)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1407)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
E/Zygote  ( 8086): MountEmulatedStorage()
I/libpersona( 8086): KNOX_SDCARD checking this for 10039
E/Zygote  ( 8086): v2
I/libpersona( 8086): KNOX_SDCARD not a persona
E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.d,atabase.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1064)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2583)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:535)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.lllllIlIlIIIIIIIIlIl(llIIIIlllllIIllIIllI:3145)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1434)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1407)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteOpenHelper( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,E/SQLiteLog( 7435): (28) failed to open "/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7435): Failed to open database '/data/user/0/com.wssyncmldm/databases/wssdmdatabase.db'.
E/SQLiteDatabase( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteDatabase( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:533)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2579)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:488)
E/SQLiteDatabase( 7435): 	at com.wssyncmldm.db.file.XDB.lIllIllllIIIlllIlllI(llIIIIlllllIIllIIllI:3503)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1450)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1407)
E/SQLiteDatabase( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteDatabase( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteDatabase( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteDatabase( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteDatabase( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteDatabase( 7435): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 7435): Couldn't open wssdmdatabase.db for writing (will try read-only):
E/SQLiteOpenHelper( 7435): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 7435): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
E/SQLiteOpenHelper( 7435): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7435): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.XDMDbContentProvider.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:41)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:533)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:2579)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.IIIIllIlIIlIIIIlllIl(llIIIIlllllIIllIIllI:488)
E/SQLiteOpenHelper( 7435): 	at com.wssyncmldm.db.file.XDB.lIllIllllIIIlllIlllI(llIIIIlllllIIllIIllI:3503)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIlIllllllllllllllI(llIIIIlllllIIllIIllI:1450)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llllllIllIlIlllIIlIl(llIIIIlllllIIllIIllI:1407)
E/SQLiteOpenHelper( 7435): 	at IlIlIlllIIlllIlIlIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:122)
E/SQLiteOpenHelper( 7435): 	at IIIlIllIlIIIIIlIIIll.lllIlIlIIIllIIlIllIl(llIIIIlllllIIllIIllI:473)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:935)
E/SQLiteOpenHelper( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
E/SQLiteOpenHelper( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
E/SQLiteOpenHelper( 7435): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
E/SQLiteOpenHelper( 7435): 	at java.lang.Thread.run(Thread.java:818)
,W/SQLiteOpenHelper( 7435): Opened wssdmdatabase.db in read-only mode
,I/art     (  349): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 302us total 14.733ms
,I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 9.492ms
,I/SELinux ( 8086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 8086): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
E/SELinux ( 8086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  349): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 572us total 10.008ms
,E/installd(  314): eof
E/installd(  314): failed to read size
I/installd(  314): closing connection
,I/ServiceManager(  264): service 'backup' died
I/ServiceManager(  264): service 'appwidget' died
I/ServiceManager(  264): service 'voiceinteraction' died
I/ServiceManager(  264): service 'SecExternalDisplayService' died
I/ServiceManager(  264): service 'diskstats' died
I/ServiceManager(  264): service 'jobscheduler' died
I/ServiceManager(  264): service 'wifi' died
I/ServiceManager(  264): service 'msapwifi' died
I/ServiceManager(  264): service 'wifiscanner' died
I/ServiceManager(  264): service 'rttmanager' died
W/AudioFlinger(  309): power manager service died !!!
I/ServiceManager(  264): service 'connectivity' died
W/AudioCache(  309): clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
I/ServiceManager(  264): service 'sb_service' died
I/ServiceManager(  264): service 'servicediscovery' died
I/ServiceManager(  264): service 'updatelock' died
I/ServiceManager(  264): service 'notification' died
I/ServiceManager(  264): service 'devicestoragemonitor' died
I/ServiceManager(  264): service 'location' died
I/ServiceManager(  264): service 'country_detector' died
I/ServiceManager(  264): service 'search' died
I/ServiceManager(  264): service 'dropbox' died
I/ServiceManager(  264): service 'wallpaper' died
I/ServiceManager(  264): service 'sec_analytics' died
I/ServiceManager(  264): service 'enterprise_policy' died
I/ServiceManager(  264): service 'statusbar' died
I/ServiceManager(  264): service 'clipboard' died
I/ServiceManager(  264): service 'clipboardEx' died
I/ServiceManager(  264): service 'network_management' died
I/SurfaceFlinger(  266): restart the boot-animation @ binderDied
I/ServiceManager(  264): service 'ABTPersistenceService' died
I/ServiceManager(  264): service 'textservices' died
I/ServiceManager(  264): service 'network_score' died
I/ServiceManager(  264): service 'netstats' died
I/ServiceManager(  264): service 'audio' died
I/ServiceManager(  264): service 'DockObserver' died
I/ServiceManager(  264): service 'usb' died
I/ServiceManager(  264): service 'serial' died
I/ServiceManager(  264): service 'uimode' died
I/ServiceManager(  264): service 'netpolicy' died
I/ServiceManager(  264): service 'wifip2p' died
I/ServiceManager(  264): service 'tactileassist' died
I/ServiceManager(  264): service 'bluetooth_manager' died
I/ServiceManager(  264): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  264): service 'rcp' died
I/ServiceManager(  264): service 'device_policy' died
I/ServiceManager(  264): service 'harmony_eas_service' died
I/ServiceManager(  264): service 'sdp' died
I/ServiceManager(  264): service 'log_manager_service' died
I/ServiceManager(  264): service 'application_policy' died
I/ServiceManager(  264): service 'wifi_policy' died
W/Sensors ( 1441): sensorservice died [0xafa1e200]
I/ServiceManager(  264): service 'phone_restriction_policy' died
I/ServiceManager(  264): service 'remoteinjection' died
I/ServiceManager(  264): service 'mum_container_policy' died
I/ServiceManager(  264): service 'enterprise_billing_policy' died
I/ServiceManager(  264): service 'knox_timakeystore_policy' died
I/ServiceManager(  264): service 'mDNIe' died
I/ServiceManager(  264): service 'spengestureservice' died
I/ServiceManager(  264): service 'quickconnect' died
I/ServiceManager(  264): service 'samplingprofiler' died
I/ServiceManager(  264): service 'commontime_management' died
I/ServiceManager(  264): service 'dreams' died
I/ServiceManager(  264): service 'print' died
I/ServiceManager(  264): service 'restrictions' died
I/ServiceManager(  264): service 'media_session' died
I/ServiceManager(  264): service 'media_router' died
I/ServiceManager(  264): service 'trust' died
I/ServiceManager(  264): service 'fingerprint' died
I/ServiceManager(  264): service 'launcherapps' died
I/ServiceManager(  264): service 'voip' died
I/ServiceManager(  264): service 'media_projection' died
I/ServiceManager(  264): service 'imms' died
I/ServiceManager(  264): service 'input_method' died
I/ServiceManager(  264): service ',accessibility' died
I/ServiceManager(  264): service 'motion_recognition' died
I/ServiceManager(  264): service 'cover' died
I/ServiceManager(  264): service 'mount' died
I/ServiceManager(  264): service 'lock_settings' died
I/ServiceManager(  264): service 'persona_policy' died
I/ServiceManager(  264): service 'alarm' died
I/ServiceManager(  264): service 'battery' died
I/ServiceManager(  264): service 'usagestats' died
I/ServiceManager(  264): service 'webviewupdate' died
I/ServiceManager(  264): service 'scheduling_policy' died
I/ServiceManager(  264): service 'telephony.registry' died
I/ServiceManager(  264): service 'batterystats' died
I/ServiceManager(  264): service 'appops' died
I/ServiceManager(  264): service 'power' died
I/ServiceManager(  264): service 'display' died
I/ServiceManager(  264): service 'entropy' died
I/ServiceManager(  264): service 'SEAMService' died
I/ServiceManager(  264): service 'persona' died
I/ServiceManager(  264): service 'account' died
I/ServiceManager(  264): service 'content' died
I/ServiceManager(  264): service 'DirEncryptService' died
I/ServiceManager(  264): service 'ReactiveService' died
I/ServiceManager(  264): service 'sedenial' died
I/ServiceManager(  264): service 'vibrator' died
I/ServiceManager(  264): service 'tima' died
I/ServiceManager(  264): service 'cepproxyks' died
I/ServiceManager(  264): service 'CustomFrequencyManagerService' died
I/ServiceManager(  264): service 'samsung.smartfaceservice' died
I/ServiceManager(  264): service 'consumer_ir' died
I/ServiceManager(  264): service 'enterprise_license_policy' died
I/ServiceManager(  264): service 'context_aware' died
I/ServiceManager(  264): service 'scontext' died
I/ServiceManager(  264): service 'barbeam' died
I/ServiceManager(  264): service 'multiwindow_facade' died
I/ServiceManager(  264): service 'window' died
I/ServiceManager(  264): service 'input' died
I/ServiceManager(  264): service 'procstats' died
I/ServiceManager(  264): service 'dbinfo' died
I/ServiceManager(  264): service 'user' died
I/ServiceManager(  264): service 'cpuinfo' died
I/ServiceManager(  264): service 'meminfo' died
I/ServiceManager(  264): service 'package' died
I/ServiceManager(  264): service 'gfxinfo' died
I/ServiceManager(  264): service 'permission' died
I/ServiceManager(  264): service 'hardware' died
I/ServiceManager(  264): service 'edmnativehelper' died
I/ServiceManager(  264): service 'activity' died
I/ServiceManager(  264): service 'mdm.remotedesktop' died
W/Sensors ( 1404): sensorservice died [0xaf0f8900]
I/ServiceManager(  264): service 'sensorservice' died
W/Sensors ( 1425): sensorservice died [0xaf07f180]
W/Sensors ( 1909): sensorservice died [0xaf0f6a00]
E/WifiManager( 1425): Channel connection lost
E/WifiManager( 1749): Channel connection lost
I/SurfaceFlinger(  266): id=7 Removed JmageWallpa (4/8)
I/SurfaceFlinger(  266): id=7 Removed JmageWallpa (-2/8)
,I/SurfaceFlinger(  266): id=9 Removed TtatusBar (6/7)
I/SurfaceFlinger(  266): id=13 Removed Mauncher (5/6)
I/SurfaceFlinger(  266): id=13 Removed Mauncher (-2/6)
I/SurfaceFlinger(  266): id=9 Removed TtatusBar (-2/6)
I/SurfaceFlinger(  266): id=10 Removed DolorFade (5/5)
I/SurfaceFlinger(  266): id=10 Removed DolorFade (-2/5)
E/WifiManager( 7435): Channel connection lost
W/Sensors ( 1749): sensorservice died [0xaf071ec0]
,I/SurfaceFlinger(  266): id=2 Removed GocusedStac (4/4)
I/SurfaceFlinger(  266): id=3 Removed EimLayer (0/3)
I/SurfaceFlinger(  266): id=4 Removed EimLayer (0/2)
I/SurfaceFlinger(  266): id=5 Removed EimLayer (0/1)
I/SurfaceFlinger(  266): id=6 Removed EimLayer (0/0)
I/SurfaceFlinger(  266): id=2 Removed GocusedStac (-2/0)
I/SurfaceFlinger(  266): id=3 Removed EimLayer (-2/0)
I/SurfaceFlinger(  266): id=4 Removed EimLayer (-2/0)
,E/WifiManager( 1309): Channel connection lost
,F/libc    ( 8086): Fatal signal 7 (SIGBUS), code 2, fault addr 0x74221bfe in tid 8086 (pp.galaxyfinder)
E/WifiManager( 1191): Channel connection lost
,I/SurfaceFlinger(  266): id=5 Removed EimLayer (-2/0)
W/Sensors ( 1191): sensorservice died [0xaf90c240]
W/Sensors ( 1772): sensorservice died [0xaf0fd300]
,I/SurfaceFlinger(  266): id=6 Removed EimLayer (-2/0)
,D/SurfaceFlinger(  266): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  266): hwc_blank: Unblanking display: 0
,E/AndroidRuntime( 8063): Error reporting crash
E/AndroidRuntime( 8063): android.os.DeadObjectException
E/AndroidRuntime( 8063): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 8063): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 8063): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 8063): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 8063): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 8063): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 8063): Sending signal. PID: 8063 SIG: 9
,E/WifiManager( 3838): Channel connection lost
,E/WifiManager( 6868): Channel connection lost
,E/AndroidRuntime( 5325): FATAL EXCEPTION: AppProvider
E/AndroidRuntime( 5325): Process: com.samsung.android.app.galaxyfinder:tagService, PID: 5325
E/AndroidRuntime( 5325): java.lang.RuntimeException: Package manager has died
E/AndroidRuntime( 5325): 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:608)
E/AndroidRuntime( 5325): 	at android.app.ApplicationPackageManager.queryIntentActivities(ApplicationPackageManager.java:590)
E/AndroidRuntime( 5325): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.updateApplicationsList(AppProvider.java:461)
E/AndroidRuntime( 5325): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider.access$300(AppProvider.java:56)
E/AndroidRuntime( 5325): 	at com.samsung.android.app.galaxyfinder.applicationprovider.AppProvider$UpdateHandler.handleMessage(AppProvider.java:203)
E/AndroidRuntime( 5325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5325): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 5325): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5325): Caused by: android.os.DeadObjectException
E/AndroidRuntime( 5325): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5325): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5325): 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentActivities(IPackageManager.java:3168)
E/AndroidRuntime( 5325): 	at android.app.ApplicationPackageManager.queryIntentActivitiesAsUser(ApplicationPackageManager.java:598)
E/AndroidRuntime( 5325): 	... 7 more
,E/AndroidRuntime( 5325): Error reporting crash
E/AndroidRuntime( 5325): android.os.DeadObjectException
E/AndroidRuntime( 5325): 	at android.os.BinderProxy.transactNative(Native Method)
E/AndroidRuntime( 5325): 	at android.os.BinderProxy.transact(Binder.java:496)
E/AndroidRuntime( 5325): 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4650)
E/AndroidRuntime( 5325): 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
E/AndroidRuntime( 5325): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/AndroidRuntime( 5325): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
I/Process ( 5325): Sending signal. PID: 5325 SIG: 9
,W/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(69/llIIIIlllllIIllIIllI)] NetworkInfo is null
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,W/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(69/llIIIIlllllIIllIIllI)] NetworkInfo is null
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,W/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(69/llIIIIlllllIIllIIllI)] NetworkInfo is null
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,W/DBG_DM  ( 7435): [lllllllIlllIIlllIlIl(69/llIIIIlllllIIllIIllI)] NetworkInfo is null
,I/DBG_DM  ( 7435): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/DBG_DM  ( 7435): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 1
,I/DBG_DM  ( 7435): [llIlIIIIlllIlllllIll(1554/llIIIIlllllIIllIIllI)] XEVENT_DL_TCPIP_OPEN
,I/DBG_DM  ( 7435): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 30
,I/DBG_DM  ( 7435): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 1 / Notification IndicatorState : 2
,W/UserManager( 7435): Could not get user list
W/UserManager( 7435): android.os.DeadObjectException
W/UserManager( 7435): 	at android.os.BinderProxy.transactNative(Native Method)
W/UserManager( 7435): 	at android.os.BinderProxy.transact(Binder.java:496)
W/UserManager( 7435): 	at android.os.IUserManager$Stub$Proxy.getProfiles(IUserManager.java:587)
W/UserManager( 7435): 	at android.os.UserManager.getProfiles(UserManager.java:866)
W/UserManager( 7435): 	at android.app.ApplicationPackageManager.getUserIfProfile(ApplicationPackageManager.java:2115)
W/UserManager( 7435): 	at android.app.ApplicationPackageManager.getUserBadgeForDensity(ApplicationPackageManager.java:1211)
W/UserManager( 7435): 	at android.app.Notification$Builder.getProfileBadgeDrawable(Notification.java:3001)
W/UserManager( 7435): 	at android.app.Notification$Builder.hasThreeLines(Notification.java:3226)
W/UserManager( 7435): 	at android.app.Notification$Builder.build(Notification.java:3773)
W/UserManager( 7435): 	at android.support.v4.app.llIIllIllIIIIllIIIlI.llllIIIllIlIIIIllllI(llIIIIlllllIIllIIllI:109)
W/UserManager( 7435): 	at android.support.v4.app.IlllllIIIIIIIIllIIIl.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:739)
W/UserManager( 7435): 	at android.support.v4.app.lIlIlIIIIlIIlIlIIlII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1503)
W/UserManager( 7435): 	at com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:355)
W/UserManager( 7435): 	at com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:155)
W/UserManager( 7435): 	at llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI(llIIIIlllllIIllIIllI:1558)
W/UserManager( 7435): 	at lllllllllllIlllllIIl.handleMessage(llIIIIlllllIIllIIllI:91)
W/UserManager( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:98)
W/UserManager( 7435): 	at android.os.Looper.loop(Looper.java:145)
W/UserManager( 7435): 	at llIlIIIIlllIlllllIll.run(llIIIIlllllIIllIIllI:106)
W/UserManager( 7435): 	at java.lang.Thread.run(Thread.java:818)
,I/DEBUG   (  296): failed to change ownership of /data/tombstones: Read-only file system
E/        (  296): ro.product_ship = true
E/        (  296): ro.debug_level = 0x4f4c
,E/audit_log( 1843): File locking failed. error= Bad file number
,I/Zygote  (  349): Process 8086 exited due to signal (7)
,I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  266): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  266): hwc_blank: Done unblanking display: 0
,I/qtaguid ( 8016): Untagging socket 50
,I/qdhwcomposer(  266): handle_blank_event: dpy:0 panel power state: 0
,I/SurfaceFlinger(  266): Disp[0] Orientation 0=>0
,I/qtaguid ( 8016): Untagging socket 54
,I/qtaguid ( 8016): Untagging socket 53
,D/Volley  ( 8016): [1267] DiskBasedCache.put: Could not clean up file /data/data/sstream.app/cache/volley/852217856-371018006
,D/Volley  ( 8016): [1268] DiskBasedCache.put: Could not clean up file /data/data/sstream.app/cache/volley/-2107138505379496909
,D/Volley  ( 8016): [1270] DiskBasedCache.put: Could not clean up file /data/data/sstream.app/cache/volley/769804234985904208
,E/SharedPreferencesImpl( 8016): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
,E/SharedPreferencesImpl( 8016): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
,E/SharedPreferencesImpl( 8016): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
,E/SharedPreferencesImpl( 8016): Couldn't create directory for SharedPreferences file /data/data/sstream.app/shared_prefs/shared_prefs.xml
,E/SQLiteLog( 8016): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 8016): (3850) statement aborts at 16: [DELETE FROM config WHERE stream_id=?] disk I/O error
,D/AndroidRuntime( 8016): Shutting down VM
,D/HockeyApp( 8016): Writing unhandled exception to: /data/data/sstream.app/files/331a5b19-e225-40e1-acd6-b7c399763681.stacktrace
,E/HockeyApp( 8016): Error saving exception stacktrace!
E/HockeyApp( 8016): 
E/HockeyApp( 8016): java.io.FileNotFoundException: /data/data/sstream.app/files/331a5b19-e225-40e1-acd6-b7c399763681.stacktrace: open failed: EROFS (Read-only file system)
E/HockeyApp( 8016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/HockeyApp( 8016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/HockeyApp( 8016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/HockeyApp( 8016): 	at java.io.FileWriter.<init>(FileWriter.java:80)
E/HockeyApp( 8016): 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
E/HockeyApp( 8016): 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
E/HockeyApp( 8016): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/HockeyApp( 8016): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/HockeyApp( 8016): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/HockeyApp( 8016): 	at libcore.io.Posix.open(Native Method)
E/HockeyApp( 8016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/HockeyApp( 8016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/HockeyApp( 8016): 	... 7 more

```
