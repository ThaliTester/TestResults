#### Test 62509094aba5909_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  290): DCD OFF
D/AndroidRuntime( 5619): 
D/AndroidRuntime( 5619): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5619): CheckJNI is OFF
D/AndroidRuntime( 5619): readGMSProperty: start
D/AndroidRuntime( 5619): readGMSProperty: already setted!!
D/AndroidRuntime( 5619): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5619): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5619): readGMSProperty: end
D/AndroidRuntime( 5619): addProductProperty: start
E/AffinityControl( 5619): AffinityControl: registerfunction enter
D/AndroidRuntime( 5619): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : -2122120936
E/Zygote  ( 5632): MountEmulatedStorage()
E/Zygote  ( 5632): v2
I/libpersona( 5632): KNOX_SDCARD checking this for 10338
I/libpersona( 5632): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5632 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 5632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1479
D/AndroidRuntime( 5619): Shutting down VM
I/SELinux ( 5632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5632): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 5632): TimaSignature is unavailable
D/ActivityThread( 5632): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{358abb13 token=android.os.BinderProxy@fb85d5c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 5632): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 5632): Time to load native libraries: 2 ms (timestamps 1990-1992)
I/LibraryLoader( 5632): Expected native library version number "",actual native library version number ""
W/art     ( 5619): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 5632): Binding Chromium to main looper Looper (main, tid 1) {10f12997}
,I/LibraryLoader( 5632): Expected native library version number "",actual native library version number ""
,I/chromium( 5632): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5632): Initializing chromium process, singleProcess=true
,W/art     ( 5632): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 5632): ApplicationContext is null in ApplicationStatus
,W/chromium( 5632): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5632): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5632): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5632): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5632): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5632): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5632): Local Branch: 
I/Adreno-EGL( 5632): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5632): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5632):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/BluetoothAdapter( 5632): 801830896: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5632): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5632): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 5632): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 5632): *FMB* installDecor flags : -2139027200
D/SystemWebViewEngine( 5632): CordovaWebView is running on device made by: samsung
W/art     ( 5632): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5632): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{10ea8bc4 u0 com.test.thalitest/.MainActivity t23}
D/OpenGLRenderer( 5632): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 5632): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 5632): updateVisibility : ActivityRecord{6000b4c token=android.os.BinderProxy@3cde689e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 5632): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 5632): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 5632
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 5632): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5632): Initialized EGL, version 1.4
D/OpenGLRenderer( 5632): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5632): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
I/ActivityManager( 1018): Displayed Component not be shown by security: +671ms (total +1m42s158ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{10ea8bc4 u0 com.test.thalitest/.MainActivity t23} time:212520
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 5632): showStatusIcon on inactive InputConnection
I/Timeline( 5632): Timeline: Activity_idle id: android.os.BinderProxy@3cde689e time:212526
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1770): getCurrentCandidateView
W/BindingManager( 5632): Cannot call determinedVisibility() - never saw a connection for the pid: 5632
D/SamsungIME( 1770): Dismiss ExpandCandiate
I/SamsungIME( 1770): getDebugLevel  : 0x4f4c
I/SamsungIME( 1770): getDebugLevel  : 0x4f4c
I/SamsungIME( 1770): KeybaordView init() : load resources
I/SamsungIME( 1770): getCurrentKeyboard
I/SamsungIME( 1770): getTextKeyboard
D/SamsungIME( 1770): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 5632): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5632): JniHelper::setJavaVM(0xb7dd9448), pthread_self() = -1204621104
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5632): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19792005 added. We now have 1 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632): setBluetoothMacAddress: 08:EC:A9:50:75:41
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5632): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5632): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@470b781 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5632): addListener: New listener added - the number of listeners is now 1
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5632): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5632): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5632): setDiscoveryMode: Discovery mode BLE is supported
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5632): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5632): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
I/chromium( 5632): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/art     ( 5632): Background sticky concurrent mark sweep GC freed 45909(4MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 5.058ms total 37.793ms
,W/jxcore-log( 5632): Initializing JXcore engine
W/jxcore-log( 5632): JXcore engine is ready
,E/audit   ( 1799): type=1400 msg=audit(1457686712.250:203): avc:  denied  { ioctl } for  pid=5683 comm="Thread-950" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1799):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1799): type=1300 msg=audit(1457686712.250:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9e9f98f8 items=0 ppid=312 ppcomm=main pid=5683 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm="Thread-950" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1799): type=1320 msg=audit(1457686712.250:203): 
,W/jxcore-log( 5632): Starting JXcore engine
,W/jxcore-log( 5632): Platform android
W/jxcore-log( 5632): 
W/jxcore-log( 5632): Process ARCH arm
W/jxcore-log( 5632): 
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 5632): JXcore Cordova bridge is ready!,
I/jxcore-log( 5632): 
W/jxcore-log( 5632): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5632): execute: REQUEST_ACCESS_COARSE_LOCATION
,D/SSRM:n  ( 1018): SIOP:: AP = 280,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 5632): INFO testUtils Toggling radios to: true
I/jxcore-log( 5632): 
,D/BluetoothAdapter( 5632): enable()
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5632, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 1018): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5632, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
W/BluetoothManagerService( 1018): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
W/BluetoothManagerService( 1018): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/BluetoothManagerService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
D/SettingsProvider( 1018): name = bluetooth_on
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/jxcore-log( 5632): Unit Test app is loaded
I/jxcore-log( 5632): 
,E/Zygote  ( 5688): MountEmulatedStorage(),
E/Zygote  ( 5688): v2
I/libpersona( 5688): KNOX_SDCARD checking this for 1002
I/libpersona( 5688): KNOX_SDCARD not a persona
,I/SELinux ( 5688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5688 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,I/SELinux ( 5688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5688): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 5632): [INFO:CONSOLE(66)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (66)
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=5632, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=5632, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5632, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,D/TimaKeyStoreProvider( 5688): TimaSignature is unavailable
,D/ActivityThread( 5688): Added TimaKeyStore provider
,I/WifiService( 1018): disconnect: pid=5632, uid=10338
,E/WifiHW  ( 1018): ##################### set firmware type 0 #####################
,W/ResourcesManager( 5688): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/BluetoothA2dpSinkServiceJni( 5688): register_com_android_bluetooth_a2dp_sink
,D/BtSettings.ProfileConfig( 5688): Adding GattService
,D/BtSettings.ProfileConfig( 5688): Adding HeadsetService
D/BtSettings.ProfileConfig( 5688): Adding A2dpService
D/BtSettings.ProfileConfig( 5688): Adding HidService
D/BtSettings.ProfileConfig( 5688): Adding HealthService
,D/BtSettings.ProfileConfig( 5688): Adding PanService
D/BtSettings.ProfileConfig( 5688): Adding BluetoothMapService
D/BtSettings.ProfileConfig( 5688): Adding SapService,
D/BtSettings.ProfileConfig( 5688): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 5688): Adding A2dpSinkService
D/BtSettings.ProfileConfig( 5688): Adding SapClientService
D/BtSettings.ProfileConfig( 5688): Adding HidDevService
I/BtSettings.ProfileConfig( 5688): *********Initializing Bluetooth Profile Settings*******
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService,
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.pan.PanService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text,
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider( 1018): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/BluetoothAdapterState( 5688): make
,I/bluedroid( 5688): init
,I/BluetoothAdapterState( 5688): Entering OffState
,I/bte_conf( 5688): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 5688): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 5688): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 5688): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 5688): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 5688): get_profile_interface socket
I/bluedroid( 5688): get_profile_interface map_client
,D/BluetoothAdapterService( 5688): checkAddrForIOP: Loading from conf
,I/GKI_LINUX( 5688): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterProperties( 5688): Address is:08:EC:A9:50:75:41
,E/BluetoothServiceJni( 5688): populateRssiValuesNative
I/bluedroid( 5688): getModelRssiValues
E/BluetoothServiceJni( 5688): model_rssi_values_callback: low = -70, mid = -60, high = 127
,D/BluetoothAdapterProperties( 5688): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/SettingsProvider( 1018): name = bluetooth_name
D/BluetoothAdapterProperties( 5688): Name is: A3-1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/bluedroid( 5688): config_hci_snoop_log
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService( 1018): Ble is always on enable gatt
,I/BluetoothManagerService( 1018): enableGattForLeMode, doBind called
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,E/DevicePolicyManagerService( 1018): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider( 1018): uri = 3 selection = isBluetoothEnabled
,D/BluetoothAdapterState( 5688): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 5688): Setting state to 11
I/BluetoothAdapterState( 5688): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 5688): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5688): updateAdapterState state is 11
,D/BluetoothAdapterService( 5688): Autoconnection is available 
D/BluetoothAdapterService( 5688): updateAdapterState prevState = 10newState = 11
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 1018): [BT Setting State] State =11
,D/BluetoothSecureManager( 5688): getInstant: null
D/BluetoothSecureManager( 5688): calling getMethod for getService
,D/BluetoothSecureManager( 5688): calling getService
,I/BtGatt.JNI( 5688): classInitNative(L900): classInitNative: Success!
,D/BluetoothSecureManager( 5688): getService return binder: android.os.BinderProxy@fc9b48f
,D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1181):  getBluetoothState : 11
,D/BluetoothSecureManagerService( 1018): isSecureModeEnabled
D/BluetoothSecureManagerService( 1018): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 5688): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
D/STATUSBAR-QSTileView( 1181): onStateChanged: Bluetooth
I/SamsungIME( 1770): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5688): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 5688): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
W/BluetoothAdapterService( 5688): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5688): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 5688): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
D/BluetoothBondStateMachine( 5688): make
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
,D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.gatt.GattService
I/BluetoothBondStateMachine( 5688): StableState(): Entering Off State
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.hfp.HeadsetService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BtGatt.DebugUtils( 5688): handleDebugAction() action=null
,D/BtGatt.GattService( 5688): Received start request. Starting profile...
D/BtGatt.GattService( 5688): start()
D/BtGatt.GattService( 5688): start()
I/bluedroid( 5688): get_profile_interface gatt
W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtGatt.AdvertiseManager( 5688): advertise manager created
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.hid.HidService
,D/BtGatt.GattService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothNotiBroadcastReceiver( 1294): onReceive
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 5688): Received start request. Starting profile...
,D/HeadsetService( 5688): start()
,I/BluetoothHeadsetServiceJni( 5688): classInitNative: succeeds,
,D/HeadsetStateMachine( 5688): make
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,E/HeadsetStateMachine( 5688): # of Max HF connection is 2
V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.pan.PanService
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5731): MountEmulatedStorage()
I/libpersona( 5731): KNOX_SDCARD checking this for 10055
E/Zygote  ( 5731): v2
I/libpersona( 5731): KNOX_SDCARD not a persona
,I/SELinux ( 5731): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5731 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a,
,I/SELinux ( 5731): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5731): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
W/BluetoothAdapterService( 5688): Not skipping com.android.bluetooth.map.BluetoothMapService
I/bluedroid( 5688): get_profile_interface handsfree
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5688): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5688): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5688): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5688): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 5688): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 5688): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 5688): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 5688): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,I/DualScoManager( 5688): Instantiating Dual Sco Manager
,I/DualScoManager( 5688): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 5688): createCMTIContentObservers
D/SettingsProvider( 1018): name = bluetooth_hfp_allowed_bvra
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/HeadsetStateMachine( 5688): Enter Disconnected: -2
,D/HeadsetService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,D/BluetoothA2dp( 1018): Proxy object connected
,D/A2dpService( 5688): Received start request. Starting profile...
D/A2dpService( 5688): start()
,D/HeadsetStateMachine( 5688): Clear mHeadsetBrsf
D/HeadsetStateMachine( 5688): map size, before remove : 0
D/HeadsetStateMachine( 5688): map size, after remove: 0
I/BluetoothAvrcpServiceJni( 5688): classInitNative: succeeds
I/bluedroid( 5688): get_profile_interface avrcp
,D/TimaKeyStoreProvider( 5731): TimaSignature is unavailable
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/ActivityThread( 5731): Added TimaKeyStore provider
,E/RemoteController( 5688): Cannot set synchronization mode on an unregistered RemoteController
,I/Avrcp   ( 5688):  Updating now playing list upon AVRCP Start
,D/BluetoothMediaBrowser( 5688):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/BluetoothA2dpServiceJni( 5688): classInitNative: succeeds
D/A2dpStateMachine( 5688): make
,I/bluedroid( 5688): get_profile_interface a2dp
,I/GKI_LINUX( 5688): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,E/bt-btif ( 5688): warning : media task started media_task_refcnt 1 
,D/A2dpService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
D/A2dpStateMachine( 5688): Enter Disconnected: -2
,E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,D/BluetoothMediaBrowser( 5688): no now playing list
D/BluetoothMediaBrowser( 5688):  getNowPlayingId now playing id : -1
,I/BluetoothHidServiceJni( 5688): classInitNative: succeeds,
,D/UserAnalysis.PlaceProvider( 5731): PlaceProvider onCreate()
,D/HidService( 5688): Received start request. Starting profile...
D/HidService( 5688): start()
I/bluedroid( 5688): get_profile_interface hidhost
D/HidService( 5688): setHidService(): set to: null
D/HidService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
I/BluetoothHealthServiceJni( 5688): classInitNative: succeeds
,D/HealthService( 5688): Received start request. Starting profile...
D/HealthService( 5688): start()
,I/bluedroid( 5688): get_profile_interface health
,D/HealthService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
I/BluetoothPanServiceJni( 5688): classInitNative(L105): succeeds
,D/BluetoothPan( 1018): BluetoothPAN Proxy object connected
,D/PanService( 5688): Received start request. Starting profile...
D/PanService( 5688): start()
D/BluetoothPanServiceJni( 5688): initializeNative(L110): pan
I/bluedroid( 5688): get_profile_interface pan
,D/Tethering( 1018): interfaceAdded wlan0
,I/WifiHW  (  280): wifi_change_fw_path(): fwpath = sta
D/SoftapController(  280): Softap fwReload - Ok
,D/PanService( 5688): mStartError = false
,D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,D/HeadsetStateMachine( 5688): Proxy object connected
,D/HeadsetStateMachine( 5688): Try to query the phonestate on bind
,I/Telecom ( 1432): BluetoothPhoneService: queryPhoneState
,I/Telecom ( 1432): BluetoothPhoneService: handleMessage(7) / param 0
,I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState
,D/UserAnalysis.SecureDbManager( 5731): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5731): SecurePlaceDbHelper() 
D/UserAnalysis( 5731): Create SecureDbHelper
,I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,D/CommandListener(  280): Setting iface cfg
D/CommandListener(  280): Trying to bring down wlan0
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1181): updateTetherState():false, false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/IntelligenceServiceApplication( 5731): onCreate()
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): InitialState.processMessage what=4
D/Tethering( 1018): interfaceAdded p2p0
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
E/WifiHW  ( 1018): supplicant_name : p2p_supplicant
D/Tethering( 1018): p2p0 is not a tetherable iface, ignoring
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1181): updateTetherState():false, false
,D/WifiMonitor( 1018): startMonitoring(wlan0) with mConnected = false
,I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(2)
,V/NetworkStats( 1018): performPollLocked() took 12ms
D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/IntelligenceServiceApplication( 5731): no applications having user consent for prediction
,D/HotspotTile( 1181): onReceive : 2, 0
,W/BluetoothHeadset( 1432): Proxy not attached to service
,I/Telecom ( 1432): BluetoothPhoneService: Result of Message : true
D/HeadsetPhoneState( 5688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
I/ActivityManager( 1018): Killing 4683:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
D/HeadsetStateMachine( 5688): Disconnected process message: 11
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss,
D/NtpTrustedTime( 1018): forceRefresh Fail.
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated,
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
V/NetworkStats( 1018): performPollLocked() took 3ms
D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,D/WifiCredService( 1294): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/PlaceDetection v1.0.19 ( 5731): [PlaceDetection::stopService] Service stopped.
,D/BluetoothMapService( 5688): Received start request. Starting profile...
D/BluetoothMapService( 5688): start()
,D/BluetoothMapService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,I/BluetoothSAPServiceJni( 5688): classInitNative(L204): succeeds
,D/SapService( 5688): Received start request. Starting profile...
,D/SapService( 5688): start()
D/BluetoothSAPServiceJni( 5688): initializeNative(L209): sap
I/bluedroid( 5688): get_profile_interface sap
D/SapService( 5688): mStartError = false
D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
D/HeadsetPhoneState( 5688): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5688): Signal level : previous=0 curr=0
,D/HeadsetStateMachine( 5688): Disconnected process message: 18
E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothA2dp( 5688): Proxy object connected
D/BluetoothAdapterService( 5688): Bluetooth A2dp source service connected
V/HeadsetService( 5688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetStateMachine( 5688): Disconnected process message: 10
D/HeadsetPhoneState( 5688): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5688): Disconnected process message: 11
E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/AuthorizationBluetoothService( 1694): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 5731): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/Zygote  ( 5758): MountEmulatedStorage()
E/Zygote  ( 5758): v2
I/libpersona( 5758): KNOX_SDCARD checking this for 10141
I/libpersona( 5758): KNOX_SDCARD not a persona
,I/SELinux ( 5758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5758 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/wpa_supplicant( 5756): [wpa_supplicant_init]: use SECRIL
,I/wpa_supplicant( 5756): Successfully initialized wpa_supplicant
,I/SecureStorage( 5756): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4683/cgroup.procs: No such file or directory
I/PowerManagerService( 1018): [PWL] Off : 105s ago
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3342): Starting #2
I/Hs20UtilService( 3342): Message received 5011
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SecureStorage( 5756): [INFO]: SPID(0x00000000)This device supports Secure Storage
I/art     (  312): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 23.153ms
I/SecureStorage(  381): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5756
I/SecureStorage(  381): [INFO]: SPID(0x00000000)Received function mask & code: 0x0000010C
I/SecureStorage( 5756): [INFO]: SPID(0x00000000)SS Daemon is running
I/wpa_supplicant( 5756): ssSupport state is = 1
I/wpa_supplicant( 5756): >>>>> GET KEY, IV <<<<<
I/SecureStorage( 5756): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage(  381): [INFO]: SPID(0x00000000)Credentials: uid 1010, gid 1010, pid 5756
I/SecureStorage(  381): [INFO]: SPID(0x00000000)Received function mask & code: 0x00000106
D/TimaKeyStoreProvider( 5758): TimaSignature is unavailable
D/ActivityThread( 5758): Added TimaKeyStore provider
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.556ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.716ms
,E/Zygote  ( 5774): MountEmulatedStorage()
,E/Zygote  ( 5774): v2
I/libpersona( 5774): KNOX_SDCARD checking this for 1000
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5774 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 5774): KNOX_SDCARD not a persona
I/SELinux ( 5774): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 5774): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5774): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 5758): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 5758): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5758): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5758): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5774): TimaSignature is unavailable
D/ActivityThread( 5774): Added TimaKeyStore provider
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 5774): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5774): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5774): StateMachine : Current State = 1
,D/SecurityLogAgent( 5774): StateMachine : Changed Current State = 1
,I/ActivityManager( 1018): Killing 5114:com.samsung.helphub/1000 (adj 15): empty #31
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
E/BluetoothAdapterService(284240279)( 5688): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,I/ActivityManager( 1018): Killing 5130:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/BluetoothAdapterState( 5688): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 5688): enable
,I/bt_hci_bdroid( 5688): init
,I/bt_vendor( 5688): bt-vendor : init
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/bt_vendor( 5688): bt-vendor : get_bt_soc_type
E/bt_vendor( 5688): get_bt_soc_type: Failed to get soc type
I/bt_vendor( 5688): init: Local BD Address : 41:75:50:a9:ec:08
D/bt_userial_mct( 5688): userial_init
I/GKI_LINUX( 5688): gki_task_entry task_id=0 [BTU] starting
,D/BadgeProvider( 5264): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
I/bt_vendor( 5688): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 5688): Starting hciattach daemon
I/bt_vendor( 5688): try to set false
,I/bt_vendor( 5688): bt-vendor : BT_VND_OP_POWER_CTRL: On
I/bt_vendor( 5688): Starting hciattach daemon
I/bt_vendor( 5688): try to set true
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SecureStorage(  381): [INFO]: SPID(0x00000001)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)Processing data has been completed
,D/BadgeProvider( 5264): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5264): sendNotify, [notify] : null
D/BadgeProvider( 5264): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5264): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5264): update, [UpdateCount] : 1
,D/Launcher.Model( 1479): reloadBadges entered.
,I/qcom-bluetooth( 5802): /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,W/libprocessgroup( 1018): failed to kill pid 5130: No such process
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5130/cgroup.procs: No such file or directory
,I/wpa_supplicant( 5756): Ctrl_iface: loading cred from phone
I/SecureStorage( 5756): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage,
,I/qcom-bluetooth( 5808): /system/etc/init.qcom.bt.sh: Transport : smd 
,I/qcom-bluetooth( 5810): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5756
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5756): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5756): ssSupport state is = 1
,I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,E/wpa_supplicant( 5756): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5756): SIM READ ERROR
I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
E/wpa_supplicant( 5756): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5756): SIM READ ERROR
I/wpa_supplicant( 5756): Blacklist: Clear (all) 
I/wpa_supplicant( 5756): wpa_default_ap_write_once,
I/wpa_supplicant( 5756): There is no /data/misc/wifi/default_ap.check. Start copy default ap,
I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5756): getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5756): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
I/wpa_supplicant( 5756): rfkill: Cannot open RFKILL control device
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5114/cgroup.procs: No such file or directory,
,I/qcom-bluetooth( 5812): /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5813): /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,I/qcom-bluetooth( 5814): /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,I/qcom-bluetooth( 5815): /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,I/wpa_supplicant( 5756): wlan0: Setting scan request: 0 sec 100000 usec
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31792(1964KB) AllocSpace objects, 30(480KB) LOS objects, 33% free, 23MB/35MB, paused 2.607ms total 165.053ms
,I/wpa_supplicant( 5756): wlan0: State: DISCONNECTED -> DISCONNECTED,
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5756,
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
I/SecureStorage( 5756): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5756): ssSupport state is = 1,
,I/wpa_supplicant( 5756): Ctrl_iface: loading cred from phone,
I/SecureStorage( 5756): [INFO]: SPID(0x00000001)Checking if this device supports Secure Storage
,I/qcom-bluetooth( 5820): /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:75:41 ,
,I/qcom-bluetooth( 5822): /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)This device supports Secure Storage,
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5756
I/SecureStorage(  381): [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,I/SecureStorage( 5756): [INFO]: SPID(0x00000001)SS Daemon is running
I/wpa_supplicant( 5756): ssSupport state is = 1
I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5756): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5756): SIM READ ERROR,
I/wpa_supplicant( 5756): wpa_default_ap_write_once
I/wpa_supplicant( 5756): There is no /data/misc/wifi/default_ap.check. Start copy default ap
I/wpa_supplicant( 5756): rfkill: Cannot open RFKILL control device,
D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
,D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false,
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/bt_vendor( 5688): bluetooth satus is on,
D/bt_userial_mct( 5688): userial_open(port:0)
I/bt_vendor( 5688): bt-vendor : BT_VND_OP_USERIAL_OPEN
,I/wpa_supplicant( 5756): p2p0: State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/bt_vendor( 5688): Done intiailizing UART
,I/bt_vendor( 5688): Done intiailizing UART
I/bt_userial_mct( 5688): CMD=65, EVT=65, ACL_Out=66, ACL_In=66
I/bt_vendor( 5688): Bluetooth Firmware and transport layer are initialized
,D/bt_userial_mct( 5688): Entering userial_read_thread()
,I/        ( 5688): BTE_InitTraceLevels -- TRC_HCI
,I/        ( 5688): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 5688): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 5688): BTE_InitTraceLevels -- TRC_AVDT
,I/        ( 5688): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 5688): BTE_InitTraceLevels -- TRC_A2D
I/        ( 5688): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 5688): BTE_InitTraceLevels -- TRC_BTM
I/        ( 5688): BTE_InitTraceLevels -- TRC_GAP
I/        ( 5688): BTE_InitTraceLevels -- TRC_PAN
I/        ( 5688): BTE_InitTraceLevels -- TRC_SAP
I/        ( 5688): BTE_InitTraceLevels -- TRC_SDP
I/        ( 5688): BTE_InitTraceLevels -- TRC_GATT
I/        ( 5688): BTE_InitTraceLevels -- TRC_SMP
I/        ( 5688): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 5688): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 5688): BTE_InitTraceLevels -- TRC_PROTOCOL
,W/bt-l2cap( 5688): l2c_link_processs_ble_num_bufs 16
,E/bt-btm  ( 5688): BTM_SecRegister:p_cb_info->p_le_callback == 0xa4584ead 
E/bt-btm  ( 5688): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4584ead 
,D/BluetoothAdapterProperties( 5688): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,E/bt-btif ( 5688): Calling BTA_HhEnable
,E/bt-btif ( 5688): btif_storage_get_adapter_property service_mask:0x2120048,
D/BluetoothAdapterProperties( 5688): Address is:08:EC:A9:50:75:41
E/BluetoothServiceJni( 5688): populateRssiValuesNative
I/bluedroid( 5688): getModelRssiValues,
,E/BluetoothServiceJni( 5688): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 5688): modelRssiValuesCallback, low, mid, high = -70,-60,127
D/BluetoothAdapterProperties( 5688): Name is: A3-1
,D/SettingsProvider( 1018): name = bluetooth_name
,D/BluetoothAdapterProperties( 5688): Scan Mode:20
,D/BluetoothAdapterProperties( 5688): Discoverable Timeout:120
,D/BluetoothAdapterProperties( 5688): LE Address is:C8:D9:53:A0:EA:82
,E/bt-btif ( 5688): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 5688): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,E/bt-btif ( 5688): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 5688): btif_sock_init: !vhci_init
,D/IOP_DB_BT( 5688): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5688): db_open: db_open : handle 2963906576l, read 13894 bytes onto local cache
,E/bt_mct  ( 5688): hci lib postload completed
,D/IOP_DB_BT( 5688): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,D/IOP_DB_BT( 5688): db_query: result 1
I/        ( 5688): iop_db_open: iop_db_open status 0
,D/bte_conf( 5688): Device ID record 1 : primary
,D/bte_conf( 5688):   vendorId            = 0075
D/bte_conf( 5688):   vendorIdSource      = 0001
D/bte_conf( 5688):   product             = 0100
D/bte_conf( 5688):   version             = 0200
D/bte_conf( 5688):   clientExecutableURL = 
D/bte_conf( 5688):   serviceDescription  = 
D/bte_conf( 5688):   documentationURL    = 
D/bte_conf( 5688): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 5688): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,I/wpa_supplicant( 5756): p2p0: State: INACTIVE -> DISCONNECTED
,I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5756): Skip scan - bUseNetwork false
D/BluetoothAdapterState( 5688): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5688): ScanMode =  20
D/BluetoothAdapterProperties( 5688): State =  11
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 5688): Setting state to 12
I/BluetoothAdapterState( 5688): Bluetooth adapter state changed: 11-> 12
,D/SettingsProvider( 1018): name = bluetooth_a2dp_sink_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 1002
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/BluetoothAdapterProperties( 5688): Scan Mode:21
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterProperties( 5688): Discoverable Timeout:120
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/BluetoothAdapterService( 5688): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5688): updateAdapterState state is 12
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,I/wpa_supplicant( 5756): HOTSPOT20_ENABLE called
,I/wpa_supplicant( 5756): [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
E/wpa_supplicant( 5756): getIMSI cannot open /data/misc/radio/kmem: No such file or directory
E/wpa_supplicant( 5756): SIM READ ERROR,
I/wpa_supplicant( 5756): Blacklist: Clear (all) ,
I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/BluetoothAdapterService( 5688): Autoconnection is available 
,D/BluetoothAdapterService( 5688): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapter( 1439): onBluetoothStateChange: up=true
D/BluetoothAdapterService( 5688): starting service from this receiver
D/BluetoothAdapter( 1439): onBluetoothStateChange: Bluetooth is on
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapter( 1635): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1635): onBluetoothStateChange: Bluetooth is on
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
,D/Tethering( 1018): interfaceStatusChanged p2p0, false
,I/BluetoothAdapterState( 5688): Entering On State from state = 11
,D/BluetoothAdapter( 5632): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 5632): onBluetoothStateChange: Bluetooth is on
,D/BluetoothA2dp( 5688): onBluetoothStateChange: up=true
,I/wpa_supplicant( 5756): wlan0: Setting scan request: 0 sec 0 usec
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1018): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1181): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1181): onBluetoothStateChange: Bluetooth is on
I/BluetoothPbapService( 5688): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,D/BluetoothAdapter( 1432): onBluetoothStateChange: up=true
,D/BluetoothAdapter( 1432): onBluetoothStateChange: Bluetooth is on
D/BluetoothAdapter( 5688): onBluetoothStateChange: up=true
D/BluetoothAdapter( 5688): onBluetoothStateChange: Bluetooth is on
,D/BluetoothAdapter( 1451): onBluetoothStateChange: up=true
D/BluetoothAdapter( 1451): onBluetoothStateChange: Bluetooth is on
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =12
I/InputMethodManagerService( 1018): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/wpa_supplicant( 5756): Skip scan - bUseNetwork false
,D/BluetoothTile( 1181):  onBluetoothStateChange:
,D/BluetoothHeadset( 1432): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19792005, true
,D/BluetoothHeadset( 1432): registerMessageListener
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,I/SamsungIME( 1770): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothTile( 1181):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1181): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,D/BluetoothTile( 1181):  getBluetoothState : 12
,D/HeadsetService( 5688): registerMessageListener
,D/HeadsetService( 5688): registerMessageListener
D/HeadsetStateMachine( 5688): Disconnected process message: 70
,D/HeadsetStateMachine( 5688): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@234398b2
,I/Telecom ( 1432): BluetoothPhoneService: handleMessage(7) / param null
I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,I/Telecom ( 1432): BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,I/Telecom ( 1432): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/WifiConfigStore( 1018): Loading config and enabling all networks 
,D/BluetoothTile( 1181):  handleUpdatestate:false name:null
,I/BluetoothPbapService( 5688): Handler(): got msg=1
,D/HeadsetStateMachine( 5688): Disconnected process message: 9
,D/HeadsetStateMachine( 5688): mNumActive: 0 mNumHeld: 0 mCallState: 6
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=true
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/STATUSBAR-WifiQuickSettingButton( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/HotspotTile( 1181): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1181): Wifi onReceive(3)
D/STATUSBAR-QSTileView( 1181): onStateChanged: Wi-Fi
,D/HotspotTile( 1181): onReceive : 3, 0
D/PhoneStatusBar( 1181): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/audio_hw_primary(  285): adev_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  285): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  285): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  285): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  285): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  285): adev_set_parameters: exit
E/HeadsetStateMachine( 5688): terminateScoUsingVirtualVoiceCall:No present call to terminate
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,D/WifiCredService( 1294): Action received :android.net.wifi.WIFI_STATE_CHANGED
,V/BluetoothPbapService( 5688): PBAP Service initSocket try: 0
,D/BluetoothMapMasInstance( 5688): set MAP SDP message type : 1,
E/WifiConfigStore( 1018): Not a HS20
,W/BluetoothAdapter( 5688): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,D/BluetoothSocket( 5688): bindListen(), new LocalSocket 
D/BluetoothSocket( 5688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8dbd5b9
D/BluetoothSocket( 5688): channel: 5
,W/BluetoothAdapter( 5688): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 5688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,D/BluetoothSocket( 5688): bindListen(), new LocalSocket 
D/BluetoothSocket( 5688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6ce8dfe
D/BluetoothSocket( 5688): channel: 19
D/BluetoothPbapService( 5688): PBAP Socket is BluetoothServerSocket
,E/WifiConfigStore( 1018): Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory),
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [65]
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 5756): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 5756): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5756): reset timer : RESET_TIMER 0
I/wpa_supplicant( 5756): P2P: Current p2p state = IDLE
I/wpa_supplicant( 5756): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 5756): First Scan Start
,I/wpa_supplicant( 5756): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiNative-wlan0( 1018): Setting external_sim to 1
,W/Settings( 5521): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine( 1018): Setting OUI to DA-A1-19
I/WifiNative-HAL( 1018): startHal
E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9f0a388c
I/WifiNative-HAL( 1018): Could not start hal
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): P2pDisabledState{ what=131203 }
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 3
D/CommandListener(  280): Setting iface cfg
,D/CommandListener(  280): Trying to bring up p2p0
D/WifiScanningService( 1018): DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiNative-HAL( 1018): startHal
,E/wifi    ( 1018): getStaticLongField sWifiHalHandle 0x9dc589bc
I/WifiNative-HAL( 1018): Could not start hal
E/WifiScanningService( 1018): could not start HAL
D/RttService( 1018): SCAN_AVAILABLE : 3,
D/RttService( 1018): DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1018): startMonitoring(p2p0) with mConnected = true
E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
D/WifiP2pService( 1018): P2pEnablingState
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,D/WifiP2pService( 1018): P2pEnablingState{ what=147457 }
,D/WifiP2pService( 1018): P2p socket connection successful
,D/WifiP2pService( 1018): P2pEnabledState
,I/wpa_supplicant( 5756): wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
D/WifiP2pService( 1018): sending p2p connection changed broadcast: IDLE
,I/wpa_supplicant( 5756): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,E/wpa_supplicant( 5756): wpa_driver_nl80211_driver_cmd: failed to issue private commands
E/WifiStateMachine( 1018): Failed to set frequency band 0
E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiP2pService( 1018): create mNetworkAgent
,D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayController( 1018): disconnect
,D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/AllShareCastTile( 1181): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/SecContentProvider2( 1018): mCursor = null
,D/AllShareCastTile( 1181): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/LocalBluetoothProfileManager( 1294): Adding local A2DP profile
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/LocalBluetoothProfileManager( 1294): Adding local HEADSET profile
,E/BluetoothHeadset( 1294): BTStateChangeCB is registed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/BluetoothHeadset( 1294): BluetoothHeadset service is binded
,D/BluetoothMap( 1294): Create BluetoothMap proxy object
D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/WifiNative-p2p0( 1018): p2pGetDeviceAddress
,D/WifiNative-p2p0( 1018): p2pGetDeviceAddress returning 0a:ec:a9:50:75:42
,D/WifiP2pService( 1018): DeviceAddress: 0a:75:42
,D/WifiDisplayController( 1018): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A3-1
D/WifiDisplayController( 1018):  deviceAddress: 0a:ec:a9:50:75:42
D/WifiDisplayController( 1018):  primary type: 10-0050F204-5
D/WifiDisplayController( 1018):  secondary type: null
D/WifiDisplayController( 1018):  wps: 0
D/WifiDisplayController( 1018):  grpcapab: 0
D/WifiDisplayController( 1018):  devcapab: 0
D/WifiDisplayController( 1018):  status: 3
D/WifiDisplayController( 1018):  wfdInfo: null
D/WifiDisplayController( 1018):  groupownerAddress: null
D/WifiDisplayController( 1018):  GOdeviceName: null
D/WifiDisplayController( 1018):  interfaceAddress: 
D/WifiDisplayController( 1018):  SConnectInfo : null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,W/ContextImpl( 1294): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/Bluetoothsap( 1294): bindService called to Bluetooth SAP Service
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/WifiP2pService( 1018): sending p2p persistent groups changed broadcast
,D/WifiP2pService( 1018): InactiveState
,D/WifiP2pService( 1018): InactiveState{ what=143376 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,I/wpa_supplicant( 5756): p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,D/WifiP2pService( 1018): InactiveState{ what=143376 }
E/ConnectivityService( 1018): updateNetworkInfo()
D/WifiP2pService( 1018): P2pEnabledState{ what=143376 }
,D/LocalBluetoothProfileManager( 1294): PANU : true
W/LocalBluetoothProfileManager( 1294): Warning: SAP profile was previously added.
D/LocalBluetoothProfileManager( 1294): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 1294): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 1294): onReceive
,D/BluetoothA2dp( 1294): Proxy object connected
D/A2dpProfile( 1294): Bluetooth service connected
,V/BluetoothStatusReceiver( 1181): Received android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothStatusReceiver( 1181): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,D/HeadsetProfile( 1294): Bluetooth service connected
,D/BluetoothMap( 1294): Proxy object connected
,D/MapProfile( 1294): Bluetooth service connected
D/BluetoothMap( 1294): getConnectedDevices()
,D/BluetoothAdapterService( 5688): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@10f12997
,D/BtConfig.SecureMode( 5688): isSecureModeOn:false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/AuthorizationBluetoothService( 1694): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothPbap( 1294): Proxy object connected
D/PbapServerProfile( 1294): Bluetooth service connected
,D/Bluetoothsap( 1294): BluetoothSAP Proxy object connected
D/SapProfile( 1294): Bluetooth service connected
D/Bluetoothsap( 1294): getConnectedDevices()
,D/BluetoothInputDevice( 1294): Proxy object connected
,D/HidProfile( 1294): Bluetooth service connected
,D/BluetoothPan( 1294): BluetoothPAN Proxy object connected
D/PanProfile( 1294): Bluetooth service connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3342): Starting #3
,I/Hs20UtilService( 3342): Message received 5011
,E/WifiStateMachine( 1018): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-wlan0( 1018): callSECStringApiVoid - ID [215]
E/WifiNative-wlan0( 1018): invaild command id : 215
,D/SecurityLogAgent( 5774): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5774): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5774): StateMachine : Current State = 1
,D/SecurityLogAgent( 5774): StateMachine : Changed Current State = 1
,D/SecContentProvider( 1018): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
,W/BluetoothAdapter( 5688): getBluetoothService() called with no BluetoothManagerCallback
,V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5843): MountEmulatedStorage(),
E/Zygote  ( 5843): v2
I/libpersona( 5843): KNOX_SDCARD checking this for 10064
I/libpersona( 5843): KNOX_SDCARD not a persona
,I/SELinux ( 5843): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5843 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5843): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5843): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BluetoothSocket( 5688): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
D/BluetoothSocket( 5688): bindListen(), new LocalSocket 
D/BluetoothSocket( 5688): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 5688): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33908a98
D/BluetoothSocket( 5688): channel: 12
I/BtOppRfcommListener( 5688): Accept thread started.
,D/TimaKeyStoreProvider( 5843): TimaSignature is unavailable
,D/ActivityThread( 5843): Added TimaKeyStore provider
,W/ResourcesManager( 5843): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/FileShare-Client( 5843): ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Client( 5843): ClientBroadcastReceiver.onReceive - disconnected
,D/FileShare-Client( 5843): Outbound.stopDelayTimer - 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5858): MountEmulatedStorage()
,E/Zygote  ( 5858): v2
I/libpersona( 5858): KNOX_SDCARD checking this for 10065
,I/libpersona( 5858): KNOX_SDCARD not a persona
,I/SELinux ( 5858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5858 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5084:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 5858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 5858): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 5858): TimaSignature is unavailable
,D/ActivityThread( 5858): Added TimaKeyStore provider
,D/FileShare-Server( 5858): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,I/ActivityManager( 1018): Killing 5148:com.sec.pcw.device/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5084/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5148/cgroup.procs: No such file or directory
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 5756): nl80211: Received scan results (20 BSSes),
I/wpa_supplicant( 5756): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 5756): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 5756): Trying to associate with  'G700'
,I/wpa_supplicant( 5756): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,E/wpa_supplicant( 5756): Cmd 35605 not handled
,I/wpa_supplicant( 5756): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
I/wpa_supplicant( 5756): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 5756): wlan0: State: ASSOCIATING -> ASSOCIATED
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 5756): Associated with F4.99.3E
I/wpa_supplicant( 5756): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
I/wpa_supplicant( 5756): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
,D/HotspotTile( 1181): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/Tethering( 1018): clearTetheredNotification()
D/HotspotTile( 1181): updateTetherState():false, false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,I/wpa_supplicant( 5756): wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,I/wpa_supplicant( 5756): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/wpa_supplicant( 5756): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,I/wpa_supplicant( 5756): wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 5756): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 5756): CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 5756): Blacklist: Clear (temp) 
I/wpa_supplicant( 5756): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,V/NetworkStats( 1018): performPollLocked() took 3ms
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1018): updateNetworkInfo()
D/NtpTrustedTime( 1018): forceRefresh() from cache miss
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NtpTrustedTime( 1018): forceRefresh Fail.
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3342): Starting #4
,I/Hs20UtilService( 3342): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  280): Setting iface cfg,
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 1,
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,E/dhcpcd  ( 5878): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 5878): version 5.5.6 starting
,E/dhcpcd  ( 5878): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 5878): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 5878): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 5878): if(wlan0) info get Success. (MAC : F4.99.3E)
I/dhcpcd  ( 5878): bssid match,
,I/dhcpcd  ( 5878): wlan0: rebinding lease of 192.168.1.106
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/dhcpcd  ( 5878): wlan0: acknowledged 192.168.1.106 from 192.168.1.1
,I/dhcpcd  ( 5878): wlan0: leased 192.168.1.106 for 172800 seconds
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1018): Adding iface wlan0 to network 502
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3342): Starting #5
,I/Hs20UtilService( 3342): Message received 5007
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1294): MountReceiver.onReceive - Keep current state
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 502,
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502
E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0,
D/ConnectivityService( 1018): Setting Dns servers for network 502 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,E/ConnectivityService( 1018): updateNetworkInfo()
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling,
E/ConnectivityService( 1018): updateNetworkInfo(),
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700",
,D/StatusBar.NetworkController( 1181): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/TelephonyNetworkFactory( 1451): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/TelephonyNetworkFactory( 1451): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3342): Starting #6
,I/System.out( 1018): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1018): (HTTPLog)-Static: isShipBuild true
I/System.out( 1018): (HTTPLog)-Thread-171-819328088: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Hs20UtilService( 3342): Message received 5007
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1294): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1294): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1294): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1294): MountReceiver.mPrefHandler - 7002
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1,
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1018): forceRefresh() from cache miss
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,V/NetworkStats( 1018): performPollLocked() took 4ms
,D/StatusBar.NetworkController( 1181): EthernetConnected: false
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1181): updateDataNetType()
,D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 3342): Starting #7
I/Hs20UtilService( 3342): Message received 5007
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1294): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1294): MountReceiver.onReceive - Keep current state
D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1018): mCursor = null
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1181): log_dcs ThreadedRenderer::initialize entered! 
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5632): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,V/io.jxcore.node.JXcoreExtension( 5632): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 5632): INFO testUtils BLE multiple advertisement supported
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): My device name is: samsung-SM-A300FU
I/jxcore-log( 5632): 
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NtpTrustedTime( 1018): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1457686727807 mCachedNtpElapsedRealtime : 225895 mCachedNtpCertainty : 25
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Mar 2016 08:58:47 GMT], X-Android-Received-Millis=[1457686724236], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1457686724143]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524290
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1181): EthernetConnected: false
,D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1181): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1181): updateDataNetType()
D/StatusBar.NetworkController( 1181): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1181): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1181): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1181): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1181): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1181): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1181): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/AlarmManagerService( 1018): Setting time of day to sec=1457686728
D/AlarmManagerService( 1018): Trying to open a file
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/AlarmManagerService( 1018): File Open Success
D/AlarmManagerService( 1018): File Close Success
I/AlarmManagerService( 1018): DRM_TIME_PATH CHMOD 666 for resetState done 
,W/AlarmManagerService( 1018): Unable to set rtc to 1457686728: Invalid argument
V/AlarmManager( 1018): waitForAlarm result :65536
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5915 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 5915): MountEmulatedStorage()
E/Zygote  ( 5915): v2
I/libpersona( 5915): KNOX_SDCARD checking this for 1000
I/libpersona( 5915): KNOX_SDCARD not a persona
I/SELinux ( 5915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/AlarmManager( 1018): No more alarm at this time.nowELAPSED=226270 batch.start=227495
,I/SELinux ( 5915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 5915): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WifiStateMachine( 1018): android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_SET
D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,I/DowntimeConditions( 1018): android.intent.action.TIME_SET ignored because schedule turned off.
,E/SMD     (  290): DCD OFF
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_SET
,W/Settings( 1018): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/DrmEventService( 1018):  no response from SecureClock 
,D/TimaKeyStoreProvider( 5915): TimaSignature is unavailable
,D/ActivityThread( 5915): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = lockscreen_zoom_panning_effect
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/KeyguardEffectViewUtil( 1181): isStrongPowerSavingMode() :false
,E/GpsLocationProvider( 1018): No APN found to select.
,D/KeyguardEffectViewController( 1181): isPreloadedWallpaper=true
,I/GeometricMosaic_Keyguard( 1181): update
,D/KeyguardEffectViewUtil( 1181): getCurrentWallpaper() mWallpaperPath :null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_LOG( 5915): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5915): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5915): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5915): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5915): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5915): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5915): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$ActiveReceiver
I/splitIntent( 1018): other index=23, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5935 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KeyguardEffectViewUtil( 1181): set current wallpaper info,
E/Zygote  ( 5935): MountEmulatedStorage()
I/libpersona( 5935): KNOX_SDCARD checking this for 10108
E/Zygote  ( 5935): v2,
I/libpersona( 5935): KNOX_SDCARD not a persona
D/SettingsProvider( 1018): name = keyguard_current_wallpaper_type
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false,
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
I/SELinux ( 5935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 5935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5935): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/Zygote  ( 5942): MountEmulatedStorage(),
E/Zygote  ( 5942): v2
I/libpersona( 5942): KNOX_SDCARD checking this for 10071
,I/libpersona( 5942): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=5942 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 5942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 5942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 5942): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 5935): TimaSignature is unavailable
D/ActivityThread( 5935): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 1694): Using platform SSLCertificateSocketFactory
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,D/SettingsProvider( 1018): name = keyguard_current_wallpaper_file_path
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 5942): TimaSignature is unavailable
D/ActivityThread( 5942): Added TimaKeyStore provider
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1018): name = keyguard_current_wallpaper_res_id
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10049
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10049
,I/ConfigFetchService( 1938): onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigService( 1694): onCreate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ConfigFetchService( 1938): running network task: configservice_periodic
,E/WakeLock( 1938): callingPackage is not supposed to be empty for wakelock Config Service fetch!
,I/ConfigFetchService( 1938): launchTask
,D/TEST    ( 1181): run!!!
,I/GeometricMosaic_Renderer( 1181): setBackgroundBitmap
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/KeyguardEffectViewController( 1181): isPreloadedWallpaper=true
,I/MusicStore( 5935): Database version: 120
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 5688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5688): Disconnected process message: 10
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,W/ResourcesManager( 5935): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5935): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,V/JNIHelp ( 5935): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/DriveInitializer( 1938): Background init thread started
,I/ConfigFetchService( 1938): service connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1694): Tagging socket 49 with tag 120300000000{4611,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/DriveInitializer( 1938): Awaiting to be initialized
,W/ActivityThread( 5935): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5935): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b56e00e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5935): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5935): GMSCore installation verified
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 1938): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 24787(1456KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 1.483ms total 110.095ms,
D/ConfigFetchService( 1938): ConfigApi connection successful.
,I/ConfigStore( 5935): Config Database version: 1
,I/qtaguid ( 1694): Tagging socket 59 with tag 120300000000{4611,0} for uid -1, pid: 1694, getuid(): 10011
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/GAV2    ( 5942): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 5942): Created application version: 3.6.9 (30609)
,E/Auth.Api.Credentials( 1938): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 63955(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 6.309ms total 196.797ms
,I/BooksSync( 5942): Starting books sync for 61035162, extras: ade
,W/DriveInitializer( 1938): Background init thread ended,
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1018): waitForAlarm result :8
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MediaRouter( 5935): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/MusicLeanback( 5935): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 5935): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.106/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1181): CM callback handler got msg 524295
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 5935): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6016): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6016 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6016): v2
I/libpersona( 6016): KNOX_SDCARD checking this for 10001
I/libpersona( 6016): KNOX_SDCARD not a persona
,I/SELinux ( 6016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/SELinux ( 6016): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5935): Using our fixed implementation of GMSCore's GoogleHttpClient
,E/SQLiteLog( 5942): (284) automatic index on view_volumes(volume_id)
,D/TimaKeyStoreProvider( 6016): TimaSignature is unavailable
,D/ActivityThread( 6016): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 5935): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/PhenotypeFlagCommitter( 1694): Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 5179:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/BooksConfig( 5942): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6038): MountEmulatedStorage()
,I/libpersona( 6038): KNOX_SDCARD checking this for 10161
E/Zygote  ( 6038): v2
I/libpersona( 6038): KNOX_SDCARD not a persona
,I/SELinux ( 6038): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6038): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6038 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6038): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5179/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6038): TimaSignature is unavailable
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 6038): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6055): MountEmulatedStorage()
,I/libpersona( 6055): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6055): v2
I/libpersona( 6055): KNOX_SDCARD not a persona
I/SELinux ( 6055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6055 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/ActivityManager( 1018): Killing 4712:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/SELinux ( 6055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
E/SELinux ( 6055): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6055): TimaSignature is unavailable
D/ActivityThread( 6055): Added TimaKeyStore provider
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Watchdog( 1018): !@Sync 7
,I/DIAGMON_AGENT( 6055): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,E/BooksAccountManager( 5942): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5942): Soft error
E/BooksSync( 5942): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5942): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5942): Sync error
E/BooksSync( 5942): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5942): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 5942): Finished books sync
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/ResourcesManager( 6038): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6038): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 5200:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22335, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/DIAGMON_AGENT( 6055): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,V/JNIHelp ( 6038): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/DIAGMON_AGENT( 6055): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_4712/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5200/cgroup.procs: No such file or directory
,W/ActivityThread( 6038): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6038): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b6f9262: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6038): Installed default security provider GmsCore_OpenSSL
,D/btif_config_util( 5688): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/DIAGMON_AGENT( 6055): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,E/Auth.Api.Credentials( 1938): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1938): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/DIAGMON_AGENT( 6055): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6055): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6055): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/dhcpcd  ( 5878): wlan0: sending IPv6 Router Solicitation
,D/PicasaService( 4451): start picasa sync
,D/PicasaService( 4451): end picasa sync
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6082): MountEmulatedStorage(),
,E/Zygote  ( 6082): v2
,I/libpersona( 6082): KNOX_SDCARD checking this for 10008
I/libpersona( 6082): KNOX_SDCARD not a persona
,I/SELinux ( 6082): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6082): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6082): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=6082 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6082): TimaSignature is unavailable
,D/ActivityThread( 6082): Added TimaKeyStore provider
,W/ResourcesManager( 6038): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6038): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.,
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,E/SQLiteLog( 1694): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 6038): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/ActivityManager( 1018): Killing 3295:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,I/FOTA_Client( 6082): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/dex2oat ( 6101): ----------------------------------------------------
I/dex2oat ( 6101): <SS>: S T A R T I N G . . .
I/dex2oat ( 6101): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6101): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1872686932.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads1872686932.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/FOTA_Client( 6082): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,I/ActivityManager( 1018): Killing 5264:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 09:58:50 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onCreate()
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/KLMS-2.5.123: ( 3408): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3408): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6117): MountEmulatedStorage()
E/Zygote  ( 6117): v2
I/libpersona( 6117): KNOX_SDCARD checking this for 10031
I/libpersona( 6117): KNOX_SDCARD not a persona
,I/SELinux ( 6117): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6117 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6117): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6117): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3408): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/art     (  312): Explicit concurrent mark sweep GC freed 8717(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 25.183ms
,I/KLMS-2.5.123: ( 3408): StateImplV2(): networkChangeListener().START
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.196ms
,D/TimaKeyStoreProvider( 6117): TimaSignature is unavailable
,D/ActivityThread( 6117): Added TimaKeyStore provider
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 796us total 16.877ms
,I/KLMS-2.5.123: ( 3408): NetworkChangeOperations(): uploadRequestLog().START 
,E/Zygote  ( 6145): MountEmulatedStorage(),
E/Zygote  ( 6145): v2
,I/libpersona( 6145): KNOX_SDCARD checking this for 10099
I/libpersona( 6145): KNOX_SDCARD not a persona
,I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/KLMS-2.5.123: ( 3408): NetworkChangeOperations(): uploadRequestLog().END 
,I/ActivityManager( 1018): Start proc com.google.android.gm for service com.google.android.gm/.provider.MailSyncAdapterService: pid=6145 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3408): StateImplV2(): networkChangeListener().END
,W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_3295/cgroup.procs: No such file or directory
,I/dex2oat ( 6101): dex2oat took 170.347ms (threads: 4)
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5264/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
,D/ActivityThread( 6145): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 11461(952KB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 10MB/18MB, paused 1.395ms total 99.110ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1938): [GCoreUtils] Current gmscore version, 7899434 is smaller than the required version 8400000
,I/Kids    ( 1938): [KidsDataSyncAdapter] Skipping
,E/SMD     (  290): DCD OFF
,I/DBG_POLICYDM( 5216): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  259): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 229306
D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3487)
,I/DBG_POLICYDM( 5216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,E/DBG_POLICYDM( 5216): [com.policydm.XDMBroadcastReceiver(240/xdmNotInitSetResume)] DM Not Init
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(246/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,I/SA      ( 5244): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/DBG_POLICYDM( 5216): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/DBG_POLICYDM( 5216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5244): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5244): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5244): [SLFUCHKMGR] constructor called
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,W/InstanceID/Rpc( 6038): Found 10011
,I/DBG_POLICYDM( 5216): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,I/SA      ( 5244): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5244): [OR] == isSIMCardReady false ==
,I/SA      ( 5244): [SCU] == networkStateCheck == true
,I/SA      ( 5244): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5244): isChinaCountryCode : false
I/SA      ( 5244): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 5244): [OR] == networkStateCheck true ==
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,I/SA      ( 5244): [OR] GetMyCountryZoneTask
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6038): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/SA      ( 5244): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5277:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 5216): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,D/accuweather( 1548): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5244): [SRS] prepareGetMyCountryZone
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/DBG_POLICYDM( 5216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 13
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 5216): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 5216): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 5216): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 5216): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 5216): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,D/accuweather( 1548): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1548): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1548): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1548): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/06/12:34:38
,I/DBG_POLICYDM( 5216): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/accuweather( 1548): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/11/09:58:51
,D/accuweather( 1548): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(324/xpollingDefaultPollingTime)] 
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/SA      ( 5244): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6199 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 6199): MountEmulatedStorage()
E/Zygote  ( 6199): v2
I/libpersona( 6199): KNOX_SDCARD checking this for 10121
I/libpersona( 6199): KNOX_SDCARD not a persona
,I/SELinux ( 6199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SA      ( 5244): [SSP] query invoked,
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/TimaKeyStoreProvider( 6199): TimaSignature is unavailable
,D/ActivityThread( 6199): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6215): MountEmulatedStorage()
E/Zygote  ( 6215): v2
I/libpersona( 6215): KNOX_SDCARD checking this for 10110
I/libpersona( 6215): KNOX_SDCARD not a persona
,I/SELinux ( 6215): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6215): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 41775(1860KB) AllocSpace objects, 6(100KB) LOS objects, 33% free, 23MB/35MB, paused 3.155ms total 190.952ms
,E/SELinux ( 6215): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for service com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.service.SyncAdapterService: pid=6215 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 27874(1366KB) AllocSpace objects, 7(243KB) LOS objects, 39% free, 8MB/13MB, paused 1.527ms total 78.265ms
,D/TimaKeyStoreProvider( 6215): TimaSignature is unavailable
,D/ActivityThread( 6215): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5277/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/SA      ( 5244): [TPMU] GetMccFromDB : null
,I/SA      ( 5244): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5244): [TPM] isNoProxy(default) : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(348/xpollingDefaultPollingTime)] Next Polling Time:2016/03/12/16:16:38
,E/File    ( 5244): fail readDirectory() errno=2
,I/Gmail   ( 6145): getAccountsCursor
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(922/xspdHandler)] XEVENT_RC_GET_VERSION
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,I/System.out( 6038): Thread-1023(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/ResourcesManager( 6199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6199): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/GAV2    ( 6145): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/System.out( 6038): Thread-1021(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6038): Thread-1021(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1021(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1021(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6038): Thread-1020(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1020(ApacheHTTPLog):isShipBuild true
,I/System.out( 6038): Thread-1020(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1020(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6038): Thread-1023(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1023(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6038): Thread-1022(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1022(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1022(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1022(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,W/Gmail   ( 6145): Sync started for account: account:61035162
,D/AndroidHttpClient( 6038): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 6038): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/System.out( 6038): Thread-1038(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1038(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1038(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1038(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,I/qtaguid ( 6038): Tagging socket 54 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Tagging socket 53 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Tagging socket 31 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Tagging socket 52 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/Gmail   ( 6145): getAccountsCursor
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6215): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Gmail   ( 6145): Error finding the version of the Email provider.....
E/Gmail   ( 6145): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6145): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 6145): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6145): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6145): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6145): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6145): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6145): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6145): We do not support migrating this version of the Email provider.
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6215): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(186/callRestClientThread)] szReqURL = http://svc-cf.spd.samsungdm.com/SM-A300FU/XEO/version.xml
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,E/SQLiteLog( 6145): (283) recovered 108 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,I/DBG_POLICYDM( 5216): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/GAv4    ( 6215): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6215):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6215):   adb logcat -s GAv4
,D/QuickConnect( 6199): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6199): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,W/art     ( 6038): Suspending all threads took: 33.257ms
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBSpdAdp(159/xdbSetSpdState)] nRestClientMode = 6
,E/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(213/RestClientProcess)] SPD SERVICE Start!!
,W/ContextImpl( 5216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.policydm.restclient.XRCProcess.RestClientProcess:214 com.policydm.restclient.XRCProcess.access$100:78 com.policydm.restclient.XRCProcess$RestClientThread.run:135 
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/QuickConnect( 6199): PeriphStartReceiver.onReceive - no need to start
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/DBG_POLICYDM( 5216): [com.policydm.XDMService(61/onCreate)] 
I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(623/execute)] 
,I/DBG_POLICYDM( 5216): [com.policydm.XDMService(83/onStartCommand)] 
,W/GAv4    ( 6215): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(1099/getPacket)] 
I/DBG_POLICYDM( 5216): -----------Device RestClient request-----------
I/DBG_POLICYDM( 5216): GET http://svc-cf.spd.samsungdm.com/SM-A300FU/XEO/version.xml HTTP/1.1
I/DBG_POLICYDM( 5216): User-Agent: samsung SM-A300FU SyncML_DM Client
I/DBG_POLICYDM( 5216): Connection: Keep-Alive
I/DBG_POLICYDM( 5216): Content-Type: application/xml
I/DBG_POLICYDM( 5216): Accept: application/xml
I/DBG_POLICYDM( 5216): ---------------- End ----------------
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6215): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/ActivityThread( 5216): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/Gmail   ( 6145): Observing account changes for notifications
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/GAv4    ( 6215): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ContextImpl( 6215): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/System.out( 5216): Thread-864(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5216): Thread-864(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5216): Thread-864(ApacheHTTPLog):isShipBuild true
I/System.out( 5216): Thread-864(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5216): Thread-864(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 1000
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/GAv4    ( 6215): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,D/SecurityLogAgent( 5774): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5774): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5774): StateMachine : Current State = 1
,D/SecurityLogAgent( 5774): StateMachine : Changed Current State = 1
,I/System.out( 6038): Thread-1029(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1029(ApacheHTTPLog):isShipBuild true
,I/System.out( 6038): Thread-1029(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 6038): Thread-1029(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10161
,I/qtaguid ( 6038): Tagging socket 68 with tag 0{0,0} for uid -1, pid: 6038, getuid(): 10161
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,E/File    ( 6145): fail readDirectory() errno=2
,I/Gmail   ( 6145): notifyAccountChanged
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 6145): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/CheckinService( 1938): Checking schedule, now: 1457686732709 next: 1457132671121
,I/CheckinService( 1938): active receiver: enabled
,I/iu.SyncManager( 1938): SYNC; picasa accounts
,D/NetworkLogImpl( 1938): Loaded NetworkSpeedPredictor
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(1099/getPacket)] 
I/DBG_POLICYDM( 5216): -----------Device RestClient response-----------
I/DBG_POLICYDM( 5216): Content-Type: application/xml
I/DBG_POLICYDM( 5216): Content-Length: 571
I/DBG_POLICYDM( 5216): Connection: keep-alive
I/DBG_POLICYDM( 5216): Date: Fri, 26 Feb 2016 07:35:38 GMT
I/DBG_POLICYDM( 5216): Last-Modified: Tue, 17 Nov 2015 07:32:13 GMT
I/DBG_POLICYDM( 5216): ETag: "4e5993ec21b533d31867dafe555308e7"
I/DBG_POLICYDM( 5216): Accept-Ranges: bytes
I/DBG_POLICYDM( 5216): Server: AmazonS3
I/DBG_POLICYDM( 5216): Age: 802
I/DBG_POLICYDM( 5216): X-Cache: Hit from cloudfront
I/DBG_POLICYDM( 5216): Via: 1.1 64150aec025f89247bcddad7c210f6cb.cloudfront.net (CloudFront)
I/DBG_POLICYDM( 5216): X-Amz-Cf-Id: TPlx8clrQCUupfejNeW1Wc9Wa0lc3wE3DzS9ouuWmk2Agmbm_E2GJA==
I/DBG_POLICYDM( 5216): ---------------- End ----------------
,I/System.out( 5216): Thread-864 calls detatch()
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(329/RestClientProcess)] HTTP status is 200
,I/iu.Environment( 1938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/gcm
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/gcm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XSPDAdapter(287/xspdGetLatestPolicyVersion)] systemPolicyVer = SEPF_SM-A300FU_5.0.2_0011
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XSPDAdapter(288/xspdGetLatestPolicyVersion)] spotaPolicyVer = SEPF_SM-A300FU_5.0.2_0027
,I/DBG_POLICYDM( 5216): [com.policydm.adapter.XSPDAdapter(320/xspdGetLatestPolicyVersion)] latestPolicyVer = SEPF_SM-A300FU_5.0.2_0027
,I/iu.UploadsManager( 1938): num queued entries: 0
,I/iu.UploadsManager( 1938): num updated entries: 0
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(98/getParsingVersionInfo)] androidver : 5.0.2
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(99/getParsingVersionInfo)] policyver : SEPF_SM-A300FU_5.0.2_0027
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 1938): NEXT; no task,
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(98/getParsingVersionInfo)] androidver : 5.0.2-1
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(99/getParsingVersionInfo)] policyver : SEPF_SM-A300FU_5.0.2-1_0038
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(136/getParsingVersionInfo)] periodunit day
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(137/getParsingVersionInfo)] period 7
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(138/getParsingVersionInfo)] time 9
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(139/getParsingVersionInfo)] range 9
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(140/getParsingVersionInfo)] reportperiod 14
I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(141/getParsingVersionInfo)] rReporttime 0
,I/CheckinService( 1938): Preparing to send checkin request
I/EventLogService( 1938): Accumulating logs since 1457686533422
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Gmail   ( 6145): notifyAccountChanged
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingXml(142/getParsingVersionInfo)] reportrange 9
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Kids    ( 1938): [GCoreUtils] Current gmscore version, 7899434 is smaller than the required version 8400000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/GcmGroups( 1938): Failed to subscribe to group.
I/GcmGroups( 1938): com.google.android.gms.auth.ad: BadAuthentication
I/GcmGroups( 1938): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/GcmGroups( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/GcmGroups( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:318)
I/GcmGroups( 1938): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:443)
I/GcmGroups( 1938): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:333)
I/GcmGroups( 1938): 	at com.google.android.gms.gcm.gmsproc.b.a(SourceFile:240)
I/GcmGroups( 1938): 	at com.google.android.gms.gcm.gmsproc.GcmReceiverService.onHandleIntent(SourceFile:50)
I/GcmGroups( 1938): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
I/GcmGroups( 1938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
I/GcmGroups( 1938): 	at android.os.Looper.loop(Looper.java:145)
I/GcmGroups( 1938): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(205/xpollingNextPollingTime)] Next Polling Time:2016/03/18/16:59:57
,E/Zygote  ( 6296): MountEmulatedStorage()
,E/Zygote  ( 6296): v2
I/libpersona( 6296): KNOX_SDCARD checking this for 10032
I/libpersona( 6296): KNOX_SDCARD not a persona
,I/SELinux ( 6296): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6296 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6296): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/DBG_POLICYDM( 5216): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
E/SELinux ( 6296): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Gmail   ( 6145): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/GcmGroups( 1938): Groups upload failed, retrying in 24000:00:00
,I/DBG_POLICYDM( 5216): [com.policydm.polling.XPollingAgent(166/xpollingSaveXMLData)] Next StatusReport Time:2016/03/12/19:29:37
,D/TimaKeyStoreProvider( 6296): TimaSignature is unavailable
,D/ActivityThread( 6296): Added TimaKeyStore provider
,E/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(389/RestClientProcess)] bPolicyUpdate is false
,I/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(949/callRestClientFinish)] 
,E/DBG_POLICYDM( 5216): [com.policydm.XDMBroadcastReceiver(540/xdmSetCheckedIntent)] b_AlreadyReceivedIntent : false
,I/System.out( 5521): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5521): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5521): (HTTPLog)-Static: isShipBuild true
I/System.out( 5521): (HTTPLog)-Thread-932-591632562: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5521): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10102
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBSpdAdp(159/xdbSetSpdState)] nRestClientMode = 0
,I/DBG_POLICYDM( 5216): [com.policydm.ui.XUIAdapter(32/xuiAdpGetUiMode)] nDmUiMode : 0
,E/DBG_POLICYDM( 5216): [com.policydm.restclient.XRCProcess(984/callRestClientFinish)] SPD SERVICE Stop!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ContextImpl( 5216): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.policydm.restclient.XRCProcess.callRestClientFinish:985 com.policydm.restclient.XRCProcess.RestClientProcess:505 com.policydm.restclient.XRCProcess.access$100:78 
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/art     ( 6038): Suspending all threads took: 10.836ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.policydm, destAppInfo.processName = com.policydm
,I/DBG_POLICYDM( 5216): [com.policydm.XDMService(44/onDestroy)] 
,I/System.out( 5521): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,I/Gmail   ( 6145): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/WebViewFactory( 6215): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/Gmail   ( 6145): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/LibraryLoader( 6215): Time to load native libraries: 1 ms (timestamps 1153-1154)
I/LibraryLoader( 6215): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6215): Binding Chromium to main looper Looper (main, tid 1) {2fae5d2d}
,I/LibraryLoader( 6215): Expected native library version number "",actual native library version number ""
,I/chromium( 6215): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/CheckinRequestBuilder( 1938): Checkin reason type: 12 attempt count: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/BrowserStartupController( 6215): Initializing chromium process, singleProcess=true
,W/art     ( 6215): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6215): ApplicationContext is null in ApplicationStatus
,I/System.out( 6038): Thread-1038 calls detatch()
,W/chromium( 6215): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
I/qtaguid ( 6038): Untagging socket 52
I/System.out( 6038): Thread-1023 calls detatch(),
I/System.out( 6038): Thread-1023(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6038): Thread-1023(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SMARTBONDING_ENABLED is false,
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 6038): Tagging socket 52 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings,
I/qtaguid ( 6038): Tagging socket 55 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
E/libEGL  ( 6215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6215): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6215): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6215): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6215): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6215): Local Branch: 
I/Adreno-EGL( 6215): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6215): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6215):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Babel   ( 5521): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 6296): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6296): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 6296): PushLog.txt file is not deleted.
,D/SPPClientService( 6296): PushLog.txt file is not deleted.
,D/SPPClientService( 6296): ============PushLog. stop!
E/SPPClientService( 6296): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6296): [SystemStateMoniter] Current Time : 231267
,I/ActivityManager( 1018): Killing 5304:com.wsomacp/u0a23 (adj 15): empty #31
,D/GCM     ( 1694): Connected,
,I/qtaguid ( 6038): Untagging socket 52
,I/System.out( 6038): Thread-1023 calls detatch()
,I/System.out( 6038): Thread-1023(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6038): Thread-1023(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1023(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/qtaguid ( 6038): Tagging socket 52 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,E/SPPClientService( 6296): [SystemStateMoniter] No Connect : false
,I/ActivityManager( 1018): Killing 5328:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,I/NSApplication( 6215): Starting up...
,I/qtaguid ( 6038): Untagging socket 54
,I/System.out( 6038): Thread-1022 calls detatch()
W/AudioManagerAndroid( 6215): Requires BLUETOOTH permission
,I/qtaguid ( 6038): Untagging socket 31
,I/System.out( 6038): Thread-1021 calls detatch()
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5304/cgroup.procs: No such file or directory
,D/GCM     ( 1694): Message class com.google.f.a.a.p
,I/qtaguid ( 6038): Untagging socket 53
,I/System.out( 6038): Thread-1020 calls detatch()
,I/System.out( 6038): Thread-1022(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6038): Thread-1022(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1022(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1022(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6038): Tagging socket 53 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Tagging socket 57 with tag ff44265f00000000{4282656351,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Untagging socket 68
,I/System.out( 6038): Thread-1029 calls detatch()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/qtaguid ( 6038): Untagging socket 52
I/System.out( 6038): Thread-1023 calls detatch()
,E/Zygote  ( 6338): MountEmulatedStorage()
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD checking this for 10077
I/libpersona( 6338): KNOX_SDCARD not a persona
,I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6338 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5915): mConnectivityHandler : connected
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable
,D/ActivityThread( 6338): Added TimaKeyStore provider
,I/qtaguid ( 6038): Untagging socket 53
,I/System.out( 6038): Thread-1022 calls detatch()
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5328/cgroup.procs: No such file or directory
,I/SyncAdapterService( 6215): Ignoring sync request for non-current account
,W/PCWCLIENTTRACE_AccountUtil( 5915): [hasSamungAccount] - No Samsung Account
,I/Gmail   ( 6145): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 5350, normalSync: true
,I/Gmail   ( 6145): getAccountsCursor
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5915): [GetString-S]
,I/ReactiveServiceManager( 5915): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5915): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5915): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5915): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5915): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5915): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5915): [ensureRegistration] - No Samsung account
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 1018): Killing 5350:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,I/Gmail   ( 6145): getAccountsCursor
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6145): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6145): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5350/cgroup.procs: No such file or directory
,I/GoogleURLConnFactory( 1938): Using platform SSLCertificateSocketFactory
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6145): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 19362(908KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.918ms total 204.292ms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: mail
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityThread( 6145): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6145): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e92e2e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6145): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6038): Thread-1026(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6038): Thread-1026(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1026(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1026(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6038): Tagging socket 68 with tag 0{0,0} for uid -1, pid: 6038, getuid(): 10161
,I/qtaguid ( 6038): Tagging socket 58 with tag 0{0,0} for uid -1, pid: 6038, getuid(): 10161
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/SubscribedFeeds( 1938): Hard error
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only,
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 22373, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 262942, reason: Periodic
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/qtaguid ( 6038): Untagging socket 68
,I/System.out( 6038): Thread-1026 calls detatch()
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true,
,D/WaitQueueForNetworkActivate( 5450): notifyNetworkActivated
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 5942): Thread[GAThread,5,main]: No campaign data found.
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/ActivityManager( 1018): Killing 5370:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #31
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 31523(1611KB) AllocSpace objects, 10(194KB) LOS objects, 39% free, 8MB/13MB, paused 2.211ms total 78.320ms
,W/ContextImpl( 5450): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 6038): Thread-1028(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6038): Thread-1028(ApacheHTTPLog):isShipBuild true
I/System.out( 6038): Thread-1028(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6038): Thread-1028(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6038): Tagging socket 68 with tag 0{0,0} for uid -1, pid: 6038, getuid(): 10161
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gm, service: mail
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> mail without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,I/dhcpcd  ( 5878): wlan0: sending IPv6 Router Solicitation
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6379): MountEmulatedStorage(),
I/libpersona( 6379): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6379): v2
I/libpersona( 6379): KNOX_SDCARD not a persona
,I/SELinux ( 6379): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6379): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6379): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6379 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6379): TimaSignature is unavailable
,D/ActivityThread( 6379): Added TimaKeyStore provider
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/qtaguid ( 6038): Untagging socket 68
,I/System.out( 6038): Thread-1028 calls detatch()
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5370/cgroup.procs: No such file or directory
,W/ResourcesManager( 6379): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6379): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 6145): notifyAccountChanged
,I/MultiDex( 6379): VM with version 2.1.0 has multidex support
,I/MultiDex( 6379): install
,I/MultiDex( 6379): VM has multidex support, MultiDex support library is disabled.
,I/Gmail   ( 6145): getAccountsCursor
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/JNIHelp ( 6379): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityThread( 6379): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6379): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33908a98: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6379): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Ads     ( 1938): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SA      ( 5244): [RC New] Execute method=[GET] start,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5450): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5450): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5450): exit::IDLE
D/InitializeManagerStateMachine( 5450): entry::NETWORK_CHECK
,I/splitIntent( 1018): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=12, mSplitNum[2]=17, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
I/splitIntent( 1018): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,D/InitializeManagerStateMachine( 5450): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5450): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5450): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5450): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5450): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5450): entry::SUCCESS
D/hcjo    ( 5450): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/FOTA_Client( 6082): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6399): MountEmulatedStorage(),
E/Zygote  ( 6399): v2,
,I/libpersona( 6399): KNOX_SDCARD checking this for 10058
,I/libpersona( 6399): KNOX_SDCARD not a persona
,I/SELinux ( 6399): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6399): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6399): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6399 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Volley  ( 5450): RestApi Request Add : 2307
,E/File    ( 5450): fail readDirectory() errno=2
,D/TimaKeyStoreProvider( 6399): TimaSignature is unavailable
,D/ActivityThread( 6399): Added TimaKeyStore provider
,E/Zygote  ( 6414): MountEmulatedStorage(),
I/libpersona( 6414): KNOX_SDCARD checking this for 10131
E/Zygote  ( 6414): v2
I/libpersona( 6414): KNOX_SDCARD not a persona
,I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6414 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
I/jxcore-log( 5632): 
,D/daemonapp( 1596): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1596): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
,D/ActivityThread( 6414): Added TimaKeyStore provider
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/ContactsSyncAdapter( 1694): innerSync failed
D/ContactsSyncAdapter( 1694): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1694): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 1694): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 1694): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 1694): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 1694): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 1694): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 1694): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/ContactsSyncAdapter( 1694): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 1694): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
D/ContactsSyncAdapter( 1694): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,D/WVCdm   (  285): Instantiating CDM.
I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Sep 25 2014 17:10:03
W/ResourcesManager( 6414): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
D/daemonapp( 1596): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/comsamsunglog( 1596): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1596): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1596): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1596): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1596): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
D/daemonapp( 1596): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
W/WVCdm   (  285): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
D/daemonapp( 1596): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1596): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1596): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/FOTA_Client( 6082): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 22373, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 263840, reason: Periodic
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  285): PrepareKeyRequest: nonce=483119036
,I/SA      ( 5244): [RC New] Security=[true]
,I/System.out( 5244): Thread-865(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5244): Thread-865(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5244): Thread-865(ApacheHTTPLog):isShipBuild true
,I/System.out( 5244): Thread-865(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5244): Thread-865(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10036
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Fri Mar 11 09:58:55 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/Gmail   ( 6145): notifyAccountChanged
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1596): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!,
,W/Gmail   ( 6145): Sync complete for account: account:61035162,
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3408): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3408): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/SA      ( 5244): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): TIME_CHANGED
,I/KLMS-2.5.123: ( 3408): StateImplV2(): dateTimeChanged().START : Fri Mar 11 09:58:55 GMT+01:00 2016
,I/Gmail   ( 6145): getAccountsCursor
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/KLMS-2.5.123: ( 3408): StateImplV2(): dateTimeChanged().END
,D/comdaemonstockapp( 1596): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1596): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onDestroy()
,I/ExternalOEMControlProvider( 6399): onCreate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6379): Using platform SSLCertificateSocketFactory
,D/accuweather( 1548): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1548): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6438 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6438): MountEmulatedStorage()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 10081
I/libpersona( 6438): KNOX_SDCARD not a persona,
,I/SELinux ( 6438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ Time Manager ( 6399): Time Difference not stored. TIME_DIFFERENCE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
,D/ActivityThread( 6438): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/daemonapp( 1596): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ResourcesManager( 6438): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6438): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6438): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6438): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6438): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6456): MountEmulatedStorage()
I/libpersona( 6456): KNOX_SDCARD checking this for 10037
E/Zygote  ( 6456): v2
I/libpersona( 6456): KNOX_SDCARD not a persona
I/SELinux ( 6456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6456 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6456): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/SecurityLogAgent( 5774): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 5774): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 5774): StateMachine : Current State = 1
,D/TimaKeyStoreProvider( 6456): TimaSignature is unavailable,
D/ActivityThread( 6456): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 6379): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6379): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6379): (HTTPLog)-Static: isShipBuild true
I/System.out( 6379): (HTTPLog)-Thread-1024-104898345: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6379): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,I/ActivityManager( 1018): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6473 uid=10153 gids={50153, 9997} abi=armeabi-v7a
,E/Zygote  ( 6473): MountEmulatedStorage()
I/libpersona( 6473): KNOX_SDCARD checking this for 10153
E/Zygote  ( 6473): v2
I/libpersona( 6473): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Killing 5388:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #31
,I/System.out( 6379): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6379): Tagging socket 30 with tag 180300000000{6147,0} for uid 10011, pid: 6379, getuid(): 10011
,I/art     (  312): Explicit concurrent mark sweep GC freed 8679(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 723us total 68.312ms,
,I/SELinux ( 6473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/qtaguid ( 6379): Tagging socket 34 with tag 180300000000{6147,0} for uid 10011, pid: 6379, getuid(): 10011,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.069ms total 20.872ms,
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.060ms,
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 23225(1031KB) AllocSpace objects, 5(101KB) LOS objects, 33% free, 23MB/35MB, paused 2.795ms total 213.341ms
,D/TimaKeyStoreProvider( 6473): TimaSignature is unavailable
,D/ActivityThread( 6473): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.google.android.syncadapters.calendar for service com.google.android.syncadapters.calendar/.CalendarSyncAdapterService: pid=6489 uid=10100 gids={50100, 9997, 3003} abi=armeabi-v7a,
,E/Zygote  ( 6489): MountEmulatedStorage()
E/Zygote  ( 6489): v2
I/libpersona( 6489): KNOX_SDCARD checking this for 10100
I/DBG_POLICYDM( 5216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO,
I/libpersona( 6489): KNOX_SDCARD not a persona
I/SELinux ( 6489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6489): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 5216): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts,
I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
,I/DBG_POLICYDM( 5216): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT,
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true,
,E/DBG_POLICYDM( 5216): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered,
,I/ActivityManager( 1018): Killing 5434:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #31,
,I/DBG_POLICYDM( 5216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5216): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/TimaKeyStoreProvider( 6489): TimaSignature is unavailable
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 22373, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/ActivityThread( 6489): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 264354, reason: Periodic
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6505): MountEmulatedStorage(),
E/Zygote  ( 6505): v2,
I/libpersona( 6505): KNOX_SDCARD checking this for 1000,
I/libpersona( 6505): KNOX_SDCARD not a persona,
,I/SELinux ( 6505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=6505 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5046:com.android.defcontainer/u0a3 (adj 15): empty #31
,W/ResourcesManager( 6456): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6505): TimaSignature is unavailable
,D/ActivityThread( 6505): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_5388/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_5434/cgroup.procs: No such file or directory,
W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_5046/cgroup.procs: No such file or directory
,I/qtaguid ( 6379): Untagging socket 30
,W/AbstractGoogleClient( 6489): Application name is not set. Call Builder#setApplicationName.
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
I/CalendarProvider2( 6456): CalendarProvider2.onCreate() called
,D/SecContentProvider2( 1018): mCursor = null
,D/TimeService( 6505): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457686736072
D/        ( 6505): TimeServiceNative: User Time to be set is 1457686736072
D/QC-time-services( 6505): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 6505): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 6505): Lib:time_genoff_operation: pargs->ts_val = 1457686736072
,D/QC-time-services( 6505): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  332): Daemon: Connection accepted:time_genoff
D/QC-time-services(  332): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457686736072
D/QC-time-services(  332): Daemon:genoff_opr: Base = 2, val = 1457686736072, operation = 0
D/QC-time-services(  332): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/6/70 2:43:33,
,D/QC-time-services(  332): Daemon:Value read from RTC seconds = 21437013000
D/QC-time-services(  332): Daemon:new time 1457686736072 ,
D/QC-time-services(  332): Daemon: delta 1436249723072 genoff 1436249723072 
D/QC-time-services(  332): Daemon:genoff_persistent_update: Writing genoff = 1436249723072 to memory
,D/QC-time-services(  332): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  332): Daemon:time_persistent_memory_opr:Genoff write operation ,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/QC-time-services(  332): Updating the TOD offset
D/QC-time-services(  332): Daemon:genoff_persistent_update: Writing genoff = 1436249723072 to memory
D/QC-time-services(  332): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  332): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/QC-time-services(  332): Daemon:Update to modem bit set
,D/QC-time-services(  332): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 6505): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
I/ActivityManager( 1018): Killing 5499:com.sec.android.app.camera/u0a135 (adj 15): empty #31
D/QC-time-services(  332): Daemon: Base = 2, Value being sent to MODEM = 1120284923072
,E/QC-time-services(  332): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,E/QC-time-services(  332): Daemon: Time-services: Waiting to acceptconnection
,D/SettingsProvider( 1018): name = next_alarm_formatted
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10081
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/ReminderSync( 1938): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=299:priority=5:group=main]
,I/SA      ( 5244): [RC New] [v2liruge] api execute + 1260
I/SA      ( 5244): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5244): AsyncTask #1 calls detatch()
,W/art     ( 6438): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 217.559ms
,I/SA      ( 5244): [ODM] saveOpenData( GEO_IP, PL )
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/SA      ( 5244): [OCP] update openData : PL
,E/Zygote  ( 6530): MountEmulatedStorage(),
E/Zygote  ( 6530): v2
I/libpersona( 6530): KNOX_SDCARD checking this for 10090,
I/SELinux ( 6530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6530): KNOX_SDCARD not a persona,
,I/SELinux ( 6530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6530 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 5012:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6530): TimaSignature is unavailable
,D/ActivityThread( 6530): Added TimaKeyStore provider
,I/SA      ( 5244): [TPMU] getNetworkMcc : 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5632): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
I/SA      ( 5244): [SCU] saveMccToPreferece Start
I/SA      ( 5244): [SCU] RegionMCC : 260
I/SA      ( 5244): [SSP] query invoked
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_5499/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/SA      ( 5244): [TPMU] GetMccFromDB : null
I/SA      ( 5244): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5244): [SCU] saveMccToPreferece End
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5012/cgroup.procs: No such file or directory
,I/SA      ( 5244): [RC New] executeRequest [v2liruge] end. 1964
I/SA      ( 5244): [RC New] Execute end
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5632): 
,I/SA      ( 5244): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5244): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5632): 
D/elm:15121( 6530): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15121( 6530): ELMEngine.ELMEngine( context ).
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5632): 
,D/InitializeManagerStateMachine( 5450): exit::SUCCESS
D/InitializeManagerStateMachine( 5450): entry::IDLE
,D/elm:15121( 6530): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6530): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6554): MountEmulatedStorage(),
I/libpersona( 6554): KNOX_SDCARD checking this for 10130
E/Zygote  ( 6554): v2
I/libpersona( 6554): KNOX_SDCARD not a persona
I/SELinux ( 6554): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6554): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6554): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6554 uid=10130 gids={50130, 9997} abi=armeabi-v7a
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
,D/elm:15121( 6530): ElmAgentService : onCreate()
,D/elm:15121( 6530): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:15121( 6530): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,I/System.out( 5450): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5450): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5450): (HTTPLog)-Static: isShipBuild true
I/System.out( 5450): (HTTPLog)-Thread-916-175262414: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5450): (HTTPLog)-Static: isSBSettingEnabled false
,I/jxcore-log( 5632): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
I/jxcore-log( 5632): 
,D/elm:15121( 6530): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:15121( 6530): ModuleBase.ModifySetAlarm()
I/jxcore-log( 5632): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 5632): 
D/elm:15121( 6530): MDMBridge.getInstance()
D/elm:15121( 6530): MDMBridge.getAllLicenseInfoFromSDK()
,I/io.jxcore.node.ConnectivityInfo( 5632): updateConnectivityInfo: 
I/io.jxcore.node.ConnectivityInfo( 5632):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 5632):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 5632):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 5632):     - is Bluetooth enabled: false
I/io.jxcore.node.ConnectivityInfo( 5632):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 5632):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 5632):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 5632):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 5632): notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 5632): INFO thaliMobileNativeWrapper Method networkChanged registered to native
I/jxcore-log( 5632): 
,D/TimaKeyStoreProvider( 6554): TimaSignature is unavailable
,D/ActivityThread( 6554): Added TimaKeyStore provider
I/jxcore-log( 5632): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 5632): 
,D/elm:15121( 6530): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 4229:flipboard.app/u0a96 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4784:com.android.vending/u0a26 (adj 15): empty #31
,W/ResourcesManager( 6554): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6554): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10009
,I/splitIntent( 1018): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5731:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onInitialize : 3277
D/WVMDrmPlugIn(  284): WVMDrmPlugin::onSetOnInfoListener : add 3277
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onGetSupportInfo : 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Sep 25 2014 17:10:03
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,D/GCM     ( 1694): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/System.out( 5450): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5450): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5450, getuid(): 10009
,W/WVCdm   (  285): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/GCoreUlr( 1635): Uploading GCM registration ID for account#2#
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10026/pid_4784/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_5731/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_4229/cgroup.procs: No such file or directory
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/WVCdm   (  285): PrepareKeyRequest: nonce=1602051117
,W/BaseAppContext( 1635): Using Auth Proxy for data requests.
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1635): [ChannelManager] Attempting to channel bind connection HttpClient.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 6145): Thread[GAThread,5,main]: No campaign data found.
,I/GLSUser ( 1635): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,E/SMD     (  290): DCD OFF
,I/qtaguid ( 5450): Untagging socket 26,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/CalendarSyncAdapter( 6489): Exception in onPerformLoggedSync 
E/CalendarSyncAdapter( 6489): com.google.android.apiary.AuthenticationException: Could not get an auth token
E/CalendarSyncAdapter( 6489): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:152)
E/CalendarSyncAdapter( 6489): 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:89)
E/CalendarSyncAdapter( 6489): 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:858)
E/CalendarSyncAdapter( 6489): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:410)
E/CalendarSyncAdapter( 6489): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:343)
E/CalendarSyncAdapter( 6489): 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:460)
E/CalendarSyncAdapter( 6489): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:1510)
E/CalendarSyncAdapter( 6489): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:1024)
E/CalendarSyncAdapter( 6489): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffs(CalendarSyncAdapterApiary.java:906)
E/CalendarSyncAdapter( 6489): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:430)
E/CalendarSyncAdapter( 6489): 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:335)
E/CalendarSyncAdapter( 6489): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
E/CalendarSyncAdapter( 6489): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/CalendarSyncAdapter( 6489): Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/CalendarSyncAdapter( 6489): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
E/CalendarSyncAdapter( 6489): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
E/CalendarSyncAdapter( 6489): 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:140)
E/CalendarSyncAdapter( 6489): 	... 12 more
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 22373, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
I/ActivityManager( 1018): Killing 5843:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #31
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 267827, reason: Periodic
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/hcjo    ( 5450): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 5450): SelfUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/hcjo    ( 5450): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/Volley  ( 5450): RestApi Request Add : 2346
,I/System.out( 5450): (HTTPLog)-Static: isSBSettingEnabled false
,W/libprocessgroup( 1018): failed to open /acct/uid_10064/pid_5843/cgroup.procs: No such file or directory
,I/System.out( 5450): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 5450): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5450, getuid(): 10009
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GCoreUlr( 1635): 
E/GCoreUlr( 1635): com.google.android.gms.auth.ad: BadAuthentication
E/GCoreUlr( 1635): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/GCoreUlr( 1635): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/GCoreUlr( 1635): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
E/GCoreUlr( 1635): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
E/GCoreUlr( 1635): 	at com.google.android.location.reporting.c.c.a(SourceFile:166)
E/GCoreUlr( 1635): 	at com.google.android.location.reporting.c.g.a(SourceFile:111)
E/GCoreUlr( 1635): 	at com.google.android.location.reporting.service.t.b(SourceFile:220)
E/GCoreUlr( 1635): 	at com.google.android.location.reporting.service.t.a(SourceFile:173)
E/GCoreUlr( 1635): 	at com.google.android.location.reporting.service.s.onPerformSync(SourceFile:149)
E/GCoreUlr( 1635): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 22373, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 267221, reason: Periodic
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6588): MountEmulatedStorage(),
E/Zygote  ( 6588): v2
I/libpersona( 6588): KNOX_SDCARD checking this for 10011
I/libpersona( 6588): KNOX_SDCARD not a persona
,I/SELinux ( 6588): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6588): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6588 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6588): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/MusicLeanback( 5935): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5935): Stop autocaching.
,D/TimaKeyStoreProvider( 6588): TimaSignature is unavailable
,D/ActivityThread( 6588): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6588): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6588): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1694): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 5935): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 5935): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 6456): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/GCM     ( 1694): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/MultiDex( 6588): VM with version 2.1.0 has multidex support
I/MultiDex( 6588): install
I/MultiDex( 6588): VM has multidex support, MultiDex support library is disabled.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Auth.Api.Credentials( 1938): [CredentialSyncAdapter] Unknown sync event.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6588): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1938): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/ActivityThread( 6588): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6588): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33908a98: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6588): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MusicLifecycle( 5935): Sync started
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 20975(1197KB) AllocSpace objects, 9(182KB) LOS objects, 39% free, 8MB/13MB, paused 2.125ms total 64.036ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,D/GCM     ( 1694): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1694): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6588): callingUid 10011, callindPid: 6588,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1635): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1635): [176] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1938): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6619): MountEmulatedStorage(),
E/Zygote  ( 6619): v2
I/libpersona( 6619): KNOX_SDCARD checking this for 10087
I/SELinux ( 6619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6619): KNOX_SDCARD not a persona,
,I/SELinux ( 6619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6619): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 35400(1708KB) AllocSpace objects, 5(84KB) LOS objects, 33% free, 23MB/35MB, paused 3.152ms total 227.916ms
,I/qtaguid ( 5450): Untagging socket -1
,I/qtaguid ( 5450): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5450): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5450): untagSocket(-1) failed with errno -9
,E/GmsUtils( 5935): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5935): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/TimaKeyStoreProvider( 6619): TimaSignature is unavailable
,D/ActivityThread( 6619): Added TimaKeyStore provider
,D/hcjo    ( 5450): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 5450): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 5450): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine( 5450): execute::IDLE:EXECUTE
,D/SellerAppAutoUpdateManagerStateMachine( 5450): exit::IDLE
,D/SellerAppAutoUpdateManagerStateMachine( 5450): entry::TOKENCHECK
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for service com.google.android.apps.docs/.sync.syncadapter.DocsSyncAdapterService: pid=6619 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SellerAppAutoUpdateManagerStateMachine( 5450): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 5450): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 5450): entry::FAILED
D/hcjo    ( 5450): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
,D/SellerAppAutoUpdateManagerStateMachine( 5450): exit::FAILED
D/SellerAppAutoUpdateManagerStateMachine( 5450): entry::IDLE
,I/ActivityManager( 1018): Killing 5858:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10065/pid_5858/cgroup.procs: No such file or directory
,I/dhcpcd  ( 5878): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 5878): wlan0: no IPv6 Routers available
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth,
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLifecycle( 5935): Sync ended
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/MusicSyncAdapter( 5935): Sync failed due to an authentication issue.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 22374, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 267127, reason: Periodic
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/ConfigFetchTask( 1938): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1Vgz3YsJzikxL1-XmFNOfL9qfigP0YQWjUB4DNYdMGpJIAaSTHn6Io7LJKiwMH26uUl023L4FLtpHm49QsFt3nNrz7sa89JjKOSHwtEvXdzPaVE17LXK1hMjVfwOTC0mIDSpk-kLTZ9E1sIUHiU9Q9YR0R8tL8dJoBMt8n-vA_UxENTfUZQB2ULy4AHCAMgCxcUHPoP1HwADtJZg3DOP4l2jcRrvlivaxcrSAgJj_3H9wy9mro
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/SSRM:n  ( 1018): SIOP:: AP = 360
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5915:com.sec.pcw.device/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GoogleURLConnFactory( 1938): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/MusicLeanback( 5935): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 5935): Stop autocaching.
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/System.out( 1938): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/File    ( 5935): fail readDirectory() errno=2
,D/WVMDrmPlugIn(  284): WVMDrmPlugin::onTerminate : 3277
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/System.out( 1938): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1938): Tagging socket 115 with tag 40b00000000{1035,0} for uid -1, pid: 1938, getuid(): 10011
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4270, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5915/cgroup.procs: No such file or directory
,V/HeadsetService( 5688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5688): Disconnected process message: 10
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GAv4    ( 6619): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6619):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6619):   adb logcat -s GAv4
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1181): level :100 plugged : 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/GAv4    ( 6619): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/qtaguid ( 1938): Tagging socket 118 with tag 40b00000000{1035,0} for uid -1, pid: 1938, getuid(): 10011
,W/GAv4    ( 6619): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6619): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/PeopleSync( 1938): onPerformSync() [5005f081]
,W/AnalyticsTrackerProxyImpl( 6619): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.33
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/GmsUtils( 5935): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5935): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5935): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ResourcesManager( 6619): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6619): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ContextImpl( 6619): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.docs/cache
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6619): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.android.vending
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6669): MountEmulatedStorage()
E/Zygote  ( 6669): v2
,I/libpersona( 6669): KNOX_SDCARD checking this for 10026
I/libpersona( 6669): KNOX_SDCARD not a persona
,I/SELinux ( 6669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6669 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6669): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/dex2oat ( 6667): ----------------------------------------------------
,I/dex2oat ( 6667): <SS>: S T A R T I N G . . .
I/dex2oat ( 6667): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6667): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityThread( 6619): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6619): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e92e2e6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6619): Installed default security provider GmsCore_OpenSSL
,D/TimaKeyStoreProvider( 6669): TimaSignature is unavailable
,D/ActivityThread( 6669): Added TimaKeyStore provider
,I/qtaguid ( 1938): Untagging socket 115
,I/ConfigFetchTask( 1938): updating config table for com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,I/PeopleSync( 1938): Setting subscription: result=true [5005f081]
I/PeopleSync( 1938): Starting sync, feed=null [5005f081]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1938): PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,I/dex2oat ( 6667): dex2oat took 161.630ms (threads: 4)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigFetchService( 1938): fetch service done; releasing wakelock
,I/ConfigFetchService( 1938): stopping self
,I/Adreno-EGL( 6379): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6379): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6379): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6379): Local Branch: 
I/Adreno-EGL( 6379): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6379): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6379):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6669): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 31877(1931KB) AllocSpace objects, 18(503KB) LOS objects, 39% free, 11MB/18MB, paused 1.441ms total 135.745ms
,I/Adreno-EGL( 6379): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6379): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6379): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6379): Local Branch: 
I/Adreno-EGL( 6379): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6379): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6379):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/ConfigFetchService( 1938): onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1938): GmsCore config value changed; rescheduling
,I/ConfigFetchService( 1938): self-hosted config:fetch_interval = 43200
,I/VacuumService( 1694): Vacuum at: now=1457686739602 tag=VacuumService
,I/ConfigFetchService( 1938): stopping self
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10087
I/Adreno-EGL( 6379): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6379): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6379): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6379): Local Branch: 
I/Adreno-EGL( 6379): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6379): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6379):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1694): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 6669): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1694): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Zygote  ( 6723): MountEmulatedStorage()
I/libpersona( 6723): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6723): v2
I/libpersona( 6723): KNOX_SDCARD not a persona
,I/SELinux ( 6723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6723 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,I/SELinux ( 6723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SELinux ( 6723): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,W/BaseAppContext( 1938): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 6723): TimaSignature is unavailable
,D/ActivityThread( 6723): Added TimaKeyStore provider
,W/Settings( 6669): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6669): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PeopleSync( 1938): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/PlayEventLogger( 6669): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6669): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6669): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6669): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/qtaguid ( 1694): Tagging socket 68 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ResourcesManager( 6723): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6723): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager( 1018): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1181): handleTimeUpdate
,D/SecKeyguardClockView( 1181): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1181): HomeTimezone(): 1
,I/MultiDex( 6723): VM with version 2.1.0 has multidex support
I/MultiDex( 6723): install
I/MultiDex( 6723): VM has multidex support, MultiDex support library is disabled.
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1181): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1181): *** don't update sliding image ***
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/System  ( 6669): Ignoring header User-Agent because its value was null.
,I/System.out( 6669): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6669): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6669): (HTTPLog)-Static: isShipBuild true
I/System.out( 6669): (HTTPLog)-Thread-1103-100666188: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6669): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10026
,I/System.out( 6669): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 27316(1334KB) AllocSpace objects, 8(136KB) LOS objects, 33% free, 24MB/36MB, paused 3.017ms total 160.334ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1181): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/Uploader( 1694): No account for auth token provided
,I/ActivityManager( 1018): Killing 6016:com.sec.android.cloudagent/u0a1 (adj 15): empty #31
,D/SecKeyguardStatusUtils( 1181): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/JNIHelp ( 6723): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6669): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6669): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6669): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.media.upload https://www.googleapis.com/auth/plus.pages.manage https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.profiles.read https://www.googleapis.com/auth/plus.profiles.write https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/plus.applications.manage https://www.googleapis.com/auth/plus.settings without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/Finsky  ( 6669): [1085] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,W/ActivityThread( 6723): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6723): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33908a98: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6723): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 6669): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1694): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1694): No account for auth token provided
,W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_6016/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1694): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/System.out( 1938): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1938): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1938): Tagging socket 113 with tag 40800000000{1032,0} for uid -1, pid: 1938, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 6055:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/MDM     ( 1635): [179] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6055/cgroup.procs: No such file or directory
,D/LocationInitializer( 1938): Restart initialization of location
,I/PeopleSync( 1938): Sync finished, successful=false, took 565ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1938): Tagging socket 126 with tag 40800000000{1032,0} for uid -1, pid: 1938, getuid(): 10011
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1694):  no longer exists, so no auth token.
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,D/Finsky  ( 6669): [1085] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1938): Cannot authenticate [5005f081]
I/PeopleSync( 1938): com.google.android.gms.auth.ad: BadAuthentication
I/PeopleSync( 1938): 	at com.google.android.gms.auth.p.b(SourceFile:442)
I/PeopleSync( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:365)
I/PeopleSync( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:310)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.o.b(SourceFile:30)
I/PeopleSync( 1938): 	at com.google.android.gms.people.service.g.b(SourceFile:171)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.o.b(SourceFile:370)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.o.a(SourceFile:340)
I/PeopleSync( 1938): 	at com.google.android.gms.common.server.o.a(SourceFile:319)
I/PeopleSync( 1938): 	at com.google.android.gms.plus.service.v2whitelisted.b.a(SourceFile:1184)
I/PeopleSync( 1938): 	at com.google.android.gms.people.sync.aa.g(SourceFile:1086)
I/PeopleSync( 1938): 	at com.google.android.gms.people.sync.aa.a(SourceFile:241)
I/PeopleSync( 1938): 	at com.google.android.gms.people.sync.s.a(SourceFile:283)
I/PeopleSync( 1938): 	at com.google.android.gms.people.sync.s.a(SourceFile:191)
I/PeopleSync( 1938): 	at com.google.android.gms.people.sync.s.a(SourceFile:93)
I/PeopleSync( 1938): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
I/PeopleSync( 1938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,I/CheckinTask( 1938): Sending checkin request (9809 bytes)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 42850(2MB) AllocSpace objects, 32(1715KB) LOS objects, 40% free, 8MB/13MB, paused 1.332ms total 78.369ms
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager( 1018): waitForAlarm result :4
,D/Finsky  ( 6669): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PeopleSync( 1938): ***Sync finished***, duration: 1884 [5005f081]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.docs, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.file https://www.googleapis.com/auth/drive.metadata.readonly https://www.googleapis.com/auth/drive.readonly https://www.googleapis.com/auth/activity https://docs.google.com/feeds https://docs.googleusercontent.com https://spreadsheets.google.com/feeds https://www.googleapis.com/auth/cloudprint https://www.googleapis.com/auth/discussions https://www.googleapis.com/auth/docs https://www.googleapis.com/auth/drive.apps https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/spreadsheets https://www.googleapis.com/auth/vouchers https://www.googleapis.com/auth/plus.me without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 22375, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,W/PlaySystemBroadcastReceiver( 1938): Processed handlePeopleChanged at 238967
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.people, PERIODIC, currentRunTime 271530, reason: Periodic
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
W/GLSActivity( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1694): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1694): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1694): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1694): 	at android.os.Binder.execTransact(Binder.java:461)
,E/DefaultHttpIssuer( 6619): Attempt to consume entity of HttpIssuer when no request is executing.
,E/DefaultHttpIssuer( 6619): Attempt to close HttpIssuer when no request is executing.
E/DefaultHttpIssuer( 6619): java.io.IOException
E/DefaultHttpIssuer( 6619): 	at cjw.b(PG:159)
E/DefaultHttpIssuer( 6619): 	at cju.b(PG:5072)
E/DefaultHttpIssuer( 6619): 	at dlh.b(PG:239)
E/DefaultHttpIssuer( 6619): 	at dlh.a(PG:140)
E/DefaultHttpIssuer( 6619): 	at dqo.a(PG:224)
E/DefaultHttpIssuer( 6619): 	at dlt.run(PG:9618)
E/DefaultHttpIssuer( 6619): 	at dlr.run(PG:3031)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/DataBroker( 1938): No player ID found and calling context is not the dest app
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BaseSyncManager( 6619): AuthenticatorException
E/BaseSyncManager( 6619): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BaseSyncManager( 6619): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/BaseSyncManager( 6619): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BaseSyncManager( 6619): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/BaseSyncManager( 6619): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BaseSyncManager( 6619): 	at android.os.Binder.execTransact(Binder.java:461)
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1938): Untagging socket 113
,W/Finsky  ( 6669): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/CheckinResponseProcessor( 1938): From server: 12 gservices updates and 1 deletes
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1694): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1694): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Finsky  ( 6669): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,E/SQLiteLog( 1938): (284) automatic index on invitations(external_inviter_id)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 6669): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1018): name = notification_sound_set
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1694): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1694): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
E/ReminderSync( 1938): AuthError [T SyncAdapterThread-2:id=315:priority=5:group=main]
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 27711, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/SyncManager( 1018): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 270499, reason: Periodic
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/SettingsProvider( 1018): name = ringtone_set
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = alarm_alert_set
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/SecKeyguardClockSingleView( 1181): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = lockscreen.options
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = serial_blacklist
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = facelock_liveliness_recognition_threshold
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = config_update_certificate
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = pubkey_blacklist
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SettingsProvider( 1018): name = dropbox:data_app_crash
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,I/CertBlacklister( 1018): Certificate blacklist changed, updating...
,D/SettingsProvider( 1018): name = facelock_max_center_movement
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = send_action_app_error
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = facelock_detection_threshold,
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
I/CertBlacklister( 1018): Certificate blacklist updated
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = dropbox:data_app_anr
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = web_autofill_query_url
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = ssl_session_cache
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = print_service_search_uri
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = masterLocationPackagePrefixBlacklist
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = masterLocationPackagePrefixWhitelist
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = dropbox:data_app_wtf
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = cert_pin_metadata_url
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = cert_pin_content_url
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = sms_short_codes_metadata_url
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = sms_short_codes_content_url
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/SettingsProvider( 1018): name = send_action_app_error
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10011
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/GservicesProvider( 1694): main difference update completed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.partnersetup
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6780): MountEmulatedStorage()
,I/libpersona( 6780): KNOX_SDCARD checking this for 10014
E/Zygote  ( 6780): v2
I/libpersona( 6780): KNOX_SDCARD not a persona
I/SELinux ( 6780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6780 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6780): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/CheckinRequestBuilder( 1938): Checkin reason type: 12 attempt count: 1
,E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.syncadapters.calendar, destAppInfo.processName = com.google.android.syncadapters.calendar
,D/TimaKeyStoreProvider( 6780): TimaSignature is unavailable
,D/ActivityThread( 6780): Added TimaKeyStore provider
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/splitIntent( 1018): intent=com.google.gservices.intent.action.GSERVICES_CHANGED will be not split. because same process=com.google.process.gapps is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gsf com.google.android.gsf.loginservice.ServicesWatcher
,I/splitIntent( 1018): other index=12, name=com.google.android.gms com.google.android.gms.gcm.ServiceAutoStarter
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.gservices.intent.action.GSERVICES_CHANGED !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6803): MountEmulatedStorage(),
E/Zygote  ( 6803): v2,
I/libpersona( 6803): KNOX_SDCARD checking this for 10082
I/libpersona( 6803): KNOX_SDCARD not a persona
,I/SELinux ( 6803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6803): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6803 uid=10082 gids={50082, 9997, 3003} abi=armeabi-v7a
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 37952(1802KB) AllocSpace objects, 8(140KB) LOS objects, 33% free, 24MB/36MB, paused 3.087ms total 163.914ms
,D/TimaKeyStoreProvider( 6803): TimaSignature is unavailable
,D/ActivityThread( 6803): Added TimaKeyStore provider
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1694): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1694): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,I/art     ( 1635): Explicit concurrent mark sweep GC freed 19474(1108KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 8MB/13MB, paused 1.304ms total 85.677ms
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1616e470)
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 42337(2MB) AllocSpace objects, 26(1177KB) LOS objects, 40% free, 8MB/14MB, paused 1.942ms total 111.395ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6803): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.configupdater, destAppInfo.processName = com.google.android.configupdater
,I/UpdateFetcherService( 6803): Update started
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6803): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,E/UpdateRequestReceiver( 6803): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/UpdateRequestReceiver( 6803): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,E/Uploader( 1694): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1694): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager( 1018): Killing 5942:com.google.android.apps.books/u0a71 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/DownloadManager( 1228): 1 items are running
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DownloadManager( 1228): [35] Starting com.google.android.configupdater
,I/System.out( 1228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,W/Finsky  ( 6669): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/DownloadManager( 1228): 1 items are running
,D/Finsky  ( 6669): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SystemUpdateService( 1938): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1228): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1228): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1228): (HTTPLog)-Static: isShipBuild true
I/System.out( 1228): (HTTPLog)-Thread-60-716021798: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1228): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 502 for uid 10038
,D/SystemUpdateService( 1938): onCreate
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6669): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6669): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/SystemUpdateService( 1938): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
I/ActivityManager( 1018): Killing 6117:com.sec.android.soagent/u0a31 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 4451:com.sec.android.gallery3d/u0a39 (adj 15): empty #32
,I/System.out( 1228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1228): Tagging socket 59 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,D/DeviceConnectionService( 1635): client connected with version: 7571000
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,D/SystemEventReceiver( 1938): Received GSERVICES_CHANGED broadcast
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,D/GCM     ( 1694): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only,
I/StatusBar( 1181): Icon Only
W/CheckinRequestBuilder( 1938): awaiting user notification for token
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/OcrUtils( 1938): Updating ocr activity enabled=false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1635): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SystemUpdateService( 1938): cancelUpdate (empty URL)
I/SystemUpdateService( 1938): active receiver: disabled
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SystemUpdateService( 1938): onDestroy
,I/GCoreUlr( 1635): DispatchingService.onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/libprocessgroup( 1018): failed to open /acct/uid_10071/pid_5942/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_6117/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_4451/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1228): Tagging socket 63 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,I/qtaguid ( 1228): Tagging socket 64 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,I/qtaguid ( 1228): Untagging socket 59
,I/qtaguid ( 1228): Untagging socket 63
,D/DownloadManager( 1228): [35] Finished with status SUCCESS
,I/CheckinTask( 1938): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,V/DownloadManager( 1228): 1 items are running
,V/DownloadManager( 1228): MIME Type = text/plain
,I/CheckinService( 1938): Checking schedule, now: 1457686742627 next: 1458215503592
I/CheckinService( 1938): active receiver: disabled
,I/art     ( 1938): Explicit concurrent mark sweep GC freed 38678(2MB) AllocSpace objects, 18(430KB) LOS objects, 39% free, 11MB/19MB, paused 1.638ms total 98.833ms
V/DownloadManager( 1228): 1 items are completed
,I/DownloadManager( 1228): Download 35 finished with status SUCCESS
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1635): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1694): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1694): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1694): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1694): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1694): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1694): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1181): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
D/PersonaManager( 1181): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1181): Icon Only
I/StatusBar( 1181): Icon Only
,D/PanelView( 1181): There is/are notification(s) 
D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,D/PersonaManager( 1181): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1181): Icon Only
,I/StatusBar( 1181): Icon Only
D/PanelView( 1181): There is/are notification(s) 
,D/PanelView( 1181): kidsfalse mQsExpansionEnabled:true
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 21784(1247KB) AllocSpace objects, 22(1162KB) LOS objects, 39% free, 8MB/14MB, paused 1.135ms total 51.855ms
,D/PanelView( 1181): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GCoreUlr( 1635): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 1938): Checking schedule, now: 1457686743010 next: 1458215503592
I/CheckinService( 1938): active receiver: disabled
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1694): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 19876(1042KB) AllocSpace objects, 8(145KB) LOS objects, 33% free, 24MB/36MB, paused 21.098ms total 183.825ms,
,E/Zygote  ( 6855): MountEmulatedStorage(),
E/Zygote  ( 6855): v2
I/libpersona( 6855): KNOX_SDCARD checking this for 10052
I/SELinux ( 6855): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6855): KNOX_SDCARD not a persona,
I/SELinux ( 6855): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6855): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.GservicesBroadcastReceiver: pid=6855 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a,
,W/Uploader( 1694): No account for auth token provided
,I/System.out( 1694): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1694): Tagging socket 64 with tag 120100000000{4609,0} for uid -1, pid: 1694, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  312): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 608us total 26.747ms
,E/SMD     (  290): DCD OFF
,D/TimaKeyStoreProvider( 6855): TimaSignature is unavailable
,D/ActivityThread( 6855): Added TimaKeyStore provider
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 18.949ms
,I/GCoreUlr( 1635): Unbound from all location providers
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.057ms total 21.222ms
,I/GCoreUlr( 1635): DispatchingService.onDestroy()
,I/GCoreUlr( 1635): Unbound from all location providers
,E/SQLiteLog( 1694): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     ( 1694): Explicit concurrent mark sweep GC freed 10568(481KB) AllocSpace objects, 34(2MB) LOS objects, 40% free, 8MB/13MB, paused 1.107ms total 44.921ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1694): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/login_manager
,I/GLSUser ( 1694): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/login_manager without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1694): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1694): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1694): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService( 1018): getProviders()=[passive]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/Auth.Api.Credentials( 1938): [SyncManager] Error during the sync.
E/Auth.Api.Credentials( 1938): com.google.android.gms.auth.ad: BadAuthentication
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.b(SourceFile:442)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:365)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.p.a(SourceFile:310)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.c.b(SourceFile:109)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.b(SourceFile:59)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.a(SourceFile:294)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.server.s.a(SourceFile:201)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.b.a.a(SourceFile:316)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.be.a.b.b(SourceFile:285)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.c.a(SourceFile:384)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.b.a(SourceFile:114)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:131)
E/Auth.Api.Credentials( 1938): 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
E/Auth.Api.Credentials( 1938): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Finsky  ( 6669): [1] VerifyInstalledPackagesReceiver.onReceive: Verify installed apps requested
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,D/Finsky  ( 6669): [1] VerifyInstalledPackagesTask.onPreExecute: Verifying installed apps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.configupdater, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,I/GservicesUpdateTask( 6855): Updating Gservices keys
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.process.gapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/DownloadManager( 1228): 1 items are completed
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/DownloadManager( 1228): 1 items are running
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/DownloadManager( 1228): 1 items are completed
,D/DownloadManager( 1228): [36] Starting com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
D/GCM     ( 1694): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Kids    ( 1938): [GCoreUtils] Current gmscore version, 7899434 is smaller than the required version 8400000
,I/System.out( 1228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,V/DownloadManager( 1228): 1 items are running
,I/System.out( 1228): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1228): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1228): Tagging socket 56 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,I/ActivityManager( 1018): Killing 6199:com.samsung.android.sconnect/u0a121 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10121/pid_6199/cgroup.procs: No such file or directory
,I/qtaguid ( 1228): Tagging socket 63 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,V/DownloadManager( 1228): 1 items are completed
,I/qtaguid ( 1228): Tagging socket 64 with tag ffffff0100000000{4294967041,0} for uid 10082, pid: 1228, getuid(): 10038
,I/qtaguid ( 1228): Untagging socket 56
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,V/DownloadManager( 1228): 1 items are running
,I/qtaguid ( 1228): Untagging socket 63
,D/DownloadManager( 1228): [36] Finished with status SUCCESS
,V/DownloadManager( 1228): MIME Type = text/plain
,I/DownloadManager( 1228): Download 36 finished with status SUCCESS
,V/DownloadManager( 1228): 2 items are completed
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.configupdater, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,I/UpdateFetcherService( 6803): Update downloaded, starting installation
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,I/UpdateFetcherService( 6803): doneInstall
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = com.google.android.configupdater
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.configupdater, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/ConfigUpdateInstallReceiver( 1018): Found new update, installing...
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,V/DownloadManager( 1228): 2 items are Removed
,I/ConfigUpdateInstallReceiver( 1018): Installation successful
,I/ConfigService( 1694): onDestroy
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps,
,D/PreloadUpdateManagerStateMachine( 5450): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5450): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5450): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 5450): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 5450): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5450): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5450): entry::REQ_UPDATE_CHECK
,I/Volley  ( 5450): RestApi Request Add : 2315
,I/System.out( 5450): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 5450): Tagging socket -1 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5450, getuid(): 10009
,I/qtaguid ( 5450): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9
I/qtaguid ( 5450): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
,I/NetworkManagementSocketTagger( 5450): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/qtaguid ( 5450): Tagging socket 31 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 5450, getuid(): 10009
,I/qtaguid ( 5450): Untagging socket -1
,I/qtaguid ( 5450): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5450): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 5450): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 5450): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
,D/PreloadUpdateManagerStateMachine( 5450): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 5450): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5450): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5450): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 5450): exit::FINISH
D/PreloadUpdateManagerStateMachine( 5450): entry::IDLE
,I/ActivityManager( 1018): Killing 5216:com.policydm/1000 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5216/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5758:com.android.email/u0a141 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10141/pid_5758/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): --= Surplus to requirements =--
I/jxcore-log( 5632): 
,I/jxcore-log( 5632): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5632): 
,D/AndroidRuntime( 6910): ,
D/AndroidRuntime( 6910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6910): CheckJNI is OFF
,D/AndroidRuntime( 6910): readGMSProperty: start
D/AndroidRuntime( 6910): readGMSProperty: already setted!!
D/AndroidRuntime( 6910): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6910): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6910): readGMSProperty: end
D/AndroidRuntime( 6910): addProductProperty: start
,I/ActivityManager( 1018): Killing 6338:com.android.chrome/u0a77 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_6338/cgroup.procs: No such file or directory
,E/AffinityControl( 6910): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6910): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1018): START PACKAGE DELETE: observer{91169845}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg,
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 5632:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1018): Skipping PackageSetting{a1b914e com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{10ea8bc4 u0 com.test.thalitest/.MainActivity t23}
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1018): Focus left window: 5632
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focused application released
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1770): mOCRHelper is null
,I/art     ( 3548): Explicit concurrent mark sweep GC freed 3003(180KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 861us total 42.925ms
,W/GeofencerStateMachine( 1635): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 09:59:08 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3408): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,D/elm:15121( 6530): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onCreate()
,D/elm:15121( 6530): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/KLMS-2.5.123: ( 3408): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3408): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): PACKAGE_REMOVED
,D/elm:15121( 6530): ElmAgentService : onCreate()
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/elm:15121( 6530): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6530): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6530): MDMBridge.getInstance()
D/elm:15121( 6530): MDMBridge.getAllLicenseInfoFromSDK()
I/KLMS-2.5.123: ( 3408): KLMSIntentService(): listeningToPackageRemoved().START
,D/elm:15121( 6530): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:15121( 6530): ElmAgentService : onDestroy().
,D/RegisteredServicesCache( 1439): empty dynamic service
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 28671(1867KB) AllocSpace objects, 10(151KB) LOS objects, 33% free, 24MB/36MB, paused 3.382ms total 195.565ms
,I/art     ( 1018): WaitForGcToComplete blocked for 183.849ms for cause Explicit
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3408): KLMSIntentService(): onDestroy()
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 8410(390KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.900ms total 156.682ms
,D/SSRM:n  ( 1018): SIOP:: AP = 370
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1018): result of delete: 1{91169845}
,D/AndroidRuntime( 6910): Shutting down VM
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
D/TaskPersister( 1018): removeObsoleteFile: deleting file=23_task.xml
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6926 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200,
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/Zygote  ( 6926): MountEmulatedStorage()
,I/libpersona( 6926): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6926): v2
I/libpersona( 6926): KNOX_SDCARD not a persona
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,I/SELinux ( 6926): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 6926): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6926): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,D/TimaKeyStoreProvider( 6926): TimaSignature is unavailable
D/ActivityThread( 6926): Added TimaKeyStore provider
,I/PCWCLIENTTRACE_LOG( 6926): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6926): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6926): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6926): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6926): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6926): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6926): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
,E/Zygote  ( 6941): MountEmulatedStorage(),
,E/Zygote  ( 6941): v2
I/libpersona( 6941): KNOX_SDCARD checking this for 10029
I/libpersona( 6941): KNOX_SDCARD not a persona,
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6941 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Killing 6215:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
,I/SELinux ( 6941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6941): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1181): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1181): handleBatteryUpdate
,V/EmergencyMode( 1412): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1412): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/TimaKeyStoreProvider( 6941): TimaSignature is unavailable
,D/ActivityThread( 6941): Added TimaKeyStore provider
,V/HeadsetService( 5688): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5688): Disconnected process message: 10
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/art     ( 6910): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/BroadcastQueue( 1018): Failure sending broadcast Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/BroadcastQueue( 1018): android.os.TransactionTooLargeException
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1018): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1018): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1220)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:529)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:665)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:717)
W/BroadcastQueue( 1018): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1018): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1181): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1181): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1181): level :100 plugged : 2
,W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_6215/cgroup.procs: No such file or directory
,I/FeatureConfig( 6941): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5244): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5244): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1018): Killing 5407:com.google.android.apps.plus/u0a117 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6941): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
W/ResourcesManager( 6941): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
W/ResourcesManager( 6941): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6959): MountEmulatedStorage()
E/Zygote  ( 6959): v2
I/libpersona( 6959): KNOX_SDCARD checking this for 10039
I/libpersona( 6959): KNOX_SDCARD not a persona
,I/SELinux ( 6959): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6959 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6959): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6959): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6941): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6959): TimaSignature is unavailable
,D/ActivityThread( 6959): Added TimaKeyStore provider
,W/ResourcesManager( 6941): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6959): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6959): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6959): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6941): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6941): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.

```
