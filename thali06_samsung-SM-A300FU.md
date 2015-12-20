#### Test 50650278bb431e6_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  291): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6143): 
D/AndroidRuntime( 6143): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6143): CheckJNI is OFF
D/AndroidRuntime( 6143): readGMSProperty: start
D/AndroidRuntime( 6143): readGMSProperty: already setted!!
D/AndroidRuntime( 6143): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6143): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6143): readGMSProperty: end
D/AndroidRuntime( 6143): addProductProperty: start
E/AffinityControl( 6143): AffinityControl: registerfunction enter
D/AndroidRuntime( 6143): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
I/ServiceManager(  318): Waiting for service AtCmdFwd...
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6156): MountEmulatedStorage()
E/Zygote  ( 6156): v2
I/libpersona( 6156): KNOX_SDCARD checking this for 10338
I/libpersona( 6156): KNOX_SDCARD not a persona
I/SELinux ( 6156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6156 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1477
D/AndroidRuntime( 6143): Shutting down VM
I/SELinux ( 6156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6156): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6156): TimaSignature is unavailable
D/ActivityThread( 6156): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1477): updateVisibility : ActivityRecord{4fd39b8 token=android.os.BinderProxy@1871a2f1 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1477): onTrimMemory. Level: 20
I/WebViewFactory( 6156): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6156): Time to load native libraries: 1 ms (timestamps 1398-1399)
I/LibraryLoader( 6156): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6156): Binding Chromium to main looper Looper (main, tid 1) {106ecc79}
I/LibraryLoader( 6156): Expected native library version number "",actual native library version number ""
I/chromium( 6156): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 6143): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 6156): Initializing chromium process, singleProcess=true
,W/art     ( 6156): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6156): ApplicationContext is null in ApplicationStatus
,W/chromium( 6156): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6156): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6156): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6156): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6156): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6156): Local Branch: 
I/Adreno-EGL( 6156): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6156): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6156):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6156): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6156): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6156): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6156): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6156): CordovaWebView is running on device made by: samsung
,W/art     ( 6156): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6156): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{3c5a6cd3 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6156): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 6156): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6156): updateVisibility : ActivityRecord{1ef2477a token=android.os.BinderProxy@aa2319c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6156): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6156): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6156
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101,
,D/SRIB_DCS( 6156): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6156): Initialized EGL, version 1.4
D/OpenGLRenderer( 6156): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6156): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1174): Icon Only,
,D/PanelView( 1174): There is/are notification(s) 
,I/ActivityManager( 1018): Displayed Component not be shown by security: +701ms (total +45s378ms)
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{3c5a6cd3 u0 com.test.thalitest/.MainActivity t20} time:161967
,W/IInputConnectionWrapper( 6156): showStatusIcon on inactive InputConnection
,I/Timeline( 6156): Timeline: Activity_idle id: android.os.BinderProxy@aa2319c time:161969
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1759): getCurrentCandidateView,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,W/BindingManager( 6156): Cannot call determinedVisibility() - never saw a connection for the pid: 6156
,D/SamsungIME( 1759): Dismiss ExpandCandiate
,I/SamsungIME( 1759): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1759): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1759): KeybaordView init() : load resources
,I/SamsungIME( 1759): getCurrentKeyboard
I/SamsungIME( 1759): getTextKeyboard
,D/SamsungIME( 1759): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6156): Set native->JS mode to OnlineEventsBridgeMode
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/jxcore_app_log( 6156): JniHelper::setJavaVM(0xb7635448), pthread_self() = -1212627264
,D/JX-Cordova( 6156): jxcore cordova android initializing
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,W/jxcore-log( 6156): Initializing JXcore engine,
W/jxcore-log( 6156): JXcore engine is ready
,I/art     ( 6156): Background sticky concurrent mark sweep GC freed 5395(493KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 6.060ms total 34.342ms
,W/jxcore-log( 6156): Starting JXcore engine
,E/audit   ( 1836): type=1400 msg=audit(1450653101.661:205): avc:  denied  { ioctl } for  pid=6156 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1836):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1836): type=1300 msg=audit(1450653101.661:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=beb36d58 items=0 ppid=308 ppcomm=main pid=6156 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1836): type=1320 msg=audit(1450653101.661:205): 
,W/jxcore-log( 6156): Platform android
W/jxcore-log( 6156): 
W/jxcore-log( 6156): Process ARCH arm
W/jxcore-log( 6156): 
,I/jxcore-log( 6156): JXcore Cordova bridge is ready!
I/jxcore-log( 6156): 
,W/jxcore-log( 6156): JXcore engine is started
I/Choreographer( 6156): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6156): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6156): Toggling radios to true,
I/jxcore-log( 6156): 
,D/BluetoothAdapter( 6156): enable(),
,D/BluetoothAdapter( 6156): enable(): BT is already enabled..!,
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6156, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6156, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6156, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6156, uid=10338
,I/wpa_supplicant( 1395): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6156): Radios toggled
I/jxcore-log( 6156): 
,I/jxcore-log( 6156): Got Device Bluetooth address: 08:EC:A9:50:75:41,
I/jxcore-log( 6156): 
,I/jxcore-log( 6156): Perf Test app loaded loaded
I/jxcore-log( 6156): 
,I/jxcore-log( 6156): check test folder
I/jxcore-log( 6156): 
,I/jxcore-log( 6156): found test : ./testFindPeers.js
I/jxcore-log( 6156): 
,I/wpa_supplicant( 1395): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1395): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1395): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): InitialState.processMessage what=4
I/wpa_supplicant( 1395): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1395): Cmd 35605 not handled
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1395): reset timer : RESET_TIMER 0,
,I/wpa_supplicant( 1395): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1395): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1395): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 1395): First Scan Start
I/wpa_supplicant( 1395): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1018): No numeric data
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1018): clearTetheredNotification()
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,E/WifiNative-wlan0( 1018): do suspend true
,V/NetworkStats( 1018): performPollLocked() took 6ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1807): Read error: ssl=0xb7b153d8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1807): SSL shutdown failed: ssl=0xb7b153d8: I/O error during system call, Broken pipe
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>,
I/wpa_supplicant( 1395): wlan0: Setting scan request: 0 sec 0 usec
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f9b7c8
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1208371912)
I/jxcore-log( 6156): found test : ./testSendData.js
I/jxcore-log( 6156): 
I/qtaguid ( 1018): Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
E/SMD     (  291): DCD OFF
,I/qtaguid ( 1018): Untagging socket 351
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1654): Starting #8,
,I/Hs20UtilService( 1654): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1208371912) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7f9b7c8
,I/jxcore-log( 6156): found test : ./testSendData2.js,
I/jxcore-log( 6156): 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/jxcore  ( 6156): Error!: unlabeled break must be inside loop or switch
E/jxcore  ( 6156): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"86","_columnNumber":"30","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:86:30"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient","_lineNumber":"82","_columnNumber":"1","_msg":"    at TestFrameworkClient@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:82:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"74","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:74:21"}]
,I/chromium( 6156): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CommandListener(  278): Clearing all IP addresses on wlan0,
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost,
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
V/NetworkStats( 1018): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null,
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
I/Hs20UtilService( 1654): Starting #9
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,I/Hs20UtilService( 1654): Message received 5007
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1321): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1321): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5730): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5730): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5730): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5730): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 5730): noConnectivity : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6231): MountEmulatedStorage()
I/libpersona( 6231): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD not a persona
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6231 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider
,I/MusicStore( 6231): Database version: 120
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6231): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1395): nl80211: Received scan results (9 BSSes),
I/wpa_supplicant( 1395): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1395): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1395): Trying to associate with  'G700'
I/wpa_supplicant( 1395): Re-associate with C0.AA.48
I/wpa_supplicant( 1395): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/wpa_supplicant( 1395): Cmd 35605 not handled,
I/wpa_supplicant( 1395): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1395): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,I/wpa_supplicant( 1395): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1395): Associated with C0.AA.48
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1395): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1395): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true,
,E/Tethering( 1018): No numeric data
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
I/wpa_supplicant( 1395): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/HotspotTile( 1174): updateTetherState():false, false
D/SecContentProvider2( 1018): mCursor = null
I/wpa_supplicant( 1395): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/wpa_supplicant( 1395): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
W/ActivityThread( 6231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/wpa_supplicant( 1395): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1395): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1395): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,W/System  ( 6231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@28703ab6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6231): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6231): GMSCore installation verified
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true,
I/wpa_supplicant( 1395): Blacklist: Clear (temp) 
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,V/NetworkStats( 1018): performPollLocked() took 9ms
D/SecContentProvider2( 1018): mCursor = null
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,I/ConfigStore( 6231): Config Database version: 1
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiNative-wlan0( 1018): do suspend false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 6231): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6258): MountEmulatedStorage()
,I/libpersona( 6258): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6258): v2
I/libpersona( 6258): KNOX_SDCARD not a persona
I/SELinux ( 6258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6258 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  308): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 25.352ms
,I/GHttpClientFactory( 6231): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 666us total 20.662ms
,D/TimaKeyStoreProvider( 6258): TimaSignature is unavailable
,D/ActivityThread( 6258): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6231): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 19.366ms
,E/dhcpcd  ( 6275): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6275): version 5.5.6 starting
,E/dhcpcd  ( 6275): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/ActivityManager( 1018): Killing 5659:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 6275): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6275): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6275): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6275): bssid match
I/dhcpcd  ( 6275): wlan0: rebinding lease of 192.168.1.132
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6284 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4184:com.sec.spp.push/u0a32 (adj 15): empty #31
E/Zygote  ( 6284): MountEmulatedStorage()
E/Zygote  ( 6284): v2
I/libpersona( 6284): KNOX_SDCARD checking this for 1000
I/libpersona( 6284): KNOX_SDCARD not a persona
,I/SELinux ( 6284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6284): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6284): TimaSignature is unavailable
,D/ActivityThread( 6284): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6284): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5659/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4184/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6284): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6284): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6284): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6299): MountEmulatedStorage()
,E/Zygote  ( 6299): v2
I/libpersona( 6299): KNOX_SDCARD checking this for 10008
I/libpersona( 6299): KNOX_SDCARD not a persona
,I/SELinux ( 6299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6299): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6299 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5222:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6299): TimaSignature is unavailable
,D/ActivityThread( 6299): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5712:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:11:45 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onCreate()
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3684): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3684): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3684): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,E/Zygote  ( 6315): MountEmulatedStorage()
E/Zygote  ( 6315): v2
I/libpersona( 6315): KNOX_SDCARD checking this for 10031
I/libpersona( 6315): KNOX_SDCARD not a persona
,I/SELinux ( 6315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/KLMS-2.5.123: ( 3684): StateImplV2(): networkChangeListener().END
,I/SELinux ( 6315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6315 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6315): TimaSignature is unavailable
,D/ActivityThread( 6315): Added TimaKeyStore provider
,I/SO_AGENT( 6315): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5775): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5913): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5913): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5913): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5222/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5712/cgroup.procs: No such file or directory
,I/SA      ( 5913): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5775): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5775): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5775): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5775): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5913): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5913): [OR] == isSIMCardReady false ==
,I/SA      ( 5913): [SCU] == networkStateCheck == false
,I/SA      ( 5913): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5309:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/DownloadManager( 1221): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1559): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1627): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1559): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1559): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1559): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1559): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1559): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1559): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6332): MountEmulatedStorage()
,E/Zygote  ( 6332): v2
I/libpersona( 6332): KNOX_SDCARD checking this for 10121
I/libpersona( 6332): KNOX_SDCARD not a persona
,I/SELinux ( 6332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6332 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6332): TimaSignature is unavailable
D/ActivityThread( 6332): Added TimaKeyStore provider
,W/ResourcesManager( 6332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6332): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6332): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5309/cgroup.procs: No such file or directory
,D/QuickConnect( 6332): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6332): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6332): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Watchdog( 1018): !@Sync 5
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6347): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6347 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 6347): v2
I/libpersona( 6347): KNOX_SDCARD checking this for 10141
I/libpersona( 6347): KNOX_SDCARD not a persona
I/SELinux ( 6347): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5739:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6347): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6347): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6347): TimaSignature is unavailable
,D/ActivityThread( 6347): Added TimaKeyStore provider
,W/ResourcesManager( 6347): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6347): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6347): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6347): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6275): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5739/cgroup.procs: No such file or directory
,D/BadgeProvider( 5866): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5866): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5866): sendNotify, [notify] : null
D/BadgeProvider( 5866): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5866): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5866): update, [UpdateCount] : 1
,D/Launcher.Model( 1477): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6275): wlan0: leased 192.168.1.132 for 86400 seconds
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6373): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6373): v2
I/libpersona( 6373): KNOX_SDCARD checking this for 1000
,I/libpersona( 6373): KNOX_SDCARD not a persona
,I/SELinux ( 6373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6373): TimaSignature is unavailable,
,D/ActivityThread( 6373): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SecurityLogAgent( 6373): KnoxConfiguration : Current State = 1,
D/SecurityLogAgent( 6373): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6373): StateMachine : Current State = 1
,D/SecurityLogAgent( 6373): StateMachine : Changed Current State = 1
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 57133(3MB) AllocSpace objects, 9(196KB) LOS objects, 33% free, 23MB/35MB, paused 3.371ms total 193.145ms,
,I/ActivityManager( 1018): Killing 5324:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2044): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2044): num queued entries: 0
I/iu.UploadsManager( 2044): num updated entries: 0
I/iu.SyncManager( 2044): NEXT; no task
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2044): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5146): connection state changed from CONNECTED to DISCONNECTED
,E/Zygote  ( 6410): MountEmulatedStorage(),
I/libpersona( 6410): KNOX_SDCARD checking this for 10032
,E/Zygote  ( 6410): v2
I/libpersona( 6410): KNOX_SDCARD not a persona
E/WifiNative-wlan0( 1018): do suspend true
I/SELinux ( 6410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6410): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6410 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5793:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6410): TimaSignature is unavailable
,D/ActivityThread( 6410): Added TimaKeyStore provider
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1018): Failed to clear dns cache for: com.samsung.android.provider.shootingmodeprovider
,E/ConnectivityService( 1018): updateNetworkInfo()
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1456): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,E/SPPClientService( 6410): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6410): [SystemStateMoniter] Current Time : 168803
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
,E/SPPClientService( 6410): [SystemStateMoniter] No Connect : true
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,E/SPPClientService( 6410): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6410): [PushClientApplication] Push log off : This is Ship build version
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/SPPClientService( 6410): PushLog.txt file is not deleted.
D/SPPClientService( 6410): PushLog.txt file is not deleted.
D/SPPClientService( 6410): ============PushLog. stop!
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,E/Zygote  ( 6432): MountEmulatedStorage(),
I/libpersona( 6432): KNOX_SDCARD checking this for 10110
E/Zygote  ( 6432): v2
I/libpersona( 6432): KNOX_SDCARD not a persona
,I/SELinux ( 6432): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/SELinux ( 6432): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6432 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6432): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5815:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_5324/cgroup.procs: No such file or directory
,E/SPPClientService( 6410): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6432): TimaSignature is unavailable
,D/ActivityThread( 6432): Added TimaKeyStore provider
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5793/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5815/cgroup.procs: No such file or directory
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:11:46 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450653106931], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450653106910]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/GAv4    ( 6432): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6432):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6432):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6432): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6432): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6432): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6432): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6432): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6432): Time to load native libraries: 1 ms (timestamps 9186-9187)
I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6432): Binding Chromium to main looper Looper (main, tid 1) {366120f5}
,I/LibraryLoader( 6432): Expected native library version number "",actual native library version number ""
,I/chromium( 6432): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,E/SMD     (  291): DCD OFF
,I/BrowserStartupController( 6432): Initializing chromium process, singleProcess=true
,W/art     ( 6432): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6432): ApplicationContext is null in ApplicationStatus
,W/chromium( 6432): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6432): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6432): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6432): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6432): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6432): Local Branch: 
I/Adreno-EGL( 6432): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6432): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6432):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6432): Starting up...
,W/AudioManagerAndroid( 6432): Requires BLUETOOTH permission
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 6488): MountEmulatedStorage(),
I/libpersona( 6488): KNOX_SDCARD checking this for 10077
E/Zygote  ( 6488): v2
I/libpersona( 6488): KNOX_SDCARD not a persona
I/SELinux ( 6488): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6488): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6488 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 6488): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 3513:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6488): TimaSignature is unavailable
,D/ActivityThread( 6488): Added TimaKeyStore provider
,I/NetworkMonitor( 6231): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_3513/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6045): notifyNetworkActivated
,W/ContextImpl( 6045): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6045): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/InitializeManagerStateMachine( 6045): execute::IDLE:EXECUTE
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/InitializeManagerStateMachine( 6045): exit::IDLE
D/InitializeManagerStateMachine( 6045): entry::NETWORK_CHECK
,I/Hs20UtilService( 1654): Starting #10
,I/Hs20UtilService( 1654): Message received 5007
D/InitializeManagerStateMachine( 6045): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6045): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6045): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6045): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6045): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6045): entry::SUCCESS
D/hcjo    ( 6045): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 6045): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6045): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 6045): exit::SUCCESS
D/InitializeManagerStateMachine( 6045): entry::IDLE
,I/ActivityManager( 1018): Killing 5697:com.android.mms/u0a41 (adj 15): empty #31
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1654): Starting #11
,I/Hs20UtilService( 1654): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/CountryDetector( 1018): No listener is left
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1654): Starting #12
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1321): DMSUtil.isNetworkConnected - flag-null, state-null,
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
I/Hs20UtilService( 1654): Message received 5007
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1321): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1654): Starting #13
,I/Hs20UtilService( 1654): Message received 5007
,D/NearbySettings( 1321): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1321): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5730): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5730): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5730): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5730): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6231): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5697/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6284): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6284): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5775): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5775): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5775): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5775): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6299): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6299): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:11:47 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3684): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3684): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/GCM     ( 1807): Connected
,I/KLMS-2.5.123: ( 3684): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3684): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3684): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3684): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3684): StateImplV2(): networkChangeListener().END
,D/GCM     ( 1807): Message class com.google.f.a.a.p
,I/DBG_POLICYDM( 5775): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5775): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5775): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5775): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5913): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5913): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5913): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5775): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5913): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5913): [OR] == isSIMCardReady false ==
,I/SA      ( 5913): [SCU] == networkStateCheck == true
,I/SA      ( 5913): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5913): isChinaCountryCode : false
I/SA      ( 5913): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5913): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5775): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 5913): [OR] GetMyCountryZoneTask
,I/SA      ( 5913): [OR] onReceive END
I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/SA      ( 5913): [SRS] prepareGetMyCountryZone
I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5775): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,V/DownloadManager( 1221): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1559): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5775): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
D/daemonapp( 1627): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/SecContentProvider2( 1018): mCursor = null
D/accuweather( 1559): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1559): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1559): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1559): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5913): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5913): [SSP] query invoked
,I/DBG_POLICYDM( 5775): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5775): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/accuweather( 1559): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1559): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6332): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6332): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6332): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 5913): [TPMU] GetMccFromDB : null
I/SA      ( 5913): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5913): [TPM] isNoProxy(default) : true
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/File    ( 5913): fail readDirectory() errno=2
,D/SecurityLogAgent( 6373): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6373): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6373): StateMachine : Current State = 1
,D/SecurityLogAgent( 6373): StateMachine : Changed Current State = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1018): Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,I/qtaguid ( 1018): Untagging socket 351
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Sun, 20 Dec 2015 23:11:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450653108201], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450653108183]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
I/iu.Environment( 2044): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2044): num queued entries: 0
,I/iu.UploadsManager( 2044): num updated entries: 0
,I/iu.SyncManager( 2044): NEXT; no task
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2044): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2044): Loading module com.google.android.gms.kids from APK com.google.android.gms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6410): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6410): [SystemStateMoniter] Current Time : 170250
,I/System.out( 5146): (HTTPLog)-Static: isSBSettingEnabled false
,E/SPPClientService( 6410): [SystemStateMoniter] No Connect : false
,I/System.out( 5146): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 5146): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/hcjo    ( 6045): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 6045): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6045): exit::IDLE
D/InitializeManagerStateMachine( 6045): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6045): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6045): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6045): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6045): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6045): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6045): entry::SUCCESS
D/hcjo    ( 6045): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 6045): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6045): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6045): exit::SUCCESS
D/InitializeManagerStateMachine( 6045): entry::IDLE
,I/Babel   ( 5146): connection state changed from DISCONNECTED to CONNECTED
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 5.
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2044): [AccountUtils] Account not ready
W/Kids    ( 2044): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2044): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2044): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2044): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2044): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2044): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2044): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2044): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2044): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2044): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2044): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2044): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5913): [RC New] Execute method=[GET] start
I/SA      ( 5913): [RC New] Security=[true]
I/System.out( 5913): Thread-1005(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5913): Thread-1005(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5913): Thread-1005(ApacheHTTPLog):isShipBuild true
I/System.out( 5913): Thread-1005(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5913): Thread-1005(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10036
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6156): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 6156): BLE supported!!
I/jxcore-log( 6156): 
I/SA      ( 5913): [RC New] [v2liruge] api execute + 659
I/SA      ( 5913): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5913): AsyncTask #1 calls detatch()
I/SA      ( 5913): [ODM] saveOpenData( GEO_IP, PL )
I/SA      ( 5913): [OCP] update openData : PL
I/SA      ( 5913): [TPMU] getNetworkMcc : 
I/SA      ( 5913): [SCU] saveMccToPreferece Start
I/SA      ( 5913): [SCU] RegionMCC : 260
I/SA      ( 5913): [SSP] query invoked
I/SA      ( 5913): [TPMU] GetMccFromDB : null
I/SA      ( 5913): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5913): [SCU] saveMccToPreferece End
I/SA      ( 5913): [RC New] executeRequest [v2liruge] end. 723
I/SA      ( 5913): [RC New] Execute end
I/SA      ( 5913): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5913): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6275): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1807): Vacuum at: now=1450653110213 tag=VacuumService
,E/SMD     (  291): DCD OFF
,I/GoogleURLConnFactory( 1807): Using platform SSLCertificateSocketFactory
,W/Uploader( 1807): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1807): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1807): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1807): (HTTPLog)-Thread-222-249375969: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1807): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/qtaguid ( 1807): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6231): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6231): Stop autocaching.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6549): MountEmulatedStorage()
,E/Zygote  ( 6549): v2
I/libpersona( 6549): KNOX_SDCARD checking this for 10011
I/libpersona( 6549): KNOX_SDCARD not a persona
,I/SELinux ( 6549): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6549): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6549 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6549): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6549): TimaSignature is unavailable
,D/ActivityThread( 6549): Added TimaKeyStore provider
,W/ResourcesManager( 6549): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6549): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/Uploader( 1807): No account for auth token provided
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,I/MultiDex( 6549): VM with version 2.1.0 has multidex support
,I/MultiDex( 6549): install
I/MultiDex( 6549): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6549): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6549): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6549): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@140f5200: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6549): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
D/GCM     ( 1807): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1807): No account for auth token provided
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,D/AuthorizationBluetoothService( 1807): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2044): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6549): callingUid 10011, callindPid: 6549
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
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1807): No account for auth token provided
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
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
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2044): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Uploader( 1807):  no longer exists, so no auth token.
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,W/Uploader( 1807): No account for auth token provided
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 42851(2MB) AllocSpace objects, 6(100KB) LOS objects, 33% free, 23MB/35MB, paused 2.999ms total 170.476ms
,E/MDM     ( 1740): [192] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6231): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/art     ( 1807): Background sticky concurrent mark sweep GC freed 41317(2MB) AllocSpace objects, 41(2MB) LOS objects, 35% free, 8MB/12MB, paused 11.124ms total 56.854ms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true,
,E/Uploader( 1807): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1807): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1807): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1807): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1807): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1807): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1807): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1807): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1807): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1807): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1807): 	,at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1807): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1807): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1807): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1807): Tagging socket 53 with tag 120100000000{4609,0} for uid -1, pid: 1807, getuid(): 10011
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1807): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 173283
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3475)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5730): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5730): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5730): [GetString-S]
,I/ReactiveServiceManager( 5730): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5730): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5730): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5730): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5730): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5730): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5730): [ensureRegistration] - No Samsung account
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/dhcpcd  ( 6275): wlan0: sending IPv6 Router Solicitation,
,D/GCM     ( 1807): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1807): Message class com.google.f.a.a.p
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 1018): Killing 5849:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5849/cgroup.procs: No such file or directory
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6045): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6045): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6045): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6045): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6045): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6045): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6045): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6045): entry::IDLE
,I/dhcpcd  ( 6275): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6275): wlan0: no IPv6 Routers available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6045): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6045): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6045): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6045): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6045): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6045): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6045): entry::IDLE
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  291): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{7ad8ff0 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Giving up after 6 failures.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/Watchdog( 1018): !@Sync 7,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282026, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...,
I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1018): waitForAlarm result :4
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true,
D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 313481, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  291): DCD OFF
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,W/GLSActivity( 1807): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1807): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1807): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1807): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1807): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1807): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1807): 	at android.os.Binder.execTransact(Binder.java:461)
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5395): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5395): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5395): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5395): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5395): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5395): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5395): 	at android.os.Binder.execTransact(Binder.java:461)
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5395): Ignoring header User-Agent because its value was null.
,I/System.out( 5395): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5395): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5395): (HTTPLog)-Static: isShipBuild true
I/System.out( 5395): (HTTPLog)-Thread-913-748370736: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5395): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5395): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 12
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 404730, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 13
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1,
D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 14
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 15
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/bootchecker(  313): bootchecker wake up!!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF,
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  318): Waiting for service AtCmdFwd...,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***,
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 57693(4MB) AllocSpace objects, 150(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.443ms total 159.277ms
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 529578, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  318): Waiting for service AtCmdFwd...
,E/SMD     (  291): DCD OFF
,W/Atfwd_Sendcmd(  318): AtCmdFwd service not published, waiting... retryCnt : 5
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 18
,I/Atfwd_Sendcmd(  318): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  318): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,I/Atfwd_Daemon(  318): Stop the daemon....,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 19
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 20
,E/SMD     (  291): DCD OFF,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 21
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 22,
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 23,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 24,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 680s ago
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/Watchdog( 1018): !@Sync 25
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 779315, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/Finsky  ( 5395): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,E/Watchdog( 1018): !@Sync 26
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5395): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2044): Aggregate from 1450651386312 (log), 1450651386312 (data)
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Finsky  ( 5395): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms,
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1807): Explicit concurrent mark sweep GC freed 44564(2MB) AllocSpace objects, 30(1176KB) LOS objects, 40% free, 7MB/13MB, paused 1.238ms total 65.177ms
,W/Finsky  ( 5395): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 5395): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5395): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5395): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1740): client connected with version: 7571000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 27
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 765s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 48425(3MB) AllocSpace objects, 138(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.467ms total 162.866ms
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 28,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 29,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5395): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5395): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5395): [1] 5.onFinished: Giving up after 6 failures.
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 855s ago,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 31
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 32
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 33
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 950s ago,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 34
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 35
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate,
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1807): Message class com.google.f.a.a.i,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 36
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 37
,I/PowerManagerService( 1018): [PWL] Off : 1050s ago
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1450654153891
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1450654154253
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 40
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 1156s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 41
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,E/Watchdog( 1018): !@Sync 42
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6073): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6073): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6073): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6073): Soft error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6073): Sync error
E/BooksSync( 6073): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6073): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6073): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1278106, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 43,
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1266s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 45
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 46
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 47
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 48
,I/PowerManagerService( 1018): [PWL] Off : 1381s ago,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 49
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  291): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 50
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 51
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 52
,I/PowerManagerService( 1018): [PWL] Off : 1501s ago
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 53
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 54
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 55
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 56
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 1626s ago
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 57,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 58
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/Watchdog( 1018): !@Sync 59
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 60
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/PowerManagerService( 1018): [PWL] Off : 1756s ago,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 61
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 62
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 63,
,E/SMD     (  291): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 64
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF,
,E/SMD     (  291): DCD OFF
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  291): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 65,
,I/PowerManagerService( 1018): [PWL] Off : 1891s ago
,E/SMD     (  291): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  291): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  291): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
I/ActivityManager( 1018): Killing 6373:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1806s
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
I/ActivityManager( 1018): Killing 6347:com.android.email/u0a141 (adj 15): empty for 1806s
,I/ActivityManager( 1018): Killing 6332:com.samsung.android.sconnect/u0a121 (adj 15): empty for 1806s
D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/ActivityManager( 1018): Killing 5913:com.osp.app.signin/u0a36 (adj 15): empty for 1806s
,I/ActivityManager( 1018): Killing 5775:com.policydm/1000 (adj 15): empty for 1806s
D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,I/ActivityManager( 1018): Killing 6315:com.sec.android.soagent/u0a31 (adj 15): empty for 1806s
I/ActivityManager( 1018): Killing 6299:com.sec.android.fotaclient/u0a8 (adj 15): empty for 1806s
,I/ActivityManager( 1018): Killing 6284:com.sec.android.diagmonagent/1000 (adj 15): empty for 1806s
I/ActivityManager( 1018): Killing 6258:com.sec.android.cloudagent/u0a1 (adj 15): empty for 1806s
,I/ActivityManager( 1018): Killing 5730:com.sec.pcw.device/1000 (adj 15): empty for 1806s
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager( 1018): Killing 5866:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1807s
,I/ActivityManager( 1018): Killing 5639:com.android.defcontainer/u0a3 (adj 15): empty for 1883s
I/ActivityManager( 1018): Killing 6028:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1892s
,I/ActivityManager( 1018): Killing 5015:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1892s
,I/ActivityManager( 1018): Killing 5973:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1892s
,I/ActivityManager( 1018): Killing 5951:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1893s
,I/ActivityManager( 1018): Killing 5931:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1893s
,I/ActivityManager( 1018): Killing 5897:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1893s
,I/ActivityManager( 1018): Killing 5882:com.wsomacp/u0a23 (adj 15): empty for 1893s
,I/ProcessStatsService( 1018): Prepared write state in 12ms
,V/NetworkStats( 1018): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1807): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1807): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1807): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1807): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1807): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1807): Message class com.google.f.a.a.i
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-20-03-06-33.bin
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6373/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10141/pid_6347/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_5973/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_6299/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_6258/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_5639/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_6315/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6284/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10121/pid_6332/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_6028/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5775/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5730/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5951/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5897/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5866/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_5015/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5882/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10036/pid_5913/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5931/cgroup.procs: No such file or directory
,E/SQLiteLog( 1807): (10) POSIX Error : 11 SQLite Error : 3850
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2627): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2627): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  291): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7355): 
D/AndroidRuntime( 7355): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7355): CheckJNI is OFF
D/AndroidRuntime( 7355): readGMSProperty: start
D/AndroidRuntime( 7355): readGMSProperty: already setted!!
D/AndroidRuntime( 7355): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7355): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7355): readGMSProperty: end
D/AndroidRuntime( 7355): addProductProperty: start
E/AffinityControl( 7355): AffinityControl: registerfunction enter
D/AndroidRuntime( 7355): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{407694653}
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
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 6156:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{3d1ee982 com.example.hello/10346} due to missing metadata
V/AlarmManager( 1018): waitForAlarm result :8
I/WindowState( 1018): WIN DEATH: Window{1914afed u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1018): Focus left window: 6156
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{3c5a6cd3 u0 com.test.thalitest/.MainActivity t20}
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1018): Focused application released
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
W/ActivityManager( 1018): Spurious death for ProcessRecord{337c932 6156:com.test.thalitest/u0a338}, curProc for 6156: null
I/art     ( 4000): Explicit concurrent mark sweep GC freed 3214(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 956us total 23.997ms
E/SamsungIME( 1759): mOCRHelper is null
W/GeofencerStateMachine( 1740): Ignoring removeGeofence because network location is disabled.
E/SMD     (  291): DCD OFF
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1456): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Dec 21 00:42:00 GMT+01:00 2015
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3684): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7367): MountEmulatedStorage()
I/libpersona( 7367): KNOX_SDCARD checking this for 10090
E/Zygote  ( 7367): v2
I/libpersona( 7367): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7367 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7367): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  308): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 754us total 20.442ms
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onCreate()
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 17.258ms
D/TimaKeyStoreProvider( 7367): TimaSignature is unavailable
I/KLMS-2.5.123: ( 3684): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ActivityThread( 7367): Added TimaKeyStore provider
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
I/KLMS-2.5.123: ( 3684): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/SecContentProvider2( 1018): mCursor = null
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 18.472ms
D/RegisteredServicesCache( 1440): empty dynamic service
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
I/art     ( 1018): Explicit concurrent mark sweep GC freed 45158(4MB) AllocSpace objects, 133(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.840ms total 208.460ms
I/art     ( 1018): WaitForGcToComplete blocked for 198.458ms for cause Explicit
D/elm:15121( 7367): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7367): ELMEngine.ELMEngine( context ).
D/elm:15121( 7367): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7367): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7367): ElmAgentService : onCreate()
D/elm:15121( 7367): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 7367): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7367): MDMBridge.getInstance()
D/elm:15121( 7367): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7367): MDMBridge.getAllLicenseInfoFromSDK()
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 7367): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 6432:com.google.android.apps.magazines/u0a110 (adj 15): empty for 1812s
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3684): KLMSIntentService(): onDestroy()
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     ( 1018): Explicit concurrent mark sweep GC freed 16474(771KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.663ms total 213.237ms
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_6432/cgroup.procs: No such file or directory
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7385): MountEmulatedStorage()
E/Zygote  ( 7385): v2
I/libpersona( 7385): KNOX_SDCARD checking this for 1000
I/libpersona( 7385): KNOX_SDCARD not a persona
I/SELinux ( 7385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7385 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 7385): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 1018): delete codoeFile: 
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
D/PackageManager( 1018): result of delete: 1{407694653}
D/AndroidRuntime( 7355): Shutting down VM
D/TimaKeyStoreProvider( 7385): TimaSignature is unavailable
D/ActivityThread( 7385): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 7385): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7385): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7385): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7385): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7385): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7385): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7385): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7400): MountEmulatedStorage()
E/Zygote  ( 7400): v2
I/libpersona( 7400): KNOX_SDCARD checking this for 10029
I/libpersona( 7400): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7400 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 6488:com.android.chrome/u0a77 (adj 15): empty for 1812s
I/SELinux ( 7400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7400): TimaSignature is unavailable
D/ActivityThread( 7400): Added TimaKeyStore provider
I/FeatureConfig( 7400): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7417): MountEmulatedStorage()
E/Zygote  ( 7417): v2
I/libpersona( 7417): KNOX_SDCARD checking this for 10036
I/libpersona( 7417): KNOX_SDCARD not a persona
I/SELinux ( 7417): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7417): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7417): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7400): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7417 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 6002:com.google.android.apps.plus/u0a117 (adj 15): empty for 1812s
W/ResourcesManager( 7400): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7417): TimaSignature is unavailable
D/ActivityThread( 7417): Added TimaKeyStore provider
W/ResourcesManager( 7400): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/art     ( 7355): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 7400): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7417): [SSP] onCreated
W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_6488/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10117/pid_6002/cgroup.procs: No such file or directory
W/ResourcesManager( 7400): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7417): [TPM] There is no property file
I/SA      ( 7417): [SCU] isHaveSA() - false
I/SA      ( 7417): [TPM] getModelProperty : null
I/SA      ( 7417): [TPM] getCSCProperty : null
W/ResourcesManager( 7400): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7417): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7417): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7417): [DM] TFT FEATURE: false
I/SA      ( 7417): [DM] init START
I/SA      ( 7417): [DM] This device is not a Vodafone
W/ResourceType( 7417): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourcesManager( 7400): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourceType( 7417): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourcesManager( 7400): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 7417): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7417): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7417): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7417): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/ResourcesManager( 7400): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7400): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SA      ( 7417): [SCU] isHaveSA() - false
I/SA      ( 7417): support phone number id : false
I/SA      ( 7417): [DM] Supports Ref Jpn : true
I/SA      ( 7417): [DM] init END
I/SA      ( 7417): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7417): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 6231:com.google.android.music:main/u0a108 (adj 15): empty for 1810s
W/GalaxyFinderApplication( 7400): system/finder_cp/cpdata.xml file not found
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7439): MountEmulatedStorage()
E/Zygote  ( 7439): v2
I/libpersona( 7439): KNOX_SDCARD checking this for 10039
I/libpersona( 7439): KNOX_SDCARD not a persona
I/SELinux ( 7439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7439): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7439 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7439): TimaSignature is unavailable
D/ActivityThread( 7439): Added TimaKeyStore provider
W/ResourcesManager( 7439): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.

```
