#### Test 5497026186051be_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
E/SMD     (  294): DCD OFF
D/AndroidRuntime( 6068): 
D/AndroidRuntime( 6068): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6068): CheckJNI is OFF
D/AndroidRuntime( 6068): readGMSProperty: start
D/AndroidRuntime( 6068): readGMSProperty: already setted!!
D/AndroidRuntime( 6068): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6068): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6068): readGMSProperty: end
D/AndroidRuntime( 6068): addProductProperty: start
E/AffinityControl( 6068): AffinityControl: registerfunction enter
D/AndroidRuntime( 6068): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
E/Zygote  ( 6080): MountEmulatedStorage()
E/Zygote  ( 6080): v2
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6080 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/libpersona( 6080): KNOX_SDCARD checking this for 10338
I/libpersona( 6080): KNOX_SDCARD not a persona
I/SELinux ( 6080): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6080): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6080): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1020): Focused application set to: xxxx
D/InputDispatcher( 1020): Focus left window: 1495
D/AndroidRuntime( 6068): Shutting down VM
D/TimaKeyStoreProvider( 6080): TimaSignature is unavailable
D/ActivityThread( 6080): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
D/Launcher( 1495): onTrimMemory. Level: 20
V/ActivityThread( 1495): updateVisibility : ActivityRecord{117583d0 token=android.os.BinderProxy@17e027dc {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
I/WebViewFactory( 6080): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6080): Time to load native libraries: 2 ms (timestamps 2165-2167)
I/LibraryLoader( 6080): Expected native library version number "",actual native library version number ""
W/art     ( 6068): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6080): Binding Chromium to main looper Looper (main, tid 1) {34dd0296}
,I/LibraryLoader( 6080): Expected native library version number "",actual native library version number ""
I/chromium( 6080): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6080): Initializing chromium process, singleProcess=true
,W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6080): ApplicationContext is null in ApplicationStatus
,W/chromium( 6080): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6080): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6080): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6080): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6080): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6080): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6080): Local Branch: 
I/Adreno-EGL( 6080): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6080): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6080):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6080): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6080): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6080): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6080): CordovaWebView is running on device made by: samsung
,W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6080): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{2308f477 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6080): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6080): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6080): updateVisibility : ActivityRecord{28cfe0a3 token=android.os.BinderProxy@3ae9e25d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6080): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6080): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1020): Focus entered window: 6080
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6080): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6080): Initialized EGL, version 1.4
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6080): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6080): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
,I/ActivityManager( 1020): Displayed Component not be shown by security: +720ms (total +36s296ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{2308f477 u0 com.test.thalitest/.MainActivity t20} time:152746
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 6080): showStatusIcon on inactive InputConnection
,I/Timeline( 6080): Timeline: Activity_idle id: android.os.BinderProxy@3ae9e25d time:152760
,I/SamsungIME( 1834): getCurrentCandidateView
,W/BindingManager( 6080): Cannot call determinedVisibility() - never saw a connection for the pid: 6080
,D/SamsungIME( 1834): Dismiss ExpandCandiate
,I/SamsungIME( 1834): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1834): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 6080): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1834): KeybaordView init() : load resources
,I/SamsungIME( 1834): getCurrentKeyboard
,I/SamsungIME( 1834): getTextKeyboard
,D/SamsungIME( 1834): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6080): JniHelper::setJavaVM(0xb89f2448), pthread_self() = -1191934072
,D/JX-Cordova( 6080): jxcore cordova android initializing
,I/PowerManagerService( 1020): [PWL] Off : 75s ago
,W/jxcore-log( 6080): Initializing JXcore engine
W/jxcore-log( 6080): JXcore engine is ready
,W/jxcore-log( 6080): Starting JXcore engine
,E/audit   ( 1831): type=1400 msg=audit(1452511789.699:205): avc:  denied  { ioctl } for  pid=6080 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1831):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1831): type=1300 msg=audit(1452511789.699:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be831d58 items=0 ppid=314 ppcomm=main pid=6080 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1831): type=1320 msg=audit(1452511789.699:205): 
,W/jxcore-log( 6080): Platform android
W/jxcore-log( 6080): 
W/jxcore-log( 6080): Process ARCH arm
W/jxcore-log( 6080): 
,E/SMD     (  294): DCD OFF
,I/jxcore-log( 6080): JXcore Cordova bridge is ready!
I/jxcore-log( 6080): 
,W/jxcore-log( 6080): JXcore engine is started
,I/chromium( 6080): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6080): Toggling radios to true
I/jxcore-log( 6080): 
,D/BluetoothAdapter( 6080): enable()
,D/BluetoothAdapter( 6080): enable(): BT is already enabled..!
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: true pid=6080, uid=10338
,W/ActivityManager( 1020): Permission Denial: getCurrentUser() from pid=6080, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1020): Failed getting userId using ActivityManagerNative
W/WifiService( 1020): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6080, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1020): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1020): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1020): name = wifi_on
,I/WifiService( 1020): disconnect: pid=6080, uid=10338
,I/wpa_supplicant( 1399): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6080): Radios toggled
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): My device name is: samsung-SM-A300FU
I/jxcore-log( 6080): 
,I/wpa_supplicant( 1399): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
,I/wpa_supplicant( 1399): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1399): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48,
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/Tethering( 1020): InitialState.processMessage what=4
,I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1399): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1399): Cmd 35605 not handled
E/WifiStateMachine( 1020): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1399): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1399): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1399): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1399): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1399): First Scan Start
I/wpa_supplicant( 1399): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1020): No numeric data
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1174): updateTetherState():false, false
,V/NetworkStats( 1020): performPollLocked() took 10ms
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
E/WifiNative-wlan0( 1020): do suspend true
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1020): updateNetworkInfo()
,D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1020): updateNetworkInfo()
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1713): Read error: ssl=0xb8f86ff0: I/O error during system call, Connection timed out
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7e7d7c8
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1209542520)
E/WifiStateMachine( 1020): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1399): wlan0: Setting scan request: 0 sec 0 usec
E/WifiNative-wlan0( 1020): do suspend true
D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1209542520) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
,I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7e7d7c8
,D/CommandListener(  280): Clearing all IP addresses on wlan0
D/ConnectivityService( 1020): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
D/ConnectivityService( 1020): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1020): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1473): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1020): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1473): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1020): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
D/WifiNetworkAgent( 1020): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): updateIfacesLocked()
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,V/NetworkStats( 1020): performPollLocked() took 9ms
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 51587(2MB) AllocSpace objects, 33(532KB) LOS objects, 33% free, 24MB/36MB, paused 2.725ms total 212.715ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,V/NativeCrypto( 1713): SSL shutdown failed: ssl=0xb8f86ff0: I/O error during system call, Broken pipe
I/Hs20UtilService( 2117): Starting #8
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/ConnectivityService( 1020): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): doQuit - quitNow()
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,I/Hs20UtilService( 2117): Message received 5007
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2117): Starting #9
,I/Hs20UtilService( 2117): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6133): MountEmulatedStorage()
I/libpersona( 6133): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6133): v2
I/libpersona( 6133): KNOX_SDCARD not a persona
I/SELinux ( 6133): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6133 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6133): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6133): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/TimaKeyStoreProvider( 6133): TimaSignature is unavailable
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/ActivityThread( 6133): Added TimaKeyStore provider
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,D/PhoneApp( 1473): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6133): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1473): FileWriteThread : threadType = 3
,I/Babel_SMS( 6133): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6133): MmsConfig.loadMmsSettings
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy( 1020): updateDataUsageMap
D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/Babel_SMS( 6133): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6133): MmsConfig.loadFromDatabase
E/Babel_SMS( 6133): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6133): MmsConfig.loadFromResources
E/Babel_SMS( 6133): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6133): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/Settings( 6133): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6133): startup - clean
I/Babel   ( 6133): deleted: false for 0
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/VideoCapabilities( 6133): Unrecognized profile 2130706433 for video/avc
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6133): Unsupported mime audio/evrc
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6133): Unsupported mime audio/qcelp
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6133): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 6133): Unsupported mime audio/mpeg-L2
I/PCWCLIENTTRACE_PushUtil( 5666): SPPPushClient is installed : true
W/AudioCapabilities( 6133): Unsupported mime audio/x-ms-wma
I/PCWCLIENTTRACE_PushUtil( 5666): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5666): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
W/AudioCapabilities( 6133): Unsupported mime audio/x-ima
W/AudioCapabilities( 6133): Unsupported mime audio/qcelp
I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
W/AudioCapabilities( 6133): Unsupported mime audio/evrc
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): noConnectivity : true
W/VideoCapabilities( 6133): Unsupported mime video/wvc1
W/VideoCapabilities( 6133): Unsupported mime video/x-ms-wmv
E/Zygote  ( 6175): MountEmulatedStorage()
E/Zygote  ( 6175): v2
I/libpersona( 6175): KNOX_SDCARD checking this for 10108
I/libpersona( 6175): KNOX_SDCARD not a persona
I/SELinux ( 6175): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6175 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6175): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6175): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 6133): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 6133): Unsupported mime video/wvc1
W/VideoCapabilities( 6133): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 6133): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 6133): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 6133): Unsupported mime video/mp43
D/TimaKeyStoreProvider( 6175): TimaSignature is unavailable
D/ActivityThread( 6175): Added TimaKeyStore provider
W/VideoCapabilities( 6133): Unsupported mime video/sorenson
W/VideoCapabilities( 6133): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6133): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6133): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6133): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6133): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6133): Unrecognized profile 2130706433 for video/avc
I/ActivityManager( 1020): Killing 5191:com.google.android.gm/u0a99 (adj 15): empty #31
I/vclib   ( 6133): onServiceConnected
W/Babel   ( 6133): Attempted to change video mute state without an active call.
I/wpa_supplicant( 1399): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1399): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1399): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1399): Trying to associate with  'G700'
I/wpa_supplicant( 1399): Re-associate with C0.AA.48
I/wpa_supplicant( 1399): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1020): didn't find BSSID Trying to associate with SSID 'NG700'
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/MusicStore( 6175): Database version: 120
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
E/wpa_supplicant( 1399): Cmd 35605 not handled
I/wpa_supplicant( 1399): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1399): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/wpa_supplicant( 1399): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1399): Associated with C0.AA.48
I/wpa_supplicant( 1399): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1399): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1399): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1399): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1399): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1399): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1399): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1399): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1399): Blacklist: Clear (temp) 
I/wpa_supplicant( 1399): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/Tethering( 1020): No numeric data
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1020): clearTetheredNotification()
W/libprocessgroup( 1020): failed to open /acct/uid_10099/pid_5191/cgroup.procs: No such file or directory
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
V/NetworkStats( 1020): performPollLocked() took 4ms
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [50]
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
E/WifiConfigStore( 1020): setLastSelectedConfiguration -1
D/HeadsetStateMachine( 2667): Disconnected process message: 10
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6175): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/ConnectivityService( 1020): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1020): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/CommandListener(  280): Setting iface cfg
E/WifiStateMachine( 1020): Start Dhcp Watchdog 2
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
W/ResourcesManager( 6175): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6175): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
E/WifiNative-wlan0( 1020): do suspend false
D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
V/JNIHelp ( 6175): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6175): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6175): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ec77eaf: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6175): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6175): GMSCore installation verified
,I/ConfigStore( 6175): Config Database version: 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1020): getStreamVolume 3 index 70
,I/MediaRouter( 6175): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6175): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6205): MountEmulatedStorage(),
I/libpersona( 6205): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6205): v2
I/libpersona( 6205): KNOX_SDCARD not a persona
,I/SELinux ( 6205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6205 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6205): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 6211): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6211): version 5.5.6 starting
E/dhcpcd  ( 6211): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/art     (  314): Explicit concurrent mark sweep GC freed 8712(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 605us total 26.297ms
,I/GHttpClientFactory( 6175): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.997ms
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 6175): Using platform SSLCertificateSocketFactory
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 16.988ms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/dhcpcd  ( 6211): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6211): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6211): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6211): bssid match
,I/dhcpcd  ( 6211): wlan0: rebinding lease of 192.168.1.132
,D/TimaKeyStoreProvider( 6205): TimaSignature is unavailable
,D/ActivityThread( 6205): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 5591:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/SQLiteLog( 1713): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6231): MountEmulatedStorage()
,E/Zygote  ( 6231): v2
I/libpersona( 6231): KNOX_SDCARD checking this for 1000
I/libpersona( 6231): KNOX_SDCARD not a persona
,I/SELinux ( 6231): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6231): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6231): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6231 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 4212:com.sec.spp.push/u0a32 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 6231): TimaSignature is unavailable
,D/ActivityThread( 6231): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6231): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_5591/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4212/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6231): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6231): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6231): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6246 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6246): MountEmulatedStorage()
E/Zygote  ( 6246): v2
I/libpersona( 6246): KNOX_SDCARD checking this for 10008
I/libpersona( 6246): KNOX_SDCARD not a persona
,I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 5173:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
,D/ActivityThread( 6246): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 5637:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:29:52 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3758): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6262): MountEmulatedStorage()
,E/Zygote  ( 6262): v2
I/libpersona( 6262): KNOX_SDCARD checking this for 10031
I/libpersona( 6262): KNOX_SDCARD not a persona,
I/SELinux ( 6262): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6262): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6262 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6262): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3758): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6262): TimaSignature is unavailable
,D/ActivityThread( 6262): Added TimaKeyStore provider
,I/SO_AGENT( 6262): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5770): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5770): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5770): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5770): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5770): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5770): [OR] == isSIMCardReady false ==
,I/SA      ( 5770): [SCU] == networkStateCheck == false
,I/SA      ( 5770): [OR] onReceive END
,I/ActivityManager( 1020): Killing 5259:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/SMD     (  294): DCD OFF
,D/daemonapp( 1655): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1597): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1597): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1597): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_5173/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5637/cgroup.procs: No such file or directory
,D/accuweather( 1597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,V/AlarmManager( 1020): waitForAlarm result :4
,I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6279 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/Zygote  ( 6279): MountEmulatedStorage()
,E/Zygote  ( 6279): v2
I/libpersona( 6279): KNOX_SDCARD checking this for 10121
I/libpersona( 6279): KNOX_SDCARD not a persona
,I/SELinux ( 6279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6279): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6279): TimaSignature is unavailable
,D/ActivityThread( 6279): Added TimaKeyStore provider
,W/ResourcesManager( 6279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6279): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6279): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6279): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/dhcpcd  ( 6211): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/QuickConnect( 6279): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6294): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6294 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 6294): v2
I/libpersona( 6294): KNOX_SDCARD checking this for 10141
I/libpersona( 6294): KNOX_SDCARD not a persona
,I/SELinux ( 6294): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 5656:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6294): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6294): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_5259/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6294): TimaSignature is unavailable
D/ActivityThread( 6294): Added TimaKeyStore provider
,I/dhcpcd  ( 6211): wlan0: leased 192.168.1.132 for 86400 seconds
,W/ResourcesManager( 6294): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6294): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6294): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_10087/pid_5656/cgroup.procs: No such file or directory
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId,
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/BadgeProvider( 5807): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5807): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 5807): sendNotify, [notify] : null
D/BadgeProvider( 5807): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5807): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5807): update, [UpdateCount] : 1
,D/Launcher.Model( 1495): reloadBadges entered.
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/WifiNative-wlan0( 1020): do suspend true
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6338): MountEmulatedStorage(),
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD checking this for 1000
I/libpersona( 6338): KNOX_SDCARD not a persona
,I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5272:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1020): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1020): VerifyingLinkState enter
,D/WifiNative-wlan0( 1020): callSECApiInt - ID [210]
,E/ConnectivityService( 1020): updateNetworkInfo()
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1020): Adding iface wlan0 to network 503
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1020): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/WifiWatchdogStateMachine( 1020): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1020): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1020): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable
,D/ActivityThread( 6338): Added TimaKeyStore provider
,E/ConnectivityService( 1020): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1020): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1020): LTETest block dns file not exists
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1020): updateNetworkInfo()
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/ConnectivityService( 1020): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
E/WifiStateMachine( 1020): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1020): Failed to clear dns cache for: com.samsung.android.app.galaxyfinder
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-12ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
D/ConnectivityService( 1020):    accepting network in place of null
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/CSLegacyTypeTracker( 1020): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/TelephonyNetworkFactory( 1473): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1473): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/CSLegacyTypeTracker( 1020): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1020): mBoosterFLAG : 0
I/WifiTrafficPoller( 1020): current booster mode : FullMode
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [212]
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
V/NetworkStats( 1020): updateIfacesLocked()
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
V/NetworkStats( 1020): performPollLocked() took 12ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/SecurityLogAgent( 6338): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6338): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6338): StateMachine : Current State = 1
D/SecurityLogAgent( 6338): StateMachine : Changed Current State = 1
I/ActivityManager( 1020): Killing 5704:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1020): failed to open /acct/uid_10029/pid_5272/cgroup.procs: No such file or directory
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1020): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ChimeraCfgMgr( 1989): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1989): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 11:29:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452511793498], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452511793482]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
,D/ConnectivityService( 1020): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1020): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_5704/cgroup.procs: No such file or directory
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,E/Zygote  ( 6363): MountEmulatedStorage()
I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6363 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6363): v2
I/libpersona( 6363): KNOX_SDCARD checking this for 10032
I/SELinux ( 6363): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6363): KNOX_SDCARD not a persona
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/SELinux ( 6363): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6363): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6363): TimaSignature is unavailable,
D/ActivityThread( 6363): Added TimaKeyStore provider
,I/System.out( 6133): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6133): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6133): (HTTPLog)-Static: isShipBuild true
I/System.out( 6133): (HTTPLog)-Thread-1051-281177219: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6133): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10102
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6133): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
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
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/SPPClientService( 6363): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6363): [SystemStateMoniter] Current Time : 158201
,W/Kids    ( 1989): [AccountUtils] Account not ready
W/Kids    ( 1989): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1989): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1989): 	at java.lang.Thread.run(Thread.java:818)
E/SPPClientService( 6363): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6363): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6363): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6363): PushLog.txt file is not deleted.
D/SPPClientService( 6363): PushLog.txt file is not deleted.
D/SPPClientService( 6363): ============PushLog. stop!
,I/Babel   ( 6133): connection state changed from UNKNOWN to CONNECTED
,E/Zygote  ( 6382): MountEmulatedStorage()
E/Zygote  ( 6382): v2
,I/libpersona( 6382): KNOX_SDCARD checking this for 10110
I/libpersona( 6382): KNOX_SDCARD not a persona
,I/SELinux ( 6382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6382 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6382): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimaKeyStoreProvider( 6382): TimaSignature is unavailable
,D/ActivityThread( 6382): Added TimaKeyStore provider
,E/SPPClientService( 6363): [[SystemStateMonitorService]] No Active Internet
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6382): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6382): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6382): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6382):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6382):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6382): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6382): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6382): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/GAv4    ( 6382): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6382): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/SSRM:n  ( 1020): SIOP:: AP = 300
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6175): type=WIFI subType= reason=null isConnected=true
,I/BooksSync( 6004): Starting books sync for 61035162, extras: ade,
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/BooksConfig( 6004): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/WebViewFactory( 6382): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/LibraryLoader( 6382): Time to load native libraries: 4 ms (timestamps 8687-8691)
,I/LibraryLoader( 6382): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6382): Binding Chromium to main looper Looper (main, tid 1) {1d2450e2}
,I/LibraryLoader( 6382): Expected native library version number "",actual native library version number ""
,I/chromium( 6382): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6382): Initializing chromium process, singleProcess=true
,W/art     ( 6382): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6382): ApplicationContext is null in ApplicationStatus
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/chromium( 6382): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6382): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6382): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6382): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6382): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6382): Local Branch: 
I/Adreno-EGL( 6382): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6382): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6382):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6382): Requires BLUETOOTH permission
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 58189(3MB) AllocSpace objects, 7(120KB) LOS objects, 33% free, 24MB/36MB, paused 2.620ms total 159.191ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/NSApplication( 6382): Starting up...
,E/BooksAccountManager( 6004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6004): Soft error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6004): Sync error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6004): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157458, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6441): MountEmulatedStorage(),
E/Zygote  ( 6441): v2
,I/libpersona( 6441): KNOX_SDCARD checking this for 10077
I/libpersona( 6441): KNOX_SDCARD not a persona
,I/SELinux ( 6441): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6441 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6441): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6441): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Killing 5625:com.android.mms/u0a41 (adj 15): empty #31
,I/ActivityManager( 1020): Killing 5742:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6441): TimaSignature is unavailable
,D/ActivityThread( 6441): Added TimaKeyStore provider
,D/ConnectivityService( 1020): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,D/CountryDetector( 1020): No listener is left
,W/libprocessgroup( 1020): failed to open /acct/uid_10152/pid_5742/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_5625/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 5975): notifyNetworkActivated
,W/ContextImpl( 5975): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1020): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5975): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5975): exit::IDLE
D/InitializeManagerStateMachine( 5975): entry::NETWORK_CHECK
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 5975): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5975): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5975): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): entry::SUCCESS
D/hcjo    ( 5975): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/Hs20UtilService( 2117): Starting #10
I/Hs20UtilService( 2117): Message received 5007
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5975): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/InitializeManagerStateMachine( 5975): exit::SUCCESS
D/InitializeManagerStateMachine( 5975): entry::IDLE
,I/ActivityManager( 1020): Killing 4834:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2117): Starting #11
,I/Hs20UtilService( 2117): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2117): Starting #12
,I/Hs20UtilService( 2117): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2117): Starting #13
,I/Hs20UtilService( 2117): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1020): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1020): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5666): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5666): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5666): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6175): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6231): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6231): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1020): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,W/libprocessgroup( 1020): failed to open /acct/uid_10011/pid_4834/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6246): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6246): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:29:54 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3758): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3758): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3758): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3758): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3758): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5770): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5770): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 5770): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5770): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5770): [OR] == isSIMCardReady false ==
,I/SA      ( 5770): [SCU] == networkStateCheck == true
,I/SA      ( 5770): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5770): isChinaCountryCode : false
I/SA      ( 5770): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5770): [OR] == networkStateCheck true ==
,I/SA      ( 5770): [OR] GetMyCountryZoneTask
,I/SA      ( 5770): [OR] onReceive END
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5770): [SRS] prepareGetMyCountryZone
,D/accuweather( 1597): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,D/daemonapp( 1655): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/accuweather( 1597): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
D/accuweather( 1597): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1597): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1020): mCursor = null
,I/SA      ( 5770): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5770): [SSP] query invoked
,D/accuweather( 1597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/DBG_POLICYDM( 5722): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/QuickConnect( 6279): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6279): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6279): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/SA      ( 5770): [TPMU] GetMccFromDB : null
,I/SA      ( 5770): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5770): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6338): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6338): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6338): StateMachine : Current State = 1
,D/SecurityLogAgent( 6338): StateMachine : Changed Current State = 1
,E/File    ( 5770): fail readDirectory() errno=2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1989): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1989): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6363): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6363): [SystemStateMoniter] Current Time : 159730
,E/SPPClientService( 6363): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6133): (HTTPLog)-Static: isSBSettingEnabled false
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5975): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5975): exit::IDLE
D/InitializeManagerStateMachine( 5975): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5975): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5975): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5975): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5975): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5975): entry::SUCCESS
D/hcjo    ( 5975): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5975): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5975): exit::SUCCESS
D/InitializeManagerStateMachine( 5975): entry::IDLE
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 1989): [AccountUtils] Account not ready
W/Kids    ( 1989): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1989): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1989): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1989): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1989): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1989): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1989): 	at java.lang.Thread.run(Thread.java:818)
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
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5770): [RC New] Execute method=[GET] start
,I/SA      ( 5770): [RC New] Security=[true]
,I/System.out( 5770): Thread-980(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5770): Thread-980(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5770): Thread-980(ApacheHTTPLog):isShipBuild true
I/System.out( 5770): Thread-980(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5770): Thread-980(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF,
,I/SA      ( 5770): [RC New] [v2liruge] api execute + 598
,I/SA      ( 5770): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5770): AsyncTask #1 calls detatch()
,I/SA      ( 5770): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5770): [OCP] update openData : PL
,I/SA      ( 5770): [TPMU] getNetworkMcc : 
,I/SA      ( 5770): [SCU] saveMccToPreferece Start
,I/SA      ( 5770): [SCU] RegionMCC : 260
I/SA      ( 5770): [SSP] query invoked
,I/SA      ( 5770): [TPMU] GetMccFromDB : null
I/SA      ( 5770): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5770): [SCU] saveMccToPreferece End
,I/SA      ( 5770): [RC New] executeRequest [v2liruge] end. 652
I/SA      ( 5770): [RC New] Execute end
,I/SA      ( 5770): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5770): [OR] GetMyCountryZoneTask Success
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/dhcpcd  ( 6211): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6211): wlan0: sendmsg: Cannot assign requested address
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6489): MountEmulatedStorage()
E/Zygote  ( 6489): v2
I/libpersona( 6489): KNOX_SDCARD checking this for 10011
,I/libpersona( 6489): KNOX_SDCARD not a persona
,I/SELinux ( 6489): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6489): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1020): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6489 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux ( 6489): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/MusicLeanback( 6175): Conditions not met for autocaching. okToAttempt=false
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/MusicLeanback( 6175): Stop autocaching.
,D/TimaKeyStoreProvider( 6489): TimaSignature is unavailable
,D/ActivityThread( 6489): Added TimaKeyStore provider
,W/ResourcesManager( 6489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6489): VM with version 2.1.0 has multidex support
,I/MultiDex( 6489): install
I/MultiDex( 6489): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6489): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6489): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6489): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2812a371: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6489): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1020): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1020): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1020): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1713): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1713): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1989): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6489): callingUid 10011, callindPid: 6489
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1989): Restart initialization of location
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1684): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 6175): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6175): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/art     ( 1713): Explicit concurrent mark sweep GC freed 23623(1422KB) AllocSpace objects, 10(202KB) LOS objects, 40% free, 7MB/12MB, paused 960us total 45.416ms
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,D/PowerManagerService( 1020): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 162874
,D/PowerManagerService( 1020): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
D/PowerManagerService( 1020): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3469)
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4,
,V/AlarmManager( 1020): waitForAlarm result :4,
,E/SMD     (  294): DCD OFF
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/GCM     ( 1713): Connected
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1713): Message class com.google.f.a.a.p
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5666): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5666): [GetString-S]
,I/ReactiveServiceManager( 5666): Supported : 1
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5666): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5666): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5666): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5666): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5666): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5666): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1020): waitForAlarm result :8
,I/dhcpcd  ( 6211): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 6080): Test app app.js loaded
I/jxcore-log( 6080): 
,I/chromium( 6080): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged,
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/ActivityManager( 1020): Killing 5793:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1020): failed to open /acct/uid_10042/pid_5793/cgroup.procs: No such file or directory
,E/Watchdog( 1020): !@Sync 5
,D/SSRM:n  ( 1020): SIOP:: AP = 310
,I/dhcpcd  ( 6211): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6211): wlan0: no IPv6 Routers available
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps,
,D/PreloadUpdateManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5975): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5975): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5975): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5975): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5975): entry::IDLE
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD OFF
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5343): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5343): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5343): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5975): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5975): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5975): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5975): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5975): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5975): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5975): entry::IDLE
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1713): Vacuum at: now=1452511808390 tag=VacuumService
,I/GoogleURLConnFactory( 1713): Using platform SSLCertificateSocketFactory
,W/Uploader( 1713): No account for auth token provided
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1713): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1713): (HTTPLog)-Static: isShipBuild true
I/System.out( 1713): (HTTPLog)-Thread-199-410862109: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1713): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1713): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,I/qtaguid ( 1713): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713): No account for auth token provided
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713): No account for auth token provided
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713):  no longer exists, so no auth token.
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,W/Uploader( 1713): No account for auth token provided
,I/System.out( 1713): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1713): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1713, getuid(): 10011
,E/SQLiteLog( 1713): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 33885(1725KB) AllocSpace objects, 7(116KB) LOS objects, 33% free, 24MB/36MB, paused 2.462ms total 176.263ms
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1020): [PWL] Off : 105s ago,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,V/AlarmManager( 1020): waitForAlarm result :4
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5343): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5343): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5343): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,I/BooksSync( 6004): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6004): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) ,
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6004): Soft error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6004): Sync error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6004): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 191728, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1020): !@Sync 6
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,I/Atfwd_Sendcmd(  332): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  332): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,V/AlarmManager( 1020): waitForAlarm result :4,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/Watchdog( 1020): !@Sync 7
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/AlarmManager( 1020): waitForAlarm result :4
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
,I/BooksSync( 6004): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6004): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1713): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1713): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1713): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1713): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1713): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6004): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6004): Soft error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6004): Sync error
E/BooksSync( 6004): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6004): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6004): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 257586, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,E/Watchdog( 1020): !@Sync 8
,I/PowerManagerService( 1020): [PWL] Off : 180s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged,
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK,
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
,E/Watchdog( 1020): !@Sync 9
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  332): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  332): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1020): Plugged,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
V/EmergencyMode( 1435): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1435): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2667): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2667): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1020): initializing...
,I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1020): !@Sync 10,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF,
,I/jxcore-log( 6080): --= Surplus to requirements =--
I/jxcore-log( 6080): 
,I/jxcore-log( 6080): ****TEST TOOK:  ms ****
I/jxcore-log( 6080): 
I/jxcore-log( 6080): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6080): 
,D/AndroidRuntime( 6603): 
D/AndroidRuntime( 6603): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6603): CheckJNI is OFF
,D/AndroidRuntime( 6603): readGMSProperty: start
D/AndroidRuntime( 6603): readGMSProperty: already setted!!
D/AndroidRuntime( 6603): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6603): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6603): readGMSProperty: end
D/AndroidRuntime( 6603): addProductProperty: start
,E/AffinityControl( 6603): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6603): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1020): START PACKAGE DELETE: observer{430891802}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg,
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1020): Killing 6080:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1020): Skipping PackageSetting{7b7f6ef com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{2308f477 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1020): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1020): Focus left window: 6080,
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focused application released,
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,W/WindowManager( 1020): Failed looking up window
W/WindowManager( 1020): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@2e1a0b98 does not exist
W/WindowManager( 1020): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
W/WindowManager( 1020): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
W/WindowManager( 1020): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
W/WindowManager( 1020): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:566)
I/WindowState( 1020): WIN DEATH: null
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4022): Explicit concurrent mark sweep GC freed 3164(190KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 904us total 31.945ms
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1834): mOCRHelper is null
,W/GeofencerStateMachine( 1684): Ignoring removeGeofence because network location is disabled.
,I/art     ( 5959): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 943us total 47.077ms
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:32:35 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3758): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6616): MountEmulatedStorage()
I/libpersona( 6616): KNOX_SDCARD checking this for 10090
E/Zygote  ( 6616): v2
I/libpersona( 6616): KNOX_SDCARD not a persona
I/SELinux ( 6616): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6616 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6616): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6616): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6616): TimaSignature is unavailable
,D/ActivityThread( 6616): Added TimaKeyStore provider
,I/art     (  314): Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.050ms total 31.057ms,
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.770ms
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onCreate()
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 17.296ms
,I/KLMS-2.5.123: ( 3758): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/RegisteredServicesCache( 1459): empty dynamic service
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/KLMS-2.5.123: ( 3758): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 41313(3MB) AllocSpace objects, 67(1081KB) LOS objects, 33% free, 24MB/36MB, paused 3.472ms total 211.535ms
,I/art     ( 1020): WaitForGcToComplete blocked for 149.381ms for cause Explicit
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/elm:15121( 6616): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6616): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6616): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6616): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/elm:15121( 6616): ElmAgentService : onCreate()
,D/elm:15121( 6616): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6616): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6616): MDMBridge.getInstance()
D/elm:15121( 6616): MDMBridge.getAllLicenseInfoFromSDK()
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,D/elm:15121( 6616): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): listeningToPackageRemoved().END
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3758): KLMSIntentService(): onDestroy()
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6616): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 5825:com.wsomacp/u0a23 (adj 15): empty #31
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 11676(577KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.386ms total 177.267ms
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
,D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 5666): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5666): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5666): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5666): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 6634): MountEmulatedStorage()
,E/Zygote  ( 6634): v2
I/libpersona( 6634): KNOX_SDCARD checking this for 10029
I/libpersona( 6634): KNOX_SDCARD not a persona
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6634 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1020): delete codoeFile: 
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1020): result of delete: 1{430891802}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6634): TimaSignature is unavailable
,D/ActivityThread( 6634): Added TimaKeyStore provider
,D/AndroidRuntime( 6603): Shutting down VM
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_5825/cgroup.procs: No such file or directory
,I/FeatureConfig( 6634): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5770): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5770): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1020): Killing 5848:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,I/PackagesMonitor( 4976): PackagesMonitor onReceive :com.test.thalitest
,W/ResourcesManager( 6634): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6634): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6634): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 6653): MountEmulatedStorage(),
I/libpersona( 6653): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6653): v2
I/libpersona( 6653): KNOX_SDCARD not a persona
I/SELinux ( 6653): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6653): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6653 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
E/SELinux ( 6653): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6634): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_10048/pid_5848/cgroup.procs: No such file or directory
,W/ResourcesManager( 6634): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6653): TimaSignature is unavailable
,D/ActivityThread( 6653): Added TimaKeyStore provider
,W/ResourcesManager( 6634): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6634): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6634): system/finder_cp/cpdata.xml file not found
,W/ResourcesManager( 6653): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6653): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6653): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6653): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,W/art     ( 6603): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,D/Mms/MmsApp( 6653): [start]    onCreate() consume time = 0.0
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
