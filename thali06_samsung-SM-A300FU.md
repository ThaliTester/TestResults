#### Test 5065027881383b1_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  293): DCD OFF
,D/AndroidRuntime( 6084): 
D/AndroidRuntime( 6084): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6084): CheckJNI is OFF
D/AndroidRuntime( 6084): readGMSProperty: start
D/AndroidRuntime( 6084): readGMSProperty: already setted!!
D/AndroidRuntime( 6084): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6084): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6084): readGMSProperty: end
D/AndroidRuntime( 6084): addProductProperty: start
E/AffinityControl( 6084): AffinityControl: registerfunction enter
D/AndroidRuntime( 6084): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1019): inState():  stateMachine is null !!
I/PersonaManagerService( 1019): PersonaId don't exist
I/ActivityManager( 1019): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1019): mDVFSHelper.acquire()
D/FocusedStackFrame( 1019): Set to : 0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1019): *FMB* installDecor flags : 25362712
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
I/ActivityManager( 1019): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6096 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1019): Focused application set to: xxxx
D/InputDispatcher( 1019): Focus left window: 1482
E/Zygote  ( 6096): MountEmulatedStorage()
E/Zygote  ( 6096): v2
I/libpersona( 6096): KNOX_SDCARD checking this for 10338
I/libpersona( 6096): KNOX_SDCARD not a persona
D/AndroidRuntime( 6084): Shutting down VM
I/SELinux ( 6096): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6096): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6096): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1019): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6096): TimaSignature is unavailable
D/ActivityThread( 6096): Added TimaKeyStore provider
V/WindowManager( 1019): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1019): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1019): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1019):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1482): updateVisibility : ActivityRecord{3d275347 token=android.os.BinderProxy@1719183e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1482): onTrimMemory. Level: 20
I/WebViewFactory( 6096): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6096): Time to load native libraries: 2 ms (timestamps 5099-5101)
I/LibraryLoader( 6096): Expected native library version number "",actual native library version number ""
W/art     ( 6084): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 6096): Binding Chromium to main looper Looper (main, tid 1) {378d2205}
I/LibraryLoader( 6096): Expected native library version number "",actual native library version number ""
I/chromium( 6096): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6096): Initializing chromium process, singleProcess=true
,W/art     ( 6096): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6096): ApplicationContext is null in ApplicationStatus
,W/chromium( 6096): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6096): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6096): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6096): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6096): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6096): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6096): Local Branch: 
I/Adreno-EGL( 6096): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6096): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6096):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6096): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6096): onDetachedFromWindow called when already detached. Ignoring,
,D/PhoneWindow( 6096): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6096): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6096): CordovaWebView is running on device made by: samsung
,W/art     ( 6096): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6096): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1019): Activity pause timeout for ActivityRecord{362f3708 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6096): Render dirty regions requested: true
,D/ActivityManager( 1019): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1019): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1019): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1019): handleActiveUserChange for user 0
D/PersonaManagerService( 1019): getPersonasForUser(): returning null!
,W/chromium( 6096): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6096): updateVisibility : ActivityRecord{221b58d6 token=android.os.BinderProxy@25c7498 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6096): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6096): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1019): Focus entered window: 6096
,D/PointerIcon( 1019): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1019): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6096): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6096): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6096): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6096): Enabling debug mode 0
,D/InputMethodManagerService( 1019): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,I/ActivityManager( 1019): Displayed Component not be shown by security: +649ms (total +39s198ms)
I/Timeline( 1019): Timeline: Activity_windows_visible id: ActivityRecord{362f3708 u0 com.test.thalitest/.MainActivity t20} time:155613
W/ActivityManager( 1019): mDVFSHelper.release()
W/IInputConnectionWrapper( 6096): showStatusIcon on inactive InputConnection
I/Timeline( 6096): Timeline: Activity_idle id: android.os.BinderProxy@25c7498 time:155618
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SamsungIME( 1885): getCurrentCandidateView
,D/SamsungIME( 1885): Dismiss ExpandCandiate
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1885): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1885): KeybaordView init() : load resources
,W/BindingManager( 6096): Cannot call determinedVisibility() - never saw a connection for the pid: 6096
,I/SamsungIME( 1885): getCurrentKeyboard
I/SamsungIME( 1885): getTextKeyboard
,D/SamsungIME( 1885): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6096): Set native->JS mode to OnlineEventsBridgeMode
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/jxcore_app_log( 6096): JniHelper::setJavaVM(0xb7098448), pthread_self() = -1218515728
,D/JX-Cordova( 6096): jxcore cordova android initializing
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2628): Disconnected process message: 10
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,W/jxcore-log( 6096): Initializing JXcore engine
W/jxcore-log( 6096): JXcore engine is ready
,W/jxcore-log( 6096): Starting JXcore engine
,E/audit   ( 1879): type=1400 msg=audit(1449752964.016:205): avc:  denied  { ioctl } for  pid=6096 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1879):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1879): type=1300 msg=audit(1449752964.016:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be8cbd58 items=0 ppid=309 ppcomm=main pid=6096 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1879): type=1320 msg=audit(1449752964.016:205): 
,W/jxcore-log( 6096): Platform android
W/jxcore-log( 6096): 
W/jxcore-log( 6096): Process ARCH arm
W/jxcore-log( 6096): 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6096): JXcore Cordova bridge is ready!,
I/jxcore-log( 6096): 
W/jxcore-log( 6096): JXcore engine is started
I/Choreographer( 6096): Skipped 125 frames!  The application may be doing too much work on its main thread.
I/chromium( 6096): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6096): Toggling radios to true,
I/jxcore-log( 6096): 
,D/BluetoothAdapter( 6096): enable(),
,D/BluetoothAdapter( 6096): enable(): BT is already enabled..!,
,D/SecContentProvider( 1019): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1019): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1019): mCursor = null
D/WifiService( 1019): setWifiEnabled: true pid=6096, uid=10338
W/ActivityManager( 1019): Permission Denial: getCurrentUser() from pid=6096, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1019): Failed getting userId using ActivityManagerNative,
W/WifiService( 1019): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6096, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1019): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1019): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1019): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1019): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1019): name = wifi_on,
I/WifiService( 1019): disconnect: pid=6096, uid=10338,
I/wpa_supplicant( 1388): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6096): Radios toggled,
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Got Device Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): Perf Test app loaded loaded
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): check test folder
I/jxcore-log( 6096): 
,I/jxcore-log( 6096): found test : ./testFindPeers.js
I/jxcore-log( 6096): 
,I/wpa_supplicant( 1388): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1388): wlan0: State: COMPLETED -> DISCONNECTED,
I/wpa_supplicant( 1388): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1388): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1388): Cmd 35605 not handled
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): InitialState.processMessage what=4
E/WifiStateMachine( 1019): WifiStateMachine: Leaving Connected state
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1388): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1388): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1388): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1388): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1388): First Scan Start
I/wpa_supplicant( 1388): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1019): No numeric data
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1019): clearTetheredNotification()
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
,I/jxcore-log( 6096): found test : ./testSendData.js
I/jxcore-log( 6096): 
D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1173): updateTetherState():false, false
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,E/WifiNative-wlan0( 1019): do suspend true
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,V/NetworkStats( 1019): performPollLocked() took 12ms
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  280): Clearing all IP addresses on wlan0
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,V/NativeCrypto( 1734): Read error: ssl=0xb74b5428: I/O error during system call, Connection timed out
E/ConnectivityService( 1019): updateNetworkInfo()
,E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1019): Start Disconnecting Watchdog 1
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xb74b5428: I/O error during system call, Broken pipe
,I/wpa_supplicant( 1388): wlan0: Setting scan request: 0 sec 0 usec
I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71927c8
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223088840)
E/WifiNative-wlan0( 1019): do suspend true
D/WifiP2pService( 1019): InactiveState{ what=143375 }
D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
D/ConnectivityService( 1019): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1019): Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1019, getuid(): 1000
I/qtaguid ( 1019): Untagging socket 348
I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223088840) wakelock released: 1, error no: 0,
I/rmt_storage(  274): 
,I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71927c8
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #8
I/Hs20UtilService( 1641): Message received 5007
D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1360): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1360): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1360): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1019): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/ConnectivityService( 1019): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ConnectivityService( 1019): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1019): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1019): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1458): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1019): nai.networkMonitor.doQuit()
D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): doQuit - quitNow(),
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): updateIfacesLocked(),
V/NetworkStats( 1019): performPollLocked(flags=0x1),
D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1173): EthernetConnected: false
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0,
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): performPollLocked() took 7ms
D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Choreographer( 6096): Skipped 106 frames!  The application may be doing too much work on its main thread.
D/WifiNetworkAgent( 1019): NetworkAgent: NetworkAgent channel lost
,I/chromium( 6096): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
I/Hs20UtilService( 1641): Starting #9
I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1360): DMSUtil.isNetworkConnected - flag-null, state-null
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1360): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1360): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1360): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3,
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,D/PhoneApp( 1458): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1458): FileWriteThread : threadType = 3
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1019): updateDataUsageMap,
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): noConnectivity : true
,I/splitIntent( 1019): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1019): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1019): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6171): MountEmulatedStorage()
I/libpersona( 6171): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6171): v2
I/libpersona( 6171): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6171 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6171): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6171): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6171): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6171): TimaSignature is unavailable
,D/ActivityThread( 6171): Added TimaKeyStore provider,
,I/MusicStore( 6171): Database version: 120
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6171): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6171): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6171): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6171): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6171): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/wpa_supplicant( 1388): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 1388): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 1388): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1388): Trying to associate with  'G700'
I/wpa_supplicant( 1388): Re-associate with C0.AA.48
I/wpa_supplicant( 1388): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1019): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,V/JNIHelp ( 6171): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/wpa_supplicant( 1388): Cmd 35605 not handled
I/wpa_supplicant( 1388): wlan0: State: ASSOCIATING -> ASSOCIATED
,I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1388): Associated with C0.AA.48
,I/wpa_supplicant( 1388): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1388): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030,
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
D/Tethering( 1019): interfaceLinkStateChanged wlan0, false
D/Tethering( 1019): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1019): interfaceStatusChanged wlan0, false,
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1388): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/Nat464Xlat( 1019): interfaceLinkStateChanged wlan0, true,
,I/wpa_supplicant( 1388): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/Tethering( 1019): interfaceLinkStateChanged wlan0, true,
V/NetworkStats( 1019): performPollLocked(flags=0x1),
D/Tethering( 1019): interfaceStatusChanged wlan0, true
,D/HotspotTile( 1173): onReceive : android.net.conn.TETHER_STATE_CHANGED
I/wpa_supplicant( 1388): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/HotspotTile( 1173): updateTetherState():false, false
I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1388): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1388): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1388): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1388): Blacklist: Clear (temp) 
I/wpa_supplicant( 1388): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering( 1019): No numeric data
D/Tethering( 1019): interfaceLinkStateChanged wlan0, true
D/Tethering( 1019): interfaceStatusChanged wlan0, true
D/Tethering( 1019): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1019): clearTetheredNotification()
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,V/NetworkStats( 1019): performPollLocked() took 9ms
,D/WifiNative-wlan0( 1019): callSECApiVoid - ID [50]
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,E/WifiConfigStore( 1019): setLastSelectedConfiguration -1
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/ConnectivityService( 1019): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1019): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1019): updateNetworkInfo()
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,W/ActivityThread( 6171): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6171): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@255b80d2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6171): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6171): GMSCore installation verified
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ConfigStore( 6171): Config Database version: 1
,E/WifiConfigStore( 1019): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine( 1019): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1019): mCursor = null
,E/WifiNative-wlan0( 1019): do suspend false
,D/SecContentProvider2( 1019): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1019): mCursor = null
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1019): getStreamVolume 3 index 70
,I/MediaRouter( 6171): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6171): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1019): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6199): MountEmulatedStorage()
E/Zygote  ( 6199): v2
I/libpersona( 6199): KNOX_SDCARD checking this for 10001
I/libpersona( 6199): KNOX_SDCARD not a persona
,I/SELinux ( 6199): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6199): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1019): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6199 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6199): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6171): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6199): TimaSignature is unavailable
,I/GoogleURLConnFactory( 6171): Using platform SSLCertificateSocketFactory
,D/ActivityThread( 6199): Added TimaKeyStore provider
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1019): Killing 5557:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/dhcpcd  ( 6216): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6216): version 5.5.6 starting
,E/dhcpcd  ( 6216): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1019): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6222 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6222): MountEmulatedStorage()
I/libpersona( 6222): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6222): v2
I/libpersona( 6222): KNOX_SDCARD not a persona
I/SELinux ( 6222): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Killing 4188:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6222): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6222): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  309): Explicit concurrent mark sweep GC freed 8705(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 30.152ms
,I/dhcpcd  ( 6216): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6216): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6216): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6216): bssid match
,I/dhcpcd  ( 6216): wlan0: rebinding lease of 192.168.1.132
,D/TimaKeyStoreProvider( 6222): TimaSignature is unavailable
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 21.019ms
,D/ActivityThread( 6222): Added TimaKeyStore provider
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.458ms
,W/libprocessgroup( 1019): failed to open /acct/uid_10139/pid_5557/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_4188/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6222): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 6222): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6222): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6222): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6240): MountEmulatedStorage()
E/Zygote  ( 6240): v2
I/libpersona( 6240): KNOX_SDCARD checking this for 10008
I/libpersona( 6240): KNOX_SDCARD not a persona
,I/SELinux ( 6240): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1019): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6240 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1019): Killing 5174:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/SELinux ( 6240): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6240): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6240): TimaSignature is unavailable
,D/ActivityThread( 6240): Added TimaKeyStore provider
,W/libprocessgroup( 1019): failed to open /acct/uid_10032/pid_5174/cgroup.procs: No such file or directory
,I/ActivityManager( 1019): Killing 5652:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3672): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 14:09:28 GMT+01:00 2015
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3672): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3672): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3672): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6256): MountEmulatedStorage()
,E/Zygote  ( 6256): v2
I/libpersona( 6256): KNOX_SDCARD checking this for 10031
I/libpersona( 6256): KNOX_SDCARD not a persona
I/SELinux ( 6256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6256 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 6256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3672): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3672): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6256): TimaSignature is unavailable
,D/ActivityThread( 6256): Added TimaKeyStore provider
,I/SO_AGENT( 6256): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5719): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5761): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/DBG_POLICYDM( 5719): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5761): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5761): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5719): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SA      ( 5761): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5719): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5719): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5761): [OR] == isSIMCardReady false ==
,I/SA      ( 5761): [SCU] == networkStateCheck == false
I/SA      ( 5761): [OR] onReceive END
,I/ActivityManager( 1019): Killing 5259:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1579): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1579): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1579): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1579): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1579): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1579): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1579): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6273): MountEmulatedStorage(),
I/libpersona( 6273): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6273): v2
,I/libpersona( 6273): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6273 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1019): failed to open /acct/uid_1000/pid_5652/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6273): TimaSignature is unavailable
,D/ActivityThread( 6273): Added TimaKeyStore provider
,W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6273): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6273): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6273): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6288): MountEmulatedStorage()
E/Zygote  ( 6288): v2
,I/libpersona( 6288): KNOX_SDCARD checking this for 10141
I/libpersona( 6288): KNOX_SDCARD not a persona
,I/SELinux ( 6288): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6288): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6288 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5672:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/SELinux ( 6288): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6288): TimaSignature is unavailable
,D/ActivityThread( 6288): Added TimaKeyStore provider
,W/ResourcesManager( 6288): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6288): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6288): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6288): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,W/libprocessgroup( 1019): failed to open /acct/uid_10014/pid_5259/cgroup.procs: No such file or directory
,W/libprocessgroup( 1019): failed to open /acct/uid_10087/pid_5672/cgroup.procs: No such file or directory
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 5801): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/BadgeProvider( 5801): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5801): sendNotify, [notify] : null
D/BadgeProvider( 5801): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5801): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5801): update, [UpdateCount] : 1
,D/Launcher.Model( 1482): reloadBadges entered.,
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6311): MountEmulatedStorage()
,I/libpersona( 6311): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6311): v2
I/libpersona( 6311): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6311 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1019): Killing 5274:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,I/SELinux ( 6311): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6311): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6311): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6311): TimaSignature is unavailable
,D/ActivityThread( 6311): Added TimaKeyStore provider
,D/SecurityLogAgent( 6311): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6311): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6311): StateMachine : Current State = 1
,D/SecurityLogAgent( 6311): StateMachine : Changed Current State = 1
,I/ActivityManager( 1019): Killing 5740:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/iu.Environment( 2056): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/iu.UploadsManager( 2056): num queued entries: 0
,I/iu.UploadsManager( 2056): num updated entries: 0
,I/iu.SyncManager( 2056): NEXT; no task,
W/ActivityManager( 1019): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/dhcpcd  ( 6216): wlan0: acknowledged 192.168.1.132 from 192.168.1.1,
,D/ChimeraCfgMgr( 2056): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5097): connection state changed from CONNECTED to DISCONNECTED,
,W/libprocessgroup( 1019): failed to open /acct/uid_10029/pid_5274/cgroup.procs: No such file or directory
,E/Zygote  ( 6331): MountEmulatedStorage(),
E/Zygote  ( 6331): v2
I/libpersona( 6331): KNOX_SDCARD checking this for 10032
I/libpersona( 6331): KNOX_SDCARD not a persona
,I/SELinux ( 6331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/dhcpcd  ( 6216): wlan0: leased 192.168.1.132 for 86400 seconds
,I/SELinux ( 6331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6331): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1019): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6331 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup( 1019): failed to open /acct/uid_10148/pid_5740/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6331): TimaSignature is unavailable,
,D/ActivityThread( 6331): Added TimaKeyStore provider
,E/SPPClientService( 6331): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6331): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6331): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6331): [SystemStateMoniter] Current Time : 162532
,E/SPPClientService( 6331): [SystemStateMoniter] No Connect : true
,D/SPPClientService( 6331): PushLog.txt file is not deleted.
,D/SPPClientService( 6331): PushLog.txt file is not deleted.
D/SPPClientService( 6331): ============PushLog. stop!
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6366): MountEmulatedStorage()
E/Zygote  ( 6366): v2
I/libpersona( 6366): KNOX_SDCARD checking this for 10110
I/libpersona( 6366): KNOX_SDCARD not a persona
I/SELinux ( 6366): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1019): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6366 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6366): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1019): Killing 5779:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
E/SELinux ( 6366): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6331): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6366): TimaSignature is unavailable
,D/ActivityThread( 6366): Added TimaKeyStore provider
,E/WifiNative-wlan0( 1019): do suspend true
,W/libprocessgroup( 1019): failed to open /acct/uid_10152/pid_5779/cgroup.procs: No such file or directory
,D/WifiP2pService( 1019): InactiveState{ what=143375 }
,E/WifiStateMachine( 1019): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1019): VerifyingLinkState enter
,D/WifiP2pService( 1019): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiNative-wlan0( 1019): callSECApiInt - ID [210]
,E/ConnectivityService( 1019): updateNetworkInfo()
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1019): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1019): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1019): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1019): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1019): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1019): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
,D/ConnectivityService( 1019): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1019): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1019): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1019): LTETest block dns file not exists
,D/StatusBar.NetworkController( 1173): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1019): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1019): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1019): updateNetworkInfo()
,E/ConnectivityService( 1019): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1019): (HTTPLog)-Static: isSBSettingEnabled false
,I/GAv4    ( 6366): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6366):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6366):   adb logcat -s GAv4
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
,W/ContextImpl( 6366): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/WifiTrafficPoller( 1019): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1019): mBoosterFLAG : 0
I/WifiTrafficPoller( 1019): current booster mode : FullMode
D/WifiNative-wlan0( 1019): callSECApiVoid - ID [212]
,D/ConnectivityService( 1019):    accepting network in place of null
,D/WIFI    ( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1458): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1458): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1019): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/CSLegacyTypeTracker( 1019): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/CSLegacyTypeTracker( 1019): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1019): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1019): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1019): MasterInitialState.processMessage what=3
D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1019): Not allowed due to - mEnabled false - primarySimSlot false
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): updateIfacesLocked()
V/NetworkStats( 1019): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1019): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1019): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,V/NetworkStats( 1019): performPollLocked() took 6ms
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
W/ContextImpl( 6366): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1019): currentTimeMillis() cache hit
V/NetworkStats( 1019): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1173): EthernetConnected: false
,D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
,D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
W/GAv4    ( 6366): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6366): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6366): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6366): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6366): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/System.out( 1019): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 10 Dec 2015 13:09:29 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449752969481], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449752969463]}
D/ConnectivityService( 1019): Validated NetworkAgentInfo [WIFI () - 503],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Don't send network conditions - lacking user consent.,
,D/ConnectivityService( 1019): rematching NetworkAgentInfo [WIFI () - 503],
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1019): Validated
D/ConnectivityService( 1019): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524290
D/ConnectivityService( 1019): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1173): EthernetConnected: false
D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1173): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1173): updateDataNetType()
D/StatusBar.NetworkController( 1173): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1173): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1173): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1173): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1173): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1173): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1173): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6366): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6366): Time to load native libraries: 2 ms (timestamps 3047-3049),
I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6366): Binding Chromium to main looper Looper (main, tid 1) {372e6f41}
,I/LibraryLoader( 6366): Expected native library version number "",actual native library version number ""
,I/chromium( 6366): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6366): Initializing chromium process, singleProcess=true
,W/art     ( 6366): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6366): ApplicationContext is null in ApplicationStatus
,W/chromium( 6366): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6366): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6366): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6366): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6366): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6366): Local Branch: 
I/Adreno-EGL( 6366): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6366): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6366):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6366): Requires BLUETOOTH permission
,I/NSApplication( 6366): Starting up...
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1019): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6430): MountEmulatedStorage()
E/Zygote  ( 6430): v2
I/libpersona( 6430): KNOX_SDCARD checking this for 10077
I/libpersona( 6430): KNOX_SDCARD not a persona
I/ActivityManager( 1019): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6430 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1019): Killing 5641:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 6430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6430): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6430): TimaSignature is unavailable
,D/ActivityThread( 6430): Added TimaKeyStore provider
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService( 1019): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/SMD     (  293): DCD OFF
,I/NetworkMonitor( 6171): type=WIFI subType= reason=null isConnected=true
,D/CountryDetector( 1019): No listener is left
,D/GpsLocationProvider( 1019): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 70181(3MB) AllocSpace objects, 14(276KB) LOS objects, 33% free, 23MB/35MB, paused 2.515ms total 158.889ms
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1019): mCursor = null
,W/libprocessgroup( 1019): failed to open /acct/uid_10041/pid_5641/cgroup.procs: No such file or directory
,V/AlarmManager( 1019): waitForAlarm result :4
,D/WaitQueueForNetworkActivate( 5989): notifyNetworkActivated
,W/ContextImpl( 5989): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1019): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5989): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5989): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5989): exit::IDLE
D/InitializeManagerStateMachine( 5989): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5989): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5989): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5989): entry::CHECK_COUNTRY_INFO,
D/InitializeManagerStateMachine( 5989): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5989): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5989): entry::SUCCESS
D/hcjo    ( 5989): AutoUpdateManager:INITCHECK:onInitializeSuccess,
W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1641): Starting #10
I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1360): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 5989): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5989): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1360): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 5989): exit::SUCCESS
D/InitializeManagerStateMachine( 5989): entry::IDLE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #11
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1360): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #12
,D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1360): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 1641): Message received 5007
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1360): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1360): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #13
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1360): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1360): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1019): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1019): mCursor = null
,D/ConnectivityService( 1019): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1019): mCursor = null
,D/SecContentProvider2( 1019): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1019): mCursor = null
,D/ConnectivityService( 1019): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1019): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
,I/splitIntent( 1019): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1019): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1019): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1019): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/ConnectivityManager.CallbackHandler( 1173): CM callback handler got msg 524295
,V/MusicLeanback( 6171): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6222): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6222): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1019): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019
,D/SRIB_DCS( 1173): log_dcs ThreadedRenderer::initialize entered! 
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 5719): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5719): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DBG_POLICYDM( 5719): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5719): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5344): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5344): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5344): [1] 5.onFinished: Scheduling replication attempt 5.
,I/FOTA_Client( 6240): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6240): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3672): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Dec 10 14:09:30 GMT+01:00 2015
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/ActivityManager( 1019): Killing 5814:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3672): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3672): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3672): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3672): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3672): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3672): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3672): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3672): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5719): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3672): KLMSIntentService(): onDestroy()
,I/SA      ( 5761): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5761): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5761): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5719): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5719): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5761): [OR] == isSIMCardReady false ==
E/DBG_POLICYDM( 5719): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5761): [SCU] == networkStateCheck == true
,I/DBG_POLICYDM( 5719): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5761): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5761): isChinaCountryCode : false
,I/SA      ( 5761): [SCU] is ChinestModel Data Restricted   : false
,I/SA      ( 5761): [OR] == networkStateCheck true ==
,I/SA      ( 5761): [OR] GetMyCountryZoneTask
,I/SA      ( 5761): [OR] onReceive END
,I/DBG_POLICYDM( 5719): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 5761): [SRS] prepareGetMyCountryZone
I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5719): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1579): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5761): [SSP] query invoked
,E/DBG_POLICYDM( 5719): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/daemonapp( 1622): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/SA      ( 5761): [TPMU] GetMccFromDB : null
I/SA      ( 5761): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5761): [TPM] isNoProxy(default) : true
,D/accuweather( 1579): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/SecContentProvider2( 1019): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1019): mCursor = null
,D/accuweather( 1579): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1579): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1579): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1019): failed to open /acct/uid_10042/pid_5814/cgroup.procs: No such file or directory
,E/File    ( 5761): fail readDirectory() errno=2
I/DBG_POLICYDM( 5719): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5719): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/accuweather( 1579): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1579): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6273): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6273): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6273): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/RCPManagerService( 1019): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6311): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6311): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6311): StateMachine : Current State = 1
,D/SecurityLogAgent( 6311): StateMachine : Changed Current State = 1
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 2056): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2056): num queued entries: 0
,I/iu.UploadsManager( 2056): num updated entries: 0
,I/iu.SyncManager( 2056): NEXT; no task
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2056): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2056): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6331): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6331): [SystemStateMoniter] Current Time : 164240
,E/SPPClientService( 6331): [SystemStateMoniter] No Connect : false
,I/System.out( 5097): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5097): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5989): AutoUpdateManager:IDLE:execute
,I/System.out( 5097): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/InitializeManagerStateMachine( 5989): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5989): exit::IDLE
D/InitializeManagerStateMachine( 5989): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5989): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5989): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5989): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5989): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5989): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5989): entry::SUCCESS
D/hcjo    ( 5989): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5989): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5989): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5989): exit::SUCCESS
,D/InitializeManagerStateMachine( 5989): entry::IDLE
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5097): connection state changed from DISCONNECTED to CONNECTED
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2056): [AccountUtils] Account not ready
W/Kids    ( 2056): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2056): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2056): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2056): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2056): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2056): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2056): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2056): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2056): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2056): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2056): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2056): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
,I/StatusBar( 1173): Icon Only
,D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1734): Connected
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1734): Message class com.google.f.a.a.p
,I/SA      ( 5761): [RC New] Execute method=[GET] start
,I/SA      ( 5761): [RC New] Security=[true]
,I/System.out( 5761): Thread-975(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5761): Thread-975(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5761): Thread-975(ApacheHTTPLog):isShipBuild true
,I/System.out( 5761): Thread-975(ApacheHTTPLog):SMARTBONDING_ENABLED is false
,I/System.out( 5761): Thread-975(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,I/jxcore-log( 6096): BLE supported!!
I/jxcore-log( 6096): 
,I/SA      ( 5761): [RC New] [v2liruge] api execute + 662
,I/SA      ( 5761): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5761): AsyncTask #1 calls detatch()
,I/SA      ( 5761): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5761): [OCP] update openData : PL
,I/SA      ( 5761): [TPMU] getNetworkMcc : 
,I/SA      ( 5761): [SCU] saveMccToPreferece Start
,I/SA      ( 5761): [SCU] RegionMCC : 260
,I/SA      ( 5761): [SSP] query invoked
,I/SA      ( 5761): [TPMU] GetMccFromDB : null
,I/SA      ( 5761): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5761): [SCU] saveMccToPreferece End
,I/SA      ( 5761): [RC New] executeRequest [v2liruge] end. 742
I/SA      ( 5761): [RC New] Execute end
,I/SA      ( 5761): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5761): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6216): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000,
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6171): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6171): Stop autocaching.
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 3495): callingUid 10011, callindPid: 3495
,E/GmsUtils( 6171): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6171): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
,I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  259): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1019): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1019) eventTime = 167338
,D/PowerManagerService( 1019): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1019 (0x0)
,D/PowerManagerService( 1019): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1019, ws=WorkSource{10049}) (elapsedTime=3475)
,E/Watchdog( 1019): !@Sync 5
,I/PowerManagerService( 1019): [PWL] Off : 105s ago
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5688): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): [GetString-S]
,I/ReactiveServiceManager( 5688): Supported : 1
,D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1019): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1019): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1019): handleString: Failed to handle string(-4)
,E/terrier ( 1019): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5688): [ensureRegistration] - No Samsung account
,E/SMD     (  293): DCD OFF
,I/dhcpcd  ( 6216): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1019): waitForAlarm result :4
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1734): Vacuum at: now=1449752978578 tag=VacuumService
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,W/Uploader( 1734): No account for auth token provided
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1734): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1734): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1734): (HTTPLog)-Thread-203-617062232: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1734): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,I/qtaguid ( 1734): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,W/Uploader( 1734): No account for auth token provided
,E/SMD     (  293): DCD OFF
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,W/Uploader( 1734):  no longer exists, so no auth token.
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 37807(2MB) AllocSpace objects, 30(1570KB) LOS objects, 39% free, 7MB/12MB, paused 1.367ms total 71.972ms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/Uploader( 1734): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1734): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1734): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1734): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1734): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1734): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1734): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1734): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true,
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,W/Uploader( 1734): No account for auth token provided
,I/System.out( 1734): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1734): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1734, getuid(): 10011
,E/SQLiteLog( 1734): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  ( 1019): SIOP:: AP = 300
,I/dhcpcd  ( 6216): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6216): wlan0: no IPv6 Routers available
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5989): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5989): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5989): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5989): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5989): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5989): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5989): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5989): entry::IDLE
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5989): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5989): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5989): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5989): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5989): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5989): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5989): entry::IDLE
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 290
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1019): waitForAlarm result :4
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5344): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5344): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5344): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,E/SMD     (  293): DCD OFF
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  293): DCD OFF,
,D/SSRM:n  ( 1019): SIOP:: AP = 290,
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 6,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 280
,I/PowerManagerService( 1019): [PWL] Off : 140s ago
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/Watchdog( 1019): !@Sync 7
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/PowerManagerService( 1019): [PWL] Off : 180s ago
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  293): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1019): !@Sync 8
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6017): Starting books sync for 61035162, extras: ade
,I/art     ( 1019): Explicit concurrent mark sweep GC freed 40250(2MB) AllocSpace objects, 44(713KB) LOS objects, 33% free, 24MB/36MB, paused 2.432ms total 156.561ms
,I/BooksConfig( 6017): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
D/PersonaManager( 1173): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
,D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6017): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6017): Soft error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6017): Sync error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6017): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 271778, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1019): SIOP:: AP = 270
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.,
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1019): !@Sync 9
,I/PowerManagerService( 1019): [PWL] Off : 225s ago
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF,
,V/AlarmManager( 1019): waitForAlarm result :4
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :8
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/TimaService( 1019): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1019): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1019): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1019): initializing...
,I/TLC_TIMA_PKM_initialize( 1019): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1019): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1019): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1019): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1019): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1019): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1019): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1019): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1019): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1019): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1019): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1019): Trustlet response is completed
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1019): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1019): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1019): stay LED for fully charged,
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate,
I/MotionRecognitionService( 1019): Plugged
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/Watchdog( 1019): !@Sync 10,
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,I/Atfwd_Sendcmd(  319): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  319): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1019): Plugged
D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1173): level :100 plugged : 2
,E/SMD     (  293): DCD OFF
,E/SMD     (  293): DCD OFF
,V/AlarmManager( 1019): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1173): handleTimeUpdate
,D/SecKeyguardClockView( 1173): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1173): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1173): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1173): *** don't update sliding image ***
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1173): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1173): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6017): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6017): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1019): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1019): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1019): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1173): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1173): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1173): Icon Only
I/StatusBar( 1173): Icon Only
D/PanelView( 1173): There is/are notification(s) 
D/PanelView( 1173): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1734): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1734): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1734): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1734): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1019): userId = 0, bbcId = -10000
,W/ActivityManager( 1019): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1019): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1173): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6017): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6017): Soft error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6017): Sync error
E/BooksSync( 6017): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6017): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6017): Finished books sync
,D/SyncManager( 1019): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 304729, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1019): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1019): mCursor = null
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,E/SMD     (  293): DCD OFF
,W/ContextImpl( 1019): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD OFF
,D/BatteryService( 1019): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1019): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1019): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1019): stay LED for fully charged
,D/BatteryService( 1019): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1019): Plugged,
I/MotionRecognitionService( 1019): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1173): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1173): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2628): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2628): Disconnected process message: 10
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1173): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1173): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1173): level :100 plugged : 2
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1019): [PWL] Off : 275s ago
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD OFF
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  319): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD OFF
,D/SSRM:n  ( 1019): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1019): Do not check CP during LCD off.
,E/SMD     (  293): DCD OFF

```
