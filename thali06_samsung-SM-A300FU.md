#### Test 62509094a319d1d_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  289): DCD OFF
D/AndroidRuntime( 6132): 
D/AndroidRuntime( 6132): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6132): CheckJNI is OFF
D/AndroidRuntime( 6132): readGMSProperty: start
D/AndroidRuntime( 6132): readGMSProperty: already setted!!
D/AndroidRuntime( 6132): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6132): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6132): readGMSProperty: end
D/AndroidRuntime( 6132): addProductProperty: start
E/AffinityControl( 6132): AffinityControl: registerfunction enter
D/AndroidRuntime( 6132): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6145 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PhoneWindow( 1019): *FMB* installDecor flags : -2122120936
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1480
E/Zygote  ( 6145): MountEmulatedStorage()
E/Zygote  ( 6145): v2
I/libpersona( 6145): KNOX_SDCARD checking this for 10167
I/libpersona( 6145): KNOX_SDCARD not a persona
I/SELinux ( 6145): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
I/SELinux ( 6145): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/AndroidRuntime( 6132): Shutting down VM
E/SELinux ( 6145): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6145): TimaSignature is unavailable
D/ActivityThread( 6145): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1480): updateVisibility : ActivityRecord{2c1a4637 token=android.os.BinderProxy@10ac5eee {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1480): onTrimMemory. Level: 20
I/WebViewFactory( 6145): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6145): Time to load native libraries: 2 ms (timestamps 1008-1010)
I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
W/art     ( 6132): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6145): Binding Chromium to main looper Looper (main, tid 1) {25da387b}
,I/LibraryLoader( 6145): Expected native library version number "",actual native library version number ""
,I/chromium( 6145): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6145): Initializing chromium process, singleProcess=true
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6145): ApplicationContext is null in ApplicationStatus
,W/chromium( 6145): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6145): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6145): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6145): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6145): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6145): Local Branch: 
I/Adreno-EGL( 6145): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6145): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6145):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6145): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6145): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6145): *FMB* installDecor flags : -2139027200
,D/SystemWebViewEngine( 6145): CordovaWebView is running on device made by: samsung
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6145): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{2e540e6b u0 com.test.thalitest/.MainActivity t23}
,D/OpenGLRenderer( 6145): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 6145): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6145): updateVisibility : ActivityRecord{19107e3 token=android.os.BinderProxy@317c679d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6145): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6145): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 6145,
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6145): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6145): Initialized EGL, version 1.4
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6145): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6145): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +635ms (total +1m43s500ms)
,W/ActivityManager( 1019): mDVFSHelper.release()
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{2e540e6b u0 com.test.thalitest/.MainActivity t23} time:221496
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6145): showStatusIcon on inactive InputConnection
,I/Timeline( 6145): Timeline: Activity_idle id: android.os.BinderProxy@317c679d time:221519
,I/SamsungIME( 1935): getCurrentCandidateView
,D/SamsungIME( 1935): Dismiss ExpandCandiate
,W/BindingManager( 6145): Cannot call determinedVisibility() - never saw a connection for the pid: 6145
,I/SamsungIME( 1935): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1935): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1935): KeybaordView init() : load resources
,I/SamsungIME( 1935): getCurrentKeyboard
,I/SamsungIME( 1935): getTextKeyboard
,D/SamsungIME( 1935): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6145): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6145): JniHelper::setJavaVM(0xb79e4448), pthread_self() = -1208786480
,D/JX-Cordova( 6145): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6145): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3165710 added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145): setBluetoothMacAddress: 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6145): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"},
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6145): setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Bluetooth MAC address: 08:EC:A9:50:75:41
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a71d43c added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6145): addListener: New listener added - the number of listeners is now 1
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6145): setDiscoveryMode: Discovery mode BLE is supported
,W/jxcore-log( 6145): Initializing JXcore engine
W/jxcore-log( 6145): JXcore engine is ready
,W/jxcore-log( 6145): Starting JXcore engine
,E/audit   ( 1886): type=1400 msg=audit(1457707125.720:205): avc:  denied  { ioctl } for  pid=6145 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1886):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1886): type=1300 msg=audit(1457707125.720:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bef65d58 items=0 ppid=304 ppcomm=main pid=6145 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1886): type=1320 msg=audit(1457707125.720:205): 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/jxcore-log( 6145): Platform android
W/jxcore-log( 6145): 
,W/jxcore-log( 6145): Process ARCH arm
W/jxcore-log( 6145): 
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/jxcore-log( 6145): JXcore Cordova bridge is ready!,
I/jxcore-log( 6145): 
W/jxcore-log( 6145): JXcore engine is started
,I/Choreographer( 6145): Skipped 118 frames!  The application may be doing too much work on its main thread.
I/chromium( 6145): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/org.thaliproject.p2p.ThaliPermissions( 6145): execute: REQUEST_ACCESS_COARSE_LOCATION,
,I/chromium( 6145): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2658): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2658): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
I/jxcore-log( 6145): INFO testUtils Toggling radios to: true
I/jxcore-log( 6145): 
D/BluetoothAdapter( 6145): enable()
D/BluetoothAdapter( 6145): enable(): BT is already enabled..!
I/jxcore-log( 6145): Unit Test app is loaded
I/jxcore-log( 6145): 
D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
E/Watchdog( 1019): !@Sync 7
D/WifiService( 1019): setWifiEnabled: true pid=6145, uid=10167
W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=6145, uid=10167 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): Failed getting userId using ActivityManagerNative
W/WifiService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6145, uid=10167 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1019): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1019): name = wifi_on
I/chromium( 6145): [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/io.jxcore.node.JXcoreExtension( 6145): isBleMultipleAdvertisementSupported: SUPPORTED
,I/jxcore-log( 6145): INFO testUtils BLE multiple advertisement supported
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): My device name is: samsung-SM-A300FU
I/jxcore-log( 6145): 
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
I/jxcore-log( 6145): 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
I/jxcore-log( 6145): 
,I/io.jxcore.node.ConnectivityInfo( 6145): updateConnectivityInfo: ,
I/io.jxcore.node.ConnectivityInfo( 6145):     - is Wi-Fi Direct supported: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - is Bluetooth LE multiple advertisement supported: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - is Wi-Fi enabled: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - is Bluetooth enabled: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - BSSID name: f4:f2:6d:22:99:3e
I/io.jxcore.node.ConnectivityInfo( 6145):     - is connected/connecting to active network: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - active network type is Wi-Fi: true
I/io.jxcore.node.ConnectivityInfo( 6145):     - force notify: true
D/io.jxcore.node.JXcoreExtension( 6145): notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,I/jxcore-log( 6145): INFO thaliMobileNativeWrapper networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): INFO thaliMobileNativeWrapper Method networkChanged registered to native,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
I/jxcore-log( 6145): 
,V/AlarmManager( 1019): waitForAlarm result :8,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js,
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js,
I/jxcore-log( 6145): 
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,I/jxcore-log( 6145): --= Surplus to requirements =--
I/jxcore-log( 6145): 
,I/jxcore-log( 6145): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6145): 
,D/SSRM:n  ( 1019): SIOP:: AP = 310,
,D/AndroidRuntime( 6212): ,
D/AndroidRuntime( 6212): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6212): CheckJNI is OFF
,D/AndroidRuntime( 6212): readGMSProperty: start
D/AndroidRuntime( 6212): readGMSProperty: already setted!!
D/AndroidRuntime( 6212): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6212): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6212): readGMSProperty: end
D/AndroidRuntime( 6212): addProductProperty: start
,E/AffinityControl( 6212): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6212): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1019): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1019): START PACKAGE DELETE: observer{742722499}
D/PackageManager( 1019): pkg{<packageName>}
D/PackageManager( 1019): user{0}
D/PackageManager( 1019): caller{2000}
D/PackageManager( 1019): flags{3}
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1019): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1019): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1019): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1019): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1019): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1019): !@killApplicatoin: 10167, uninstall pkg
,I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
,I/ActivityManager( 1019): Killing 6145:com.test.thalitest/u0a167 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1019): Skipping PackageSetting{3cd8c80e com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1019):   Force finishing activity ActivityRecord{2e540e6b u0 com.test.thalitest/.MainActivity t23}
,E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1019): Focus left window: 6145,
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1019): Focused application released
E/JavaBinder( 1019): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager( 1019): Force stopping com.test.thalitest appid=10167 user=0: pkg removed
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1019): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 5984): Explicit concurrent mark sweep GC freed 94(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 964us total 40.768ms
,I/art     ( 3967): Explicit concurrent mark sweep GC freed 20269(1124KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 939us total 40.543ms
,I/InputReader( 1019): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1935): mOCRHelper is null
,I/KLMS-2.5.123: ( 3665): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Mar 11 15:39:06 GMT+01:00 2016
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3665): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1019): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1019): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1019): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): onCreate()
,E/Zygote  ( 6225): MountEmulatedStorage(),
E/Zygote  ( 6225): v2
I/libpersona( 6225): KNOX_SDCARD checking this for 10090
I/libpersona( 6225): KNOX_SDCARD not a persona
,I/SELinux ( 6225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6225 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,I/KLMS-2.5.123: ( 3665): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/SELinux ( 6225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6225): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 1827): Explicit concurrent mark sweep GC freed 17028(954KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 8MB/13MB, paused 1.380ms total 91.966ms
,W/GeofencerStateMachine( 1827): Ignoring removeGeofence because network location is disabled.
,E/DataBuffer( 1827): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@94876c9)
,I/KLMS-2.5.123: ( 3665): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/TimaKeyStoreProvider( 6225): TimaSignature is unavailable
,D/ActivityThread( 6225): Added TimaKeyStore provider
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): PACKAGE_REMOVED
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 48296(3MB) AllocSpace objects, 54(877KB) LOS objects, 33% free, 24MB/36MB, paused 3.022ms total 195.305ms
,I/art     ( 1019): WaitForGcToComplete blocked for 133.542ms for cause Explicit
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): listeningToPackageRemoved().START
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:15121( 6225): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6225): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6225): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6225): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/EnterpriseDeviceManagerService( 1019): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1019): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1019): no available spell checker services found
,D/RCPManagerService( 1019): PackageReceiver onReceive()
,D/elm:15121( 6225): ElmAgentService : onCreate()
,I/HarmonyEASService( 1019): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1019): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6225): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6225): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6225): MDMBridge.getInstance()
D/elm:15121( 6225): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6225): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6225): ElmAgentService : onDestroy().
,I/ActivityManager( 1019): Killing 5208:com.google.android.gm/u0a99 (adj 15): empty #31
,E/SMD     (  289): DCD OFF
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3665): KLMSIntentService(): onDestroy()
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 9887(555KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.773ms total 163.138ms
I/art     ( 1019): WaitForGcToComplete blocked for 226.787ms for cause Explicit
,W/ResourceType( 1019): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1019): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1019): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1019): delete codoeFile: 
,D/AASAuninstall( 1019): userId = 0, info.removedAppID = -1, info.uid = 10167, packageName = com.test.thalitest
I/AASA_removePackage( 1019): UID=10167 Target=com.test.thalitest
D/PackageManager( 1019): result of delete: 1{742722499}
D/AndroidRuntime( 6212): Shutting down VM
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1019): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1019): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10167
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1019): uID is 10167
V/EnterpriseBillingPolicy( 1019): Removed Packageuid is0
D/TaskPersister( 1019): removeObsoleteFile: deleting file=23_task.xml
V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1019): getProfileForApplication - exit null : containerId = 0
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1019): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1019): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1019): MSG_TYPE_APP_REMOVED::
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1019): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1019): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1019): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1019): failed to open /acct/uid_10099/pid_5208/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 5685): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5685): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5685): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5685): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/SA      ( 5785): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 6324(321KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 3.286ms total 164.026ms
,I/SA      ( 5785): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4992): PackagesMonitor onReceive :com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 5652): onReceive, action : android.intent.action.PACKAGE_REMOVED
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,I/TactileAssist( 1019): enable value -1
I/TactileAssist( 1019): internal enable value -1
I/TactileAssist( 1019): intensity value -1
I/TactileAssist( 1019): saveAppList value true
,D/Mms/FreeMessageReceiverService( 5652): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService( 5652): onHandleIntent: ACTION_PACKAGE_REMOVED
,I/TactileAssist( 1019): List of disabled apps :
,D/Compatibility( 5872): onReceive() it will make start service
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5872): onHandleIntent()
,D/Compatibility( 5872): intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/Compatibility( 5872): found: 2
,D/Compatibility( 5872): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5872): skipping ResolveInfo{142d3ef1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
I/libpersona( 6245): KNOX_SDCARD checking this for 10055
D/Compatibility( 5872): considering ResolveInfo{3fd76ad6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
I/libpersona( 6245): KNOX_SDCARD not a persona
D/Compatibility( 5872): default: com.sec.android.app.soundalive.SAControlPanelActivity
E/Zygote  ( 6245): MountEmulatedStorage()
E/Zygote  ( 6245): v2
,I/SELinux ( 6245): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/Compatibility( 5872): enabling receiver ResolveInfo{8c9e157 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/SELinux ( 6245): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6245): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1019): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6245 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,D/Compatibility( 5872): enabling receiver ResolveInfo{20e7a444 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5872): enabling receiver ResolveInfo{2745d92d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5872): enabling receiver ResolveInfo{26b75e62 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 6245): TimaSignature is unavailable
,D/ActivityThread( 6245): Added TimaKeyStore provider
,W/art     ( 6212): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/Compatibility( 5872): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/UserAnalysis.PlaceProvider( 6245): PlaceProvider onCreate()
,D/UserAnalysis.SecureDbManager( 6245): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 6245): SecurePlaceDbHelper() ,
D/UserAnalysis( 6245): Create SecureDbHelper
,D/IntelligenceServiceApplication( 6245): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 6245): Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,E/SQLiteLog( 6245): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6245): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteDatabase( 6245): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteDatabase( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6245): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6245): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 6245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
E/SQLiteOpenHelper( 6245): 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
E/SQLiteOpenHelper( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteOpenHelper( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteOpenHelper( 6245): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ContextImpl( 5896): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
W/SQLiteOpenHelper( 6245): Opened privacy in read-only mode
,D/IntelligenceServiceApplication( 6245): no applications having user consent for prediction
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,V/PlaceDetection v1.0.19 ( 6245): [PlaceDetection::stopService] Service stopped.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,V/PlaceDetection v1.0.19 ( 6245): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,E/SQLiteLog( 6245): (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,E/Zygote  ( 6263): MountEmulatedStorage()
I/libpersona( 6263): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6263): v2
I/libpersona( 6263): KNOX_SDCARD not a persona
E/SQLiteLog( 5896): (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
I/ActivityManager( 1019): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6263 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteDatabase( 5896): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 5896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 5896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 5896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5896): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 5896): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
E/SQLiteDatabase( 5896): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5896): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 5896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 5896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 5896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 5896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
W/System.err( 5896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
W/System.err( 5896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
W/System.err( 5896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
W/System.err( 5896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
W/System.err( 5896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
W/System.err( 5896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
W/System.err( 5896): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 5896): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
W/System.err( 589,6): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 5896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5896): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5896): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 1019): Killing 5582:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
E/SQLiteDatabase( 6245): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 6245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/SQLiteDatabase( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/SQLiteDatabase( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6245): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6245): Shutting down VM
E/AndroidRuntime( 6245): FATAL EXCEPTION: main
E/AndroidRuntime( 6245): Process: com.samsung.android.intelligenceservice, PID: 6245
E/AndroidRuntime( 6245): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6245): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6245): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6245): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:204)
E/AndroidRuntime( 6245): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:78)
E/AndroidRuntime( 6245): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6245): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6245): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6245): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6245): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6245): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6245): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6245): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
I/Process ( 6245): Sending signal. PID: 6245 SIG: 9
D/TimaKeyStoreProvider( 6263): TimaSignature is unavailable
D/ActivityThread( 6263): Added TimaKeyStore provider
E/DropBoxManagerService( 1019): Can't write: system_app_crash
E/DropBoxManagerService( 1019): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1019): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1019): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1019): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1019): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
E/DropBoxManagerService( 1019): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1019): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1019): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1019): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1019): 	... 5 more

```
