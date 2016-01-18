#### Test 5615109370bee58_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/AndroidRuntime( 6093): 
D/AndroidRuntime( 6093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6093): CheckJNI is OFF
D/AndroidRuntime( 6093): readGMSProperty: start
D/AndroidRuntime( 6093): readGMSProperty: already setted!!
D/AndroidRuntime( 6093): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6093): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6093): readGMSProperty: end
D/AndroidRuntime( 6093): addProductProperty: start
E/AffinityControl( 6093): AffinityControl: registerfunction enter
D/AndroidRuntime( 6093): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6105): MountEmulatedStorage()
E/Zygote  ( 6105): v2
I/libpersona( 6105): KNOX_SDCARD checking this for 10338
I/libpersona( 6105): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6105 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1479
D/AndroidRuntime( 6093): Shutting down VM
I/SELinux ( 6105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6105): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6105): TimaSignature is unavailable
D/ActivityThread( 6105): Added TimaKeyStore provider
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{2699c366 token=android.os.BinderProxy@1bc67d07 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/ServiceManager(  317): Waiting for service AtCmdFwd...
I/WebViewFactory( 6105): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6105): Time to load native libraries: 2 ms (timestamps 2394-2396)
I/LibraryLoader( 6105): Expected native library version number "",actual native library version number ""
W/art     ( 6093): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6105): Binding Chromium to main looper Looper (main, tid 1) {1c0a3fcf}
,I/LibraryLoader( 6105): Expected native library version number "",actual native library version number ""
,I/chromium( 6105): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6105): Initializing chromium process, singleProcess=true
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6105): ApplicationContext is null in ApplicationStatus
,W/chromium( 6105): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6105): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6105): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6105): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6105): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6105): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6105): Local Branch: 
I/Adreno-EGL( 6105): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6105): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6105):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6105): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6105): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6105): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6105): CordovaWebView is running on device made by: samsung
W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6105): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{3dec62a u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6105): Render dirty regions requested: true
,D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
,W/chromium( 6105): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6105): updateVisibility : ActivityRecord{28dbce78 token=android.os.BinderProxy@184f74ea {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6105): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6105): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1017): Focus entered window: 6105,
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6105): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6105): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6105): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
D/OpenGLRenderer( 6105): Enabling debug mode 0
,D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6105): showStatusIcon on inactive InputConnection
,I/Timeline( 6105): Timeline: Activity_idle id: android.os.BinderProxy@184f74ea time:162923
,I/ActivityManager( 1017): Displayed Component not be shown by security: +682ms (total +46s853ms)
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{3dec62a u0 com.test.thalitest/.MainActivity t20} time:162927
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1873): getCurrentCandidateView
,D/SamsungIME( 1873): Dismiss ExpandCandiate
,I/SamsungIME( 1873): getDebugLevel  : 0x4f4c
,W/BindingManager( 6105): Cannot call determinedVisibility() - never saw a connection for the pid: 6105
,I/SamsungIME( 1873): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1873): KeybaordView init() : load resources
,I/SamsungIME( 1873): getCurrentKeyboard
I/SamsungIME( 1873): getTextKeyboard
,D/SamsungIME( 1873): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6105): Set native->JS mode to OnlineEventsBridgeMode
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,D/jxcore_app_log( 6105): JniHelper::setJavaVM(0xb8c37448), pthread_self() = -1189550168
,D/JX-Cordova( 6105): jxcore cordova android initializing
,W/jxcore-log( 6105): Initializing JXcore engine,
W/jxcore-log( 6105): JXcore engine is ready
,W/jxcore-log( 6105): Starting JXcore engine,
,E/audit   ( 1871): type=1400 msg=audit(1453126637.245:205): avc:  denied  { ioctl } for  pid=6105 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1871):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1871): type=1300 msg=audit(1453126637.245:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bec63d58 items=0 ppid=307 ppcomm=main pid=6105 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1871): type=1320 msg=audit(1453126637.245:205): 
,W/jxcore-log( 6105): Platform android
W/jxcore-log( 6105): 
W/jxcore-log( 6105): Process ARCH arm
W/jxcore-log( 6105): 
,I/jxcore-log( 6105): JXcore Cordova bridge is ready!
I/jxcore-log( 6105): 
,W/jxcore-log( 6105): JXcore engine is started
I/Choreographer( 6105): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6105): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6105): Toggling radios to true
I/jxcore-log( 6105): 
,D/BluetoothAdapter( 6105): enable()
,D/BluetoothAdapter( 6105): enable(): BT is already enabled..!
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6105, uid=10338
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6105, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6105, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6105, uid=10338
,I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6105): Radios toggled
I/jxcore-log( 6105): 
,I/jxcore-log( 6105): My device name is: samsung-SM-A300FU
I/jxcore-log( 6105): 
,I/wpa_supplicant( 1383): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1383): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1383): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030,
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false,
I/wpa_supplicant( 1383): wlan0: State: DISCONNECTED -> DISCONNECTED
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1383): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1383): wlan0: Setting scan request: 0 sec 0 usec
E/wpa_supplicant( 1383): Cmd 35605 not handled
,I/wpa_supplicant( 1383): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1383): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1383): First Scan Start
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1383): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
E/WifiNative-wlan0( 1017): do suspend true
,D/HotspotTile( 1176): updateTetherState():false, false
,V/NetworkStats( 1017): performPollLocked() took 7ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1661): Read error: ssl=0xb9057120: I/O error during system call, Connection timed out
,E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1383): wlan0: Setting scan request: 0 sec 0 usec,
V/NativeCrypto( 1661): SSL shutdown failed: ssl=0xb9057120: I/O error during system call, Broken pipe
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 335 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75447c8
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received,
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1219213176)
E/WifiNative-wlan0( 1017): do suspend true
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/qtaguid ( 1017): Untagging socket 335
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #8
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
I/Hs20UtilService( 1682): Message received 5007
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/TelephonyNetworkFactory( 1455): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1455): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1219213176) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75447c8
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 5ms
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #9
,I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,D/PhoneApp( 1455): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1455): FileWriteThread : threadType = 3
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,I/PCWCLIENTTRACE_PushUtil( 5676): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5676): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5676): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5676): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5676): noConnectivity : true
,E/Zygote  ( 6179): MountEmulatedStorage()
,E/Zygote  ( 6179): v2
I/libpersona( 6179): KNOX_SDCARD checking this for 10108
I/libpersona( 6179): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6179 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6179): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6179): TimaSignature is unavailable
,D/ActivityThread( 6179): Added TimaKeyStore provider
,I/MusicStore( 6179): Database version: 120,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6179): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,I/wpa_supplicant( 1383): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 1383): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1383): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1383): Trying to associate with  'G700'
I/wpa_supplicant( 1383): Re-associate with C0.AA.48
,I/wpa_supplicant( 1383): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,W/ResourcesManager( 6179): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6179): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6179): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/wpa_supplicant( 1383): Cmd 35605 not handled,
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
W/ActivityThread( 6179): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
I/wpa_supplicant( 1383): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1383): Associated with C0.AA.48
I/wpa_supplicant( 1383): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1383): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030,
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false,
W/System  ( 6179): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c47b514: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/ProviderInstaller( 6179): Installed default security provider GmsCore_OpenSSL,
D/AndroidMusic( 6179): GMSCore installation verified
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true,
D/Tethering( 1017): interfaceStatusChanged wlan0, true
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,I/wpa_supplicant( 1383): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1383): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1383): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1383): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1383): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1383): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 1383): Blacklist: Clear (temp) 
,I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true,
D/Tethering( 1017): interfaceStatusChanged wlan0, true
,E/Tethering( 1017): No numeric data
D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 5ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
I/ConfigStore( 6179): Config Database version: 1
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,E/WifiNative-wlan0( 1017): do suspend false
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,I/MediaRouter( 6179): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6206): MountEmulatedStorage(),
I/libpersona( 6206): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6206): v2
I/libpersona( 6206): KNOX_SDCARD not a persona
,I/SELinux ( 6206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6206 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6206): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  307): Explicit concurrent mark sweep GC freed 8706(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 28.136ms
,D/TimaKeyStoreProvider( 6206): TimaSignature is unavailable
,D/ActivityThread( 6206): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 16.681ms
,I/GHttpClientFactory( 6179): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6179): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.566ms
,I/ActivityManager( 1017): Killing 5603:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/dhcpcd  ( 6224): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6224): version 5.5.6 starting
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 6224): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6228): MountEmulatedStorage()
,E/Zygote  ( 6228): v2
I/libpersona( 6228): KNOX_SDCARD checking this for 1000,
I/libpersona( 6228): KNOX_SDCARD not a persona
,I/SELinux ( 6228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6228): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6228 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
I/ActivityManager( 1017): Killing 4172:com.sec.spp.push/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6228): TimaSignature is unavailable
,D/ActivityThread( 6228): Added TimaKeyStore provider
,I/dhcpcd  ( 6224): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6224): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6224): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6224): bssid match
,I/dhcpcd  ( 6224): wlan0: rebinding lease of 192.168.1.132
,I/DIAGMON_AGENT( 6228): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_5603/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_4172/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6228): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6228): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6228): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6247): MountEmulatedStorage()
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6247 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6247): v2
I/libpersona( 6247): KNOX_SDCARD checking this for 10008
I/SELinux ( 6247): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6247): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Killing 5259:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6247): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6247): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6247): TimaSignature is unavailable
,D/ActivityThread( 6247): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5176:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 15:17:19 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6263): MountEmulatedStorage(),
E/Zygote  ( 6263): v2
I/libpersona( 6263): KNOX_SDCARD checking this for 10031
I/libpersona( 6263): KNOX_SDCARD not a persona
,I/SELinux ( 6263): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6263 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6263): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5259/cgroup.procs: No such file or directory
,E/SELinux ( 6263): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/TimaKeyStoreProvider( 6263): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
D/ActivityThread( 6263): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy()
,I/SO_AGENT( 6263): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5706): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5765): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5765): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5765): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5706): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5765): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5706): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5706): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5706): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/SA      ( 5765): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5765): [OR] == isSIMCardReady false ==
,I/SA      ( 5765): [SCU] == networkStateCheck == false
,I/SA      ( 5765): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5659:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1586): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5176/cgroup.procs: No such file or directory
,D/daemonapp( 1645): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1586): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1586): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1586): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1586): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1586): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1586): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6280): MountEmulatedStorage()
,E/Zygote  ( 6280): v2
I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6280 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/libpersona( 6280): KNOX_SDCARD checking this for 10121
I/libpersona( 6280): KNOX_SDCARD not a persona
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6280): Added TimaKeyStore provider
,W/ResourcesManager( 6280): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6280): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6280): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6280): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6280): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6280): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6295): MountEmulatedStorage()
,E/Zygote  ( 6295): v2
I/libpersona( 6295): KNOX_SDCARD checking this for 10141
I/libpersona( 6295): KNOX_SDCARD not a persona
,I/SELinux ( 6295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6295 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/SELinux ( 6295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5691:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6295): TimaSignature is unavailable
,D/ActivityThread( 6295): Added TimaKeyStore provider
,W/ResourcesManager( 6295): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5659/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_5691/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5814): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5814): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5814): sendNotify, [notify] : null
D/BadgeProvider( 5814): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5814): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5814): update, [UpdateCount] : 1
,D/Launcher.Model( 1479): reloadBadges entered.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6318 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6318): MountEmulatedStorage(),
I/libpersona( 6318): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD not a persona
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
D/ActivityThread( 6318): Added TimaKeyStore provider
,D/SecurityLogAgent( 6318): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6318): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6318): StateMachine : Current State = 1
,E/Watchdog( 1017): !@Sync 5
,D/SecurityLogAgent( 6318): StateMachine : Changed Current State = 1
,I/ActivityManager( 1017): Killing 5273:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2047): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2047): num queued entries: 0
,I/iu.UploadsManager( 2047): num updated entries: 0
,I/iu.SyncManager( 2047): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2047): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 58445(3MB) AllocSpace objects, 21(388KB) LOS objects, 33% free, 23MB/35MB, paused 3.178ms total 211.494ms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5098): connection state changed from CONNECTED to DISCONNECTED
,E/Zygote  ( 6340): MountEmulatedStorage(),
I/libpersona( 6340): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6340): v2
I/libpersona( 6340): KNOX_SDCARD not a persona
I/SELinux ( 6340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6340 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6340): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
,I/ActivityManager( 1017): Killing 5746:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6340): TimaSignature is unavailable
,D/ActivityThread( 6340): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5273/cgroup.procs: No such file or directory
,E/SPPClientService( 6340): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6340): [SystemStateMoniter] Current Time : 168355
,E/SPPClientService( 6340): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6340): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6340): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6340): PushLog.txt file is not deleted.
,D/SPPClientService( 6340): PushLog.txt file is not deleted.
D/SPPClientService( 6340): ============PushLog. stop!
,E/Zygote  ( 6357): MountEmulatedStorage()
,E/Zygote  ( 6357): v2
I/libpersona( 6357): KNOX_SDCARD checking this for 10110
I/libpersona( 6357): KNOX_SDCARD not a persona
I/SELinux ( 6357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_5746/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6357 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Killing 5782:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
E/SELinux ( 6357): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SPPClientService( 6340): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6357): TimaSignature is unavailable
,D/ActivityThread( 6357): Added TimaKeyStore provider
,W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5782/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6357): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6357):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6357):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,W/GAv4    ( 6357): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6357): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6357): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6357): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 6224): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,V/AlarmManager( 1017): waitForAlarm result :4
,I/dhcpcd  ( 6224): wlan0: leased 192.168.1.132 for 86400 seconds
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6357): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,E/WifiNative-wlan0( 1017): do suspend true
,I/LibraryLoader( 6357): Time to load native libraries: 2 ms (timestamps 8841-8843)
I/LibraryLoader( 6357): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6357): Binding Chromium to main looper Looper (main, tid 1) {26d7e225}
,I/LibraryLoader( 6357): Expected native library version number "",actual native library version number ""
I/chromium( 6357): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1017): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1017): updateNetworkInfo()
I/BrowserStartupController( 6357): Initializing chromium process, singleProcess=true
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/art     ( 6357): Attempt to remove local handle scope entry from IRT, ignoring
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1017): Adding iface wlan0 to network 503
E/SysUtils( 6357): ApplicationContext is null in ApplicationStatus
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
,D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1017): updateNetworkInfo()
,E/ConnectivityService( 1017): updateNetworkInfo()
W/chromium( 6357): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/ConnectivityService( 1017):    accepting network in place of null
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1455): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1455): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/libEGL  ( 6357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6357): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6357): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6357): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6357): Local Branch: 
I/Adreno-EGL( 6357): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6357): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6357):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,V/NetworkStats( 1017): updateIfacesLocked()
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 6ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/AudioManagerAndroid( 6357): Requires BLUETOOTH permission
,I/NSApplication( 6357): Starting up...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6439): MountEmulatedStorage()
,E/Zygote  ( 6439): v2
I/libpersona( 6439): KNOX_SDCARD checking this for 10077
I/libpersona( 6439): KNOX_SDCARD not a persona
,I/SELinux ( 6439): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6439 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6439): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6439): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6439): TimaSignature is unavailable
,D/ActivityThread( 6439): Added TimaKeyStore provider
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/Finsky  ( 5345): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5345): [1] 5.onFinished: Installation state replication failed.
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5345): [1] 5.onFinished: Scheduling replication attempt 5.
,D/WaitQueueForNetworkActivate( 5995): notifyNetworkActivated
,I/ActivityManager( 1017): Killing 5644:com.android.mms/u0a41 (adj 15): empty #31
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 5995): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 18 Jan 2016 14:17:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453126641721], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453126641677]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CountryDetector( 1017): No listener is left
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_5644/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5995): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5995): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5995): exit::IDLE
D/InitializeManagerStateMachine( 5995): entry::NETWORK_CHECK
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 5995): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5995): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5995): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5995): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): entry::SUCCESS
D/hcjo    ( 5995): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/Hs20UtilService( 1682): Starting #10
,I/Hs20UtilService( 1682): Message received 5007
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5995): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/InitializeManagerStateMachine( 5995): exit::SUCCESS
D/InitializeManagerStateMachine( 5995): entry::IDLE
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1017): Killing 5832:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
I/NetworkMonitor( 6179): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #11
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1682): Message received 5007
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #12
,I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #13
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/Hs20UtilService( 1682): Message received 5007
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5676): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5676): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5676): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5676): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6179): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5832/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6228): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6228): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5706): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5706): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5706): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5706): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6247): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6247): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 15:17:22 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3681): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5706): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5706): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5706): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 5765): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5765): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5765): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5706): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5765): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5765): [OR] == isSIMCardReady false ==
,I/SA      ( 5765): [SCU] == networkStateCheck == true
,I/KLMS-2.5.123: ( 3681): NetworkChangeOperations(): uploadRequestLog().END 
,I/SA      ( 5765): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5765): isChinaCountryCode : false
I/SA      ( 5765): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5765): [OR] == networkStateCheck true ==
,I/KLMS-2.5.123: ( 3681): StateImplV2(): networkChangeListener().END
,I/DBG_POLICYDM( 5706): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy()
,I/SA      ( 5765): [OR] GetMyCountryZoneTask
,I/SA      ( 5765): [OR] onReceive END
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5765): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5706): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/accuweather( 1586): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/SA      ( 5765): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
I/DBG_POLICYDM( 5706): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/SecContentProvider2( 1017): mCursor = null
,I/SA      ( 5765): [SSP] query invoked
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/daemonapp( 1645): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1586): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1586): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1586): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1586): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5765): [TPMU] GetMccFromDB : null
I/SA      ( 5765): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5765): [TPM] isNoProxy(default) : true
E/DBG_POLICYDM( 5706): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1586): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1586): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/File    ( 5765): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5706): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5706): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/QuickConnect( 6280): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6280): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6280): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6318): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6318): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6318): StateMachine : Current State = 1
,D/SecurityLogAgent( 6318): StateMachine : Changed Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 2047): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/iu.UploadsManager( 2047): num queued entries: 0
,I/iu.UploadsManager( 2047): num updated entries: 0
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 2047): NEXT; no task
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/ChimeraCfgMgr( 2047): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2047): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6340): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6340): [SystemStateMoniter] Current Time : 169979
,E/SPPClientService( 6340): [SystemStateMoniter] No Connect : false
,I/System.out( 5098): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5098): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5995): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5995): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5995): exit::IDLE
D/InitializeManagerStateMachine( 5995): entry::NETWORK_CHECK
I/System.out( 5098): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/InitializeManagerStateMachine( 5995): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5995): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5995): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5995): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5995): entry::SUCCESS
D/hcjo    ( 5995): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5995): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5995): exit::SUCCESS
D/InitializeManagerStateMachine( 5995): entry::IDLE
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/Babel   ( 5098): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 2047): [AccountUtils] Account not ready
W/Kids    ( 2047): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2047): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2047): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2047): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2047): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2047): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2047): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2047): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2047): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2047): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2047): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2047): 	at java.lang.Thread.run(Thread.java:818)
D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1661): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1661): Message class com.google.f.a.a.p
,I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6105): 
I/SA      ( 5765): [RC New] Execute method=[GET] start
I/SA      ( 5765): [RC New] Security=[true]
I/System.out( 5765): Thread-980(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5765): Thread-980(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5765): Thread-980(ApacheHTTPLog):isShipBuild true
I/System.out( 5765): Thread-980(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5765): Thread-980(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10036
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6105): 
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6105): 
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6105): 
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6105): 
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6105): 
I/SA      ( 5765): [RC New] [v2liruge] api execute + 639
I/SA      ( 5765): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5765): AsyncTask #1 calls detatch()
I/SA      ( 5765): [ODM] saveOpenData( GEO_IP, PL )
I/SA      ( 5765): [OCP] update openData : PL
I/SA      ( 5765): [TPMU] getNetworkMcc : 
I/SA      ( 5765): [SCU] saveMccToPreferece Start
I/SA      ( 5765): [SCU] RegionMCC : 260
I/SA      ( 5765): [SSP] query invoked
I/jxcore-log( 6105): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6105): 
I/SA      ( 5765): [TPMU] GetMccFromDB : null
I/SA      ( 5765): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5765): [SCU] saveMccToPreferece End
I/SA      ( 5765): [RC New] executeRequest [v2liruge] end. 693
I/SA      ( 5765): [RC New] Execute end
I/SA      ( 5765): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5765): [OR] GetMyCountryZoneTask Success
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6224): wlan0: sending IPv6 Router Solicitation
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/jxcore-log( 6105): Test app app.js loaded
I/jxcore-log( 6105): 
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6105): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6105): BLE advertisement is supported
I/jxcore-log( 6105): 
,I/VacuumService( 1661): Vacuum at: now=1453126644024 tag=VacuumService
,I/GoogleURLConnFactory( 1661): Using platform SSLCertificateSocketFactory
,I/chromium( 6105): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/Uploader( 1661): No account for auth token provided
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1661): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1661): (HTTPLog)-Static: isShipBuild true
I/System.out( 1661): (HTTPLog)-Thread-190-973817422: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1661): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,I/qtaguid ( 1661): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,W/Uploader( 1661): No account for auth token provided
,I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/Uploader( 1661): No account for auth token provided
,I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,W/Uploader( 1661):  no longer exists, so no auth token.
,I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/Uploader( 1661): No account for auth token provided
,I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6179): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6179): Stop autocaching.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 3550): callingUid 10011, callindPid: 3550
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SMD     (  290): DCD OFF
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 40205(2MB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 23MB/35MB, paused 2.485ms total 147.601ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6179): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1661): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1661): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1661): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1661): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1661): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1661): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
I/System.out( 1661): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1661): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1661, getuid(): 10011
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1661): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 173095
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3484)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5676): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5676): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5676): [GetString-S]
I/ReactiveServiceManager( 5676): Supported : 1
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5676): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5676): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5676): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5676): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5676): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5676): [ensureRegistration] - No Samsung account
,E/SMD     (  290): DCD OFF
,I/dhcpcd  ( 6224): wlan0: sending IPv6 Router Solicitation
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 310
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5995): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5995): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5995): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5995): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5995): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5995): entry::IDLE
,I/dhcpcd  ( 6224): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6224): wlan0: no IPv6 Routers available
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5995): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5995): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5995): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5995): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5995): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5995): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5995): entry::IDLE
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate,
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1017): waitForAlarm result :4
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5345): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5345): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5345): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,V/AlarmManager( 1017): waitForAlarm result :8,
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 280
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6022): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6022): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1661): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1661): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1661): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1661): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1661): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6022): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6022): Soft error
E/BooksSync( 6022): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6022): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6022): Sync error
E/BooksSync( 6022): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6022): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6022): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 284204, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 9
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1414): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1414): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2622): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2622): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...,
I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040,
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 10
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6105): --= Surplus to requirements =--
I/jxcore-log( 6105): 
,I/jxcore-log( 6105): ****TEST TOOK:  ms ****
I/jxcore-log( 6105): 
I/jxcore-log( 6105): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6105): 
,D/AndroidRuntime( 6577): 
D/AndroidRuntime( 6577): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6577): CheckJNI is OFF
,D/AndroidRuntime( 6577): readGMSProperty: start
D/AndroidRuntime( 6577): readGMSProperty: already setted!!
D/AndroidRuntime( 6577): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6577): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6577): readGMSProperty: end
D/AndroidRuntime( 6577): addProductProperty: start
,E/AffinityControl( 6577): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6577): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{12303822}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6105:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1017): Skipping PackageSetting{166c41a8 com.example.hello/10346} due to missing metadata
,I/WindowState( 1017): WIN DEATH: Window{374bd92c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3dec62a u0 com.test.thalitest/.MainActivity t20}
,D/InputDispatcher( 1017): Focus left window: 6105
,W/ActivityManager( 1017): Spurious death for ProcessRecord{1f18c4ef 6105:com.test.thalitest/u0a338}, curProc for 6105: null
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{3dec62a u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{3dec62a u0 com.test.thalitest/.MainActivity t20 f}
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1017): Focused application released
,I/art     ( 3958): Explicit concurrent mark sweep GC freed 3204(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 758us total 27.500ms
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1815): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1873): mOCRHelper is null
,I/art     ( 5977): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 759us total 58.212ms
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 18 15:19:57 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3681): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onCreate()
,E/Zygote  ( 6590): MountEmulatedStorage()
E/Zygote  ( 6590): v2
I/libpersona( 6590): KNOX_SDCARD checking this for 10090
I/libpersona( 6590): KNOX_SDCARD not a persona
,I/SELinux ( 6590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6590 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3681): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 36725(2MB) AllocSpace objects, 69(1113KB) LOS objects, 33% free, 23MB/35MB, paused 3.231ms total 163.100ms
,I/art     ( 1017): WaitForGcToComplete blocked for 160.142ms for cause Explicit
,I/KLMS-2.5.123: ( 3681): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,D/TimaKeyStoreProvider( 6590): TimaSignature is unavailable
,D/ActivityThread( 6590): Added TimaKeyStore provider
,D/RegisteredServicesCache( 1445): empty dynamic service
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,D/elm:15121( 6590): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6590): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6590): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6590): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6590): ElmAgentService : onCreate()
,D/elm:15121( 6590): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6590): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6590): MDMBridge.getInstance()
D/elm:15121( 6590): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6590): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3681): KLMSIntentService(): onDestroy()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6590): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 4952:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 9990(473KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.393ms total 180.712ms
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,D/TaskPersister( 1017): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1017): uID is 10338
,V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1017): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{12303822}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 6577): Shutting down VM
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest,
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest,
,W/libprocessgroup( 1017): failed to open /acct/uid_10039/pid_4952/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 5676): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5676): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5676): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5676): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6608): MountEmulatedStorage()
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6608 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 6608): v2
I/libpersona( 6608): KNOX_SDCARD checking this for 10029
I/libpersona( 6608): KNOX_SDCARD not a persona
,I/SELinux ( 6608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6608): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6608): TimaSignature is unavailable
,I/art     (  307): Explicit concurrent mark sweep GC freed 8699(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.032ms total 21.823ms
,D/ActivityThread( 6608): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.869ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 707us total 17.546ms
,I/FeatureConfig( 6608): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5765): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 5765): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1017): Killing 5849:com.wsomacp/u0a23 (adj 15): empty #31,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6608): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SMD     (  290): DCD OFF
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6608): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6626): MountEmulatedStorage()
I/libpersona( 6626): KNOX_SDCARD checking this for 10039
E/Zygote  ( 6626): v2
I/libpersona( 6626): KNOX_SDCARD not a persona
I/SELinux ( 6626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourcesManager( 6608): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6626 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6608): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6626): TimaSignature is unavailable
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread( 6626): Added TimaKeyStore provider
,W/art     ( 6577): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6608): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_5849/cgroup.procs: No such file or directory
,W/ResourcesManager( 6608): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6608): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6608): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6626): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6626): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6626): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6626): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6626): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6626): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6626): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6626): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6626): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6626): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6626): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6626): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NearbySource( 6626): Nearby Source Create!
D/NearbyContext( 6626): Nearby Context Create!
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6626): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 6626): Samsung link source created

```
