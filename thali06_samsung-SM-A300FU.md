#### Test 549702613245198_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system,
D/SSRM:n  ( 1016): SIOP:: AP = 260
--------- beginning of main
E/SMD     (  289): DCD OFF
D/AndroidRuntime( 6039): 
D/AndroidRuntime( 6039): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6039): CheckJNI is OFF
D/AndroidRuntime( 6039): readGMSProperty: start
D/AndroidRuntime( 6039): readGMSProperty: already setted!!
D/AndroidRuntime( 6039): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6039): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6039): readGMSProperty: end
D/AndroidRuntime( 6039): addProductProperty: start
E/AffinityControl( 6039): AffinityControl: registerfunction enter
D/AndroidRuntime( 6039): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/FocusedStackFrame( 1016): Set to : 0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/Zygote  ( 6051): MountEmulatedStorage()
E/Zygote  ( 6051): v2
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6051 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1477
D/AndroidRuntime( 6039): Shutting down VM
I/libpersona( 6051): KNOX_SDCARD checking this for 10338
I/libpersona( 6051): KNOX_SDCARD not a persona
I/SELinux ( 6051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/SELinux ( 6051): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6051): TimaSignature is unavailable
D/ActivityThread( 6051): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1477): updateVisibility : ActivityRecord{92e38b3 token=android.os.BinderProxy@2201c7c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1477): onTrimMemory. Level: 20
I/WebViewFactory( 6051): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6051): Time to load native libraries: 2 ms (timestamps 4679-4681)
I/LibraryLoader( 6051): Expected native library version number "",actual native library version number ""
W/art     ( 6039): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6051): Binding Chromium to main looper Looper (main, tid 1) {31894a36}
,I/LibraryLoader( 6051): Expected native library version number "",actual native library version number ""
,I/chromium( 6051): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6051): Initializing chromium process, singleProcess=true
,W/art     ( 6051): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6051): ApplicationContext is null in ApplicationStatus
,W/chromium( 6051): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6051): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6051): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6051): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6051): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6051): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6051): Local Branch: 
I/Adreno-EGL( 6051): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6051): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6051):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6051): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6051): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6051): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6051): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6051): CordovaWebView is running on device made by: samsung
,W/art     ( 6051): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6051): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{38bc2050 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6051): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,W/chromium( 6051): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6051): updateVisibility : ActivityRecord{15879c3 token=android.os.BinderProxy@21534e7d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6051): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6051): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1016): Focus entered window: 6051
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101,
D/SRIB_DCS( 6051): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6051): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6051): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6051): Enabling debug mode 0
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +646ms (total +38s629ms)
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{38bc2050 u0 com.test.thalitest/.MainActivity t20} time:155189
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,W/IInputConnectionWrapper( 6051): showStatusIcon on inactive InputConnection,
,I/Timeline( 6051): Timeline: Activity_idle id: android.os.BinderProxy@21534e7d time:155202
,I/SamsungIME( 1886): getCurrentCandidateView
,D/SamsungIME( 1886): Dismiss ExpandCandiate
,I/SamsungIME( 1886): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1886): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1886): KeybaordView init() : load resources
,W/BindingManager( 6051): Cannot call determinedVisibility() - never saw a connection for the pid: 6051
,I/SamsungIME( 1886): getCurrentKeyboard
I/SamsungIME( 1886): getTextKeyboard
,D/SamsungIME( 1886): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6051): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6051): JniHelper::setJavaVM(0xb78c8448), pthread_self() = -1209922456
,D/JX-Cordova( 6051): jxcore cordova android initializing
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2653): Disconnected process message: 10
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
W/jxcore-log( 6051): Initializing JXcore engine
W/jxcore-log( 6051): JXcore engine is ready
W/jxcore-log( 6051): Starting JXcore engine
E/audit   ( 1905): type=1400 msg=audit(1452283729.379:205): avc:  denied  { ioctl } for  pid=6051 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1905):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1905): type=1300 msg=audit(1452283729.379:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bed09d58 items=0 ppid=304 ppcomm=main pid=6051 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1905): type=1320 msg=audit(1452283729.379:205): 
,W/jxcore-log( 6051): Platform android
W/jxcore-log( 6051): 
W/jxcore-log( 6051): Process ARCH arm
W/jxcore-log( 6051): 
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6051): JXcore Cordova bridge is ready!,
I/jxcore-log( 6051): 
W/jxcore-log( 6051): JXcore engine is started
,I/chromium( 6051): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6051): Toggling radios to true
I/jxcore-log( 6051): 
,D/BluetoothAdapter( 6051): enable()
,D/BluetoothAdapter( 6051): enable(): BT is already enabled..!
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: true pid=6051, uid=10338
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=6051, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1016): Failed getting userId using ActivityManagerNative,
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6051, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223),
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1016): name = wifi_on
,I/WifiService( 1016): disconnect: pid=6051, uid=10338
,I/wpa_supplicant( 1379): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6051): Radios toggled
I/jxcore-log( 6051): 
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1379): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1379): wlan0: State: COMPLETED -> DISCONNECTED,
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1379): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1379): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1379): Cmd 35605 not handled
D/Tethering( 1016): InitialState.processMessage what=4
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1379): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1379): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1379): P2P: Current p2p state = IDLE,
I/wpa_supplicant( 1379): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1379): First Scan Start
I/wpa_supplicant( 1379): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false,
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1016): No numeric data,
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/HotspotTile( 1170): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1170): updateTetherState():false, false
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 7ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/CommandListener(  277): Clearing all IP addresses on wlan0,
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1016): InactiveState{ what=143375 },
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
V/NativeCrypto( 1679): Read error: ssl=0xb7ce5c10: I/O error during system call, Connection timed out
E/WifiStateMachine( 1016): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1379): wlan0: Setting scan request: 0 sec 0 usec,
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7b807c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1212675960)
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1016): do suspend true
V/NativeCrypto( 1679): SSL shutdown failed: ssl=0xb7ce5c10: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1016): Tagging socket 339 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000,
,I/qtaguid ( 1016): Untagging socket 339,
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1696): Starting #8
,I/Hs20UtilService( 1696): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1212675960) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
,I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7b807c8
,E/Zygote  ( 6106): MountEmulatedStorage(),
E/Zygote  ( 6106): v2
I/libpersona( 6106): KNOX_SDCARD checking this for 10102
I/SELinux ( 6106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6106): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6106 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6106): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/CommandListener(  277): Clearing all IP addresses on wlan0
D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1459): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-8ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
,D/TimaKeyStoreProvider( 6106): TimaSignature is unavailable
D/ActivityThread( 6106): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
E/ConnectivityService( 1016): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1016): MasterInitialState.processMessage what=3
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1170): EthernetConnected: false
V/NetworkStats( 1016): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0,
E/StatusBar.NetworkController( 1170): updateLTEICONDataNetType:0
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,W/ResourcesManager( 6106): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,D/PhoneApp( 1459): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1459): FileWriteThread : threadType = 3
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,I/Babel_SMS( 6106): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6106): MmsConfig.loadMmsSettings
I/Babel_SMS( 6106): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6106): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6106): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6106): MmsConfig.loadFromResources
,E/Babel_SMS( 6106): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6106): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  284): getCameraInfo: X
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6106): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/Babel_Crash( 6106): startup - clean
,I/Babel   ( 6106): deleted: false for 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1696): Starting #9
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1696): Message received 5007
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6106): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6106): Unsupported mime audio/evrc
,W/AudioCapabilities( 6106): Unsupported mime audio/qcelp
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6106): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6106): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6106): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6106): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6106): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6106): Unsupported mime audio/evrc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6106): Unsupported mime video/wvc1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6106): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6106): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/VideoCapabilities( 6106): Unsupported mime video/wvc1
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/VideoCapabilities( 6106): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6106): Unsupported mime video/x-ms-wmv7
,I/ApplicationPolicy( 1016): updateDataUsageMap
,W/VideoCapabilities( 6106): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6106): Unsupported mime video/mp43
,W/VideoCapabilities( 6106): Unsupported mime video/sorenson
,W/VideoCapabilities( 6106): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6106): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6106): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6106): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6106): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6106): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1016): Killing 5150:com.google.android.gm/u0a99 (adj 15): empty #31
,I/vclib   ( 6106): onServiceConnected
,W/Babel   ( 6106): Attempted to change video mute state without an active call.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_5150/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1379): nl80211: Received scan results (4 BSSes),
I/wpa_supplicant( 1379): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1379): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1379): Trying to associate with  'G700'
I/wpa_supplicant( 1379): Re-associate with C0.AA.48
I/wpa_supplicant( 1379): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 0 for uid 10011
,I/PCWCLIENTTRACE_PushUtil( 5627): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5627): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5627): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5627): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1016): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/PCWCLIENTTRACE_SYSTEMReceiver( 5627): noConnectivity : true
I/splitIntent( 1016): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6155): MountEmulatedStorage()
E/Zygote  ( 6155): v2
I/libpersona( 6155): KNOX_SDCARD checking this for 10108
I/libpersona( 6155): KNOX_SDCARD not a persona
I/SELinux ( 6155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6155 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6155): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6155): TimaSignature is unavailable
,D/ActivityThread( 6155): Added TimaKeyStore provider
,E/wpa_supplicant( 1379): Cmd 35605 not handled,
,I/wpa_supplicant( 1379): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1379): Associated with C0.AA.48
I/wpa_supplicant( 1379): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1379): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1379): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
E/Tethering( 1016): No numeric data
I/wpa_supplicant( 1379): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1016): clearTetheredNotification()
I/wpa_supplicant( 1379): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1379): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1379): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1379): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1379): Blacklist: Clear (temp) 
I/wpa_supplicant( 1379): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/SecContentProvider2( 1016): mCursor = null
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/HotspotTile( 1170): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/HotspotTile( 1170): updateTetherState():false, false
,V/NetworkStats( 1016): performPollLocked() took 5ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  277): Setting iface cfg
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,E/WifiNative-wlan0( 1016): do suspend false
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,I/MusicStore( 6155): Database version: 120
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6155): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6155): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6155): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/dhcpcd  ( 6178): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6178): version 5.5.6 starting,
,E/dhcpcd  ( 6178): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,W/ResourcesManager( 6155): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6155): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6155): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/dhcpcd  ( 6178): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6178): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6178): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6178): bssid match
,I/dhcpcd  ( 6178): wlan0: rebinding lease of 192.168.1.132,
,W/ActivityThread( 6155): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6155): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38d1b1cf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6155): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6155): GMSCore installation verified
,I/ConfigStore( 6155): Config Database version: 1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 70
,I/MediaRouter( 6155): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6155): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,V/AlarmManager( 1016): waitForAlarm result :4
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6189): MountEmulatedStorage(),
I/libpersona( 6189): KNOX_SDCARD checking this for 10001,
,E/Zygote  ( 6189): v2
I/libpersona( 6189): KNOX_SDCARD not a persona
I/SELinux ( 6189): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6189 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6189): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6189): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6189): TimaSignature is unavailable
,D/ActivityThread( 6189): Added TimaKeyStore provider
,I/GHttpClientFactory( 6155): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6155): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1016): Killing 5525:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6208 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6208): MountEmulatedStorage()
,E/Zygote  ( 6208): v2
I/libpersona( 6208): KNOX_SDCARD checking this for 1000
I/libpersona( 6208): KNOX_SDCARD not a persona
,I/SELinux ( 6208): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Killing 4142:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6208): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6208): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6208): TimaSignature is unavailable
,D/ActivityThread( 6208): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6208): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_5525/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4142/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6208): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6208): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6208): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6223): MountEmulatedStorage()
,E/Zygote  ( 6223): v2
I/libpersona( 6223): KNOX_SDCARD checking this for 10008
I/libpersona( 6223): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6223 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Killing 5224:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6223): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6223): TimaSignature is unavailable
,I/art     (  304): Explicit concurrent mark sweep GC freed 8682(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 26.608ms
,D/ActivityThread( 6223): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 16.597ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 654us total 16.651ms
,I/ActivityManager( 1016): Killing 5605:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:08:52 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6239): MountEmulatedStorage()
,E/Zygote  ( 6239): v2
,I/libpersona( 6239): KNOX_SDCARD checking this for 10031
I/SELinux ( 6239): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6239): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6239 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux ( 6239): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_5224/cgroup.procs: No such file or directory
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/SELinux ( 6239): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3669): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6239): TimaSignature is unavailable
,D/ActivityThread( 6239): Added TimaKeyStore provider
,I/SO_AGENT( 6239): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5659): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5605/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5659): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5659): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5659): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5659): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5709): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5709): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5709): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5709): [SLFUCHKMGR] constructor called
,I/SA      ( 5709): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5709): [OR] == isSIMCardReady false ==
,I/SA      ( 5709): [SCU] == networkStateCheck == false
,I/SA      ( 5709): [OR] onReceive END
,I/ActivityManager( 1016): Killing 5132:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1598): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1640): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1598): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1598): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1598): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1598): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1598): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1598): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6256): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6256 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 6256): v2
I/libpersona( 6256): KNOX_SDCARD checking this for 10121
I/libpersona( 6256): KNOX_SDCARD not a persona
,I/SELinux ( 6256): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6256): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6256): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6256): TimaSignature is unavailable
,D/ActivityThread( 6256): Added TimaKeyStore provider
,W/ResourcesManager( 6256): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6256): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6256): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SMD     (  289): DCD OFF
,D/QuickConnect( 6256): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,I/QuickConnect( 6256): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6256): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5132/cgroup.procs: No such file or directory
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Zygote  ( 6271): MountEmulatedStorage(),
E/Zygote  ( 6271): v2,
,I/SELinux ( 6271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6271): KNOX_SDCARD checking this for 10141
I/libpersona( 6271): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6271 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5642:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6271): TimaSignature is unavailable
,D/ActivityThread( 6271): Added TimaKeyStore provider
,W/ResourcesManager( 6271): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6271): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6271): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/libprocessgroup( 1016): failed to open /acct/uid_10087/pid_5642/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 5761): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 5761): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5761): sendNotify, [notify] : null
D/BadgeProvider( 5761): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5761): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5761): update, [UpdateCount] : 1
,D/Launcher.Model( 1477): reloadBadges entered.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6178): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6295): MountEmulatedStorage(),
,E/Zygote  ( 6295): v2
I/libpersona( 6295): KNOX_SDCARD checking this for 1000
I/libpersona( 6295): KNOX_SDCARD not a persona
,I/SELinux ( 6295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6295 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 6295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6295): TimaSignature is unavailable
,D/ActivityThread( 6295): Added TimaKeyStore provider
,I/dhcpcd  ( 6178): wlan0: leased 192.168.1.132 for 86400 seconds,
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 56077(3MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 23MB/35MB, paused 2.761ms total 189.158ms
,I/ActivityManager( 1016): Killing 5234:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/SecurityLogAgent( 6295): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6295): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6295): StateMachine : Current State = 1
,D/SecurityLogAgent( 6295): StateMachine : Changed Current State = 1,
,I/ActivityManager( 1016): Killing 5698:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1924): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1924): num queued entries: 0
,I/iu.UploadsManager( 1924): num updated entries: 0
,I/iu.SyncManager( 1924): NEXT; no task
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1924): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6336): MountEmulatedStorage(),
E/Zygote  ( 6336): v2
I/libpersona( 6336): KNOX_SDCARD checking this for 10032
I/libpersona( 6336): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6336 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6336): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/SELinux ( 6336): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1016): failed to open /acct/uid_10029/pid_5234/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10148/pid_5698/cgroup.procs: No such file or directory
,E/SELinux ( 6336): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Babel   ( 6106): connection state changed from UNKNOWN to DISCONNECTED
,D/TimaKeyStoreProvider( 6336): TimaSignature is unavailable
,D/ActivityThread( 6336): Added TimaKeyStore provider
,E/WifiNative-wlan0( 1016): do suspend true
,E/SPPClientService( 6336): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6336): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6336): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6336): [SystemStateMoniter] Current Time : 160855
,E/SPPClientService( 6336): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6336): PushLog.txt file is not deleted.
,D/SPPClientService( 6336): PushLog.txt file is not deleted.
D/SPPClientService( 6336): ============PushLog. stop!
,E/Zygote  ( 6353): MountEmulatedStorage(),
I/libpersona( 6353): KNOX_SDCARD checking this for 10110
E/Zygote  ( 6353): v2,
I/libpersona( 6353): KNOX_SDCARD not a persona
I/SELinux ( 6353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6353 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5733:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/SELinux ( 6353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1016): VerifyingLinkState enter
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SELinux ( 6353): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1016): Adding iface wlan0 to network 503
,D/TimaKeyStoreProvider( 6353): TimaSignature is unavailable
,D/ActivityThread( 6353): Added TimaKeyStore provider
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 503
E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
E/SPPClientService( 6336): [[SystemStateMonitorService]] No Active Internet
D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1016): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1016): LTETest block dns file not exists
D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1016): updateNetworkInfo()
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1016): Failed to clear dns cache for: com.sec.android.widgetapp.tapandpay
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
D/ConnectivityService( 1016):    accepting network in place of null
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1459): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1459): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
I/WifiTrafficPoller( 1016): current booster mode : FullMode
D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1016): MasterInitialState.processMessage what=3
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked() took 4ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): EthernetConnected: false
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1170): updateDataNetType()
D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1170): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5733/cgroup.procs: No such file or directory
,I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:08:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283733560], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283733543]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
,D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1170): EthernetConnected: false
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1170): updateDataNetType()
,D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1170): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1170): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GAv4    ( 6353): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6353):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6353):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6353): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6353): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6353): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6353): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6353): Time to load native libraries: 1 ms (timestamps 1450-1451)
,I/LibraryLoader( 6353): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6353): Binding Chromium to main looper Looper (main, tid 1) {38a81282}
,I/LibraryLoader( 6353): Expected native library version number "",actual native library version number ""
,I/chromium( 6353): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/BrowserStartupController( 6353): Initializing chromium process, singleProcess=true
,W/art     ( 6353): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6353): ApplicationContext is null in ApplicationStatus
,I/NetworkMonitor( 6155): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/chromium( 6353): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6353): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6353): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6353): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6353): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6353): Local Branch: 
I/Adreno-EGL( 6353): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6353): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6353):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/AudioManagerAndroid( 6353): Requires BLUETOOTH permission
,I/NSApplication( 6353): Starting up...
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6414): MountEmulatedStorage(),
E/Zygote  ( 6414): v2
I/libpersona( 6414): KNOX_SDCARD checking this for 10077
I/libpersona( 6414): KNOX_SDCARD not a persona
,I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6414 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5594:com.android.mms/u0a41 (adj 15): empty #31
I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
,D/ActivityThread( 6414): Added TimaKeyStore provider
,D/CountryDetector( 1016): No listener is left
,W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_5594/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 5944): notifyNetworkActivated
,W/ContextImpl( 5944): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1016): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
D/InitializeManagerStateMachine( 5944): entry::IDLE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1696): Starting #10
,I/ActivityManager( 1016): Killing 5771:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/Hs20UtilService( 1696): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,I/Hs20UtilService( 1696): Starting #11
,I/Hs20UtilService( 1696): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1696): Starting #12
,I/Hs20UtilService( 1696): Message received 5007
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1696): Starting #13
,I/Hs20UtilService( 1696): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5627): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5627): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5627): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5627): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1016): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6155): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 6208): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6208): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1170): log_dcs ThreadedRenderer::initialize entered! 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/DBG_POLICYDM( 5659): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5659): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5659): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5659): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5771/cgroup.procs: No such file or directory
,I/FOTA_Client( 6223): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6223): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/GCM     ( 1679): Connected
,D/GCM     ( 1679): Message class com.google.f.a.a.p
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:08:54 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/KLMS-2.5.123: ( 3669): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3669): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3669): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3669): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3669): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3669): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5659): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5659): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5659): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5659): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5709): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5709): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5709): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5709): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5709): [OR] == isSIMCardReady false ==
,I/SA      ( 5709): [SCU] == networkStateCheck == true
,I/SA      ( 5709): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5709): isChinaCountryCode : false
I/SA      ( 5709): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5709): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5659): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5709): [OR] GetMyCountryZoneTask
,I/SA      ( 5709): [OR] onReceive END
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5709): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5659): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/accuweather( 1598): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/SA      ( 5709): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5709): [SSP] query invoked
I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5659): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/SA      ( 5709): [TPMU] GetMccFromDB : null
I/SA      ( 5709): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5709): [TPM] isNoProxy(default) : true
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/daemonapp( 1640): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/SecContentProvider2( 1016): mCursor = null
,D/accuweather( 1598): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1598): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1598): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1598): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1598): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5659): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1598): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6256): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6256): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6256): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5659): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5659): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/File    ( 5709): fail readDirectory() errno=2
,D/SecurityLogAgent( 6295): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6295): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6295): StateMachine : Current State = 1
,D/SecurityLogAgent( 6295): StateMachine : Changed Current State = 1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1016): Tagging socket 339 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,I/qtaguid ( 1016): Untagging socket 339
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 20:08:55 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452283735033], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452283735018]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated,
D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 503]
I/iu.Environment( 1924): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524290
,D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/iu.UploadsManager( 1924): num queued entries: 0
,I/iu.UploadsManager( 1924): num updated entries: 0
,I/iu.SyncManager( 1924): NEXT; no task
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1924): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1924): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6336): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6336): [SystemStateMoniter] Current Time : 162589
,E/SPPClientService( 6336): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6106): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6106): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6106): (HTTPLog)-Static: isShipBuild true
I/System.out( 6106): (HTTPLog)-Thread-1043-688718937: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6106): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10102
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6106): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK,
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/Kids    ( 1924): [AccountUtils] Account not ready
W/Kids    ( 1924): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1924): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1924): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1924): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1924): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1924): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1924): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1924): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1924): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1924): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1924): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1924): 	at java.lang.Thread.run(Thread.java:818)
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
D/InitializeManagerStateMachine( 5944): entry::IDLE
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1170): Icon Only
,I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 6106): connection state changed from DISCONNECTED to CONNECTED
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5709): [RC New] Execute method=[GET] start
,I/SA      ( 5709): [RC New] Security=[true]
,I/System.out( 5709): Thread-965(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5709): Thread-965(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5709): Thread-965(ApacheHTTPLog):isShipBuild true
I/System.out( 5709): Thread-965(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5709): Thread-965(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10036
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1016): waitForAlarm result :4
,I/dhcpcd  ( 6178): wlan0: sending IPv6 Router Solicitation
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5309): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5309): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5309): [1] 5.onFinished: Scheduling replication attempt 5.
,I/SA      ( 5709): [RC New] [v2liruge] api execute + 643
,I/SA      ( 5709): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5709): AsyncTask #1 calls detatch()
,I/SA      ( 5709): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5709): [OCP] update openData : PL
,I/SA      ( 5709): [TPMU] getNetworkMcc : 
,I/SA      ( 5709): [SCU] saveMccToPreferece Start
,I/SA      ( 5709): [SCU] RegionMCC : 260
I/SA      ( 5709): [SSP] query invoked
,I/SA      ( 5709): [TPMU] GetMccFromDB : null
,I/SA      ( 5709): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5709): [SCU] saveMccToPreferece End
,I/SA      ( 5709): [RC New] executeRequest [v2liruge] end. 693
I/SA      ( 5709): [RC New] Execute end
I/SA      ( 5709): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5709): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 1016): SIOP:: AP = 320
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/AlarmManager( 1016): waitForAlarm result :4
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6155): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6155): Stop autocaching.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/WearableService( 4792): callingUid 10011, callindPid: 4792
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,E/GmsUtils( 6155): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6155): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/GCM     ( 1679): Connected
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1679): Message class com.google.f.a.a.p
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 165689
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10049}) (elapsedTime=3477)
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2653): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1170): level :100 plugged : 2
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5627): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5627): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5627): [GetString-S]
,I/ReactiveServiceManager( 5627): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5627): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5627): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5627): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5627): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5627): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5627): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1016): waitForAlarm result :8
,I/dhcpcd  ( 6178): wlan0: sending IPv6 Router Solicitation
,E/Watchdog( 1016): !@Sync 5
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,I/jxcore-log( 6051): Test app app.js loaded
I/jxcore-log( 6051): 
,I/chromium( 6051): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  289): DCD OFF
,I/dhcpcd  ( 6178): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6178): wlan0: no IPv6 Routers available
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate,
,D/SecKeyguardClockView( 1170): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1170): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1170): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1679): Vacuum at: now=1452283745039 tag=VacuumService
,I/GoogleURLConnFactory( 1679): Using platform SSLCertificateSocketFactory
,W/Uploader( 1679): No account for auth token provided
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1679): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1679): (HTTPLog)-Static: isShipBuild true
I/System.out( 1679): (HTTPLog)-Thread-200-539833368: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,I/System.out( 1679): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,I/qtaguid ( 1679): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,W/Uploader( 1679): No account for auth token provided
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,W/Uploader( 1679): No account for auth token provided
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,W/Uploader( 1679): No account for auth token provided
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,W/Uploader( 1679):  no longer exists, so no auth token.
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,W/Uploader( 1679): No account for auth token provided
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,I/art     ( 1679): Background sticky concurrent mark sweep GC freed 43716(2MB) AllocSpace objects, 46(2MB) LOS objects, 35% free, 8MB/12MB, paused 8.231ms total 54.306ms
,I/art     ( 1679): WaitForGcToComplete blocked for 16.318ms for cause Explicit
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 6060(262KB) AllocSpace objects, 3(192KB) LOS objects, 39% free, 7MB/12MB, paused 1.374ms total 61.963ms
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 42068(2MB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 23MB/35MB, paused 2.460ms total 152.779ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
E/Uploader( 1679): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1679): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1679): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1679): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1679, getuid(): 10011
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged,
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2653): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5309): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5309): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5309): [1] 5.onFinished: Giving up after 6 failures.
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1016): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,V/AlarmManager( 1016): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2653): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2653): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2653): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1170): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1170): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1016): !@Sync 8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/SecKeyguardClockView( 1170): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1170): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5973): Starting books sync for 61035162, extras: ade
,D/SViewCoverWidget( 1170): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 5973): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1170): Icon Only
I/StatusBar( 1170): Icon Only
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1170): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 5973): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5973): Soft error
E/BooksSync( 5973): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5973): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 5973): Sync error
E/BooksSync( 5973): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5973): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5973): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 273075, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1016): waitForAlarm result :8
,E/Watchdog( 1016): !@Sync 9
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
D/SecKeyguardClockView( 1170): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1170): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1170): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
,I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1016): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1016): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 10
,I/jxcore-log( 6051): --= Surplus to requirements =--
I/jxcore-log( 6051): 
I/jxcore-log( 6051): ****TEST TOOK:  ms ****
I/jxcore-log( 6051): 
I/jxcore-log( 6051): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6051): 
,D/AndroidRuntime( 6559): 
D/AndroidRuntime( 6559): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6559): CheckJNI is OFF
D/AndroidRuntime( 6559): readGMSProperty: start
D/AndroidRuntime( 6559): readGMSProperty: already setted!!
D/AndroidRuntime( 6559): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6559): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6559): readGMSProperty: end
D/AndroidRuntime( 6559): addProductProperty: start
,E/AffinityControl( 6559): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6559): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1016): START PACKAGE DELETE: observer{772497326}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1016): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 6051:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{e740a0f com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{38bc2050 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1016): Focus left window: 6051
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focused application released
,E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4042): Explicit concurrent mark sweep GC freed 3214(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 750us total 32.021ms
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5928): Explicit concurrent mark sweep GC freed 34(13KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 720us total 42.190ms
W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1886): mOCRHelper is null
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 21:11:31 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3669): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
,I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6571): MountEmulatedStorage()
,E/Zygote  ( 6571): v2
,I/libpersona( 6571): KNOX_SDCARD checking this for 10090
I/libpersona( 6571): KNOX_SDCARD not a persona
,I/SELinux ( 6571): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6571): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6571): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onCreate()
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6571 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3669): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3669): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/TimaKeyStoreProvider( 6571): TimaSignature is unavailable
,D/ActivityThread( 6571): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RegisteredServicesCache( 1438): empty dynamic service
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 34937(2MB) AllocSpace objects, 67(1081KB) LOS objects, 33% free, 23MB/35MB, paused 2.913ms total 204.230ms
,I/art     ( 1016): WaitForGcToComplete blocked for 187.582ms for cause Explicit
,D/elm:15121( 6571): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6571): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6571): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6571): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6571): ElmAgentService : onCreate()
,D/elm:15121( 6571): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6571): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6571): MDMBridge.getInstance()
D/elm:15121( 6571): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3669): KLMSIntentService(): onDestroy()
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
,D/elm:15121( 6571): MDMBridge.getAllLicenseInfoFromSDK()
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6571): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 4936:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 9975(456KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.373ms total 174.198ms
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1016): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1016): result of delete: 1{772497326}
,D/AndroidRuntime( 6559): Shutting down VM
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10338
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=20_task.xml
,D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1016): uID is 10338
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 5627): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5627): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5627): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5627): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF,
,E/Zygote  ( 6589): MountEmulatedStorage()
,E/Zygote  ( 6589): v2
I/libpersona( 6589): KNOX_SDCARD checking this for 10029
I/libpersona( 6589): KNOX_SDCARD not a persona
,I/SELinux ( 6589): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6589 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6589): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6589): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1016): failed to open /acct/uid_10039/pid_4936/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6589): TimaSignature is unavailable,
,D/ActivityThread( 6589): Added TimaKeyStore provider
,I/SA      ( 5709): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5709): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/FeatureConfig( 6589): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1016): Killing 5801:com.wsomacp/u0a23 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6589): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6589): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6607): MountEmulatedStorage()
E/Zygote  ( 6607): v2
I/libpersona( 6607): KNOX_SDCARD checking this for 10039
I/libpersona( 6607): KNOX_SDCARD not a persona
,I/SELinux ( 6607): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6607 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
I/SELinux ( 6607): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6607): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 6589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6607): TimaSignature is unavailable
,W/ResourcesManager( 6589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread( 6607): Added TimaKeyStore provider
,W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6607): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6559): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6589): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10023/pid_5801/cgroup.procs: No such file or directory
,W/ResourcesManager( 6589): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6589): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6589): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6607): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6607): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6607): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6607): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6607): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6607): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6607): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6607): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6607): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6607): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6607): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6607): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6607): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6607): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6607): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,D/NearbySource( 6607): Nearby Source Create!
,D/NearbyContext( 6607): Nearby Context Create!

```
