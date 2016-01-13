#### Test 55902202f27eba5_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
I/PowerManagerService( 1020): [PWL] Off : 75s ago
,--------- beginning of main
D/AndroidRuntime( 6104): 
D/AndroidRuntime( 6104): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6104): CheckJNI is OFF
D/AndroidRuntime( 6104): readGMSProperty: start
D/AndroidRuntime( 6104): readGMSProperty: already setted!!
D/AndroidRuntime( 6104): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6104): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6104): readGMSProperty: end
D/AndroidRuntime( 6104): addProductProperty: start
E/AffinityControl( 6104): AffinityControl: registerfunction enter
D/AndroidRuntime( 6104): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1020): inState():  stateMachine is null !!
I/PersonaManagerService( 1020): PersonaId don't exist
I/ActivityManager( 1020): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1020): mDVFSHelper.acquire()
D/FocusedStackFrame( 1020): Set to : 0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1020): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1020): *FMB* installDecor flags : 25362712
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/ActivityManager( 1020): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6116 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/libpersona( 6116): KNOX_SDCARD checking this for 10338
D/InputDispatcher( 1020): Focused application set to: xxxx
I/libpersona( 6116): KNOX_SDCARD not a persona
D/InputDispatcher( 1020): Focus left window: 1481
E/Zygote  ( 6116): MountEmulatedStorage()
E/Zygote  ( 6116): v2
D/AndroidRuntime( 6104): Shutting down VM
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1020): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
D/ActivityThread( 6116): Added TimaKeyStore provider
V/WindowManager( 1020): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1020): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1020): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1020):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  257): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1481): updateVisibility : ActivityRecord{165f9719 token=android.os.BinderProxy@aaf1b3b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1481): onTrimMemory. Level: 20
I/WebViewFactory( 6116): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6116): Time to load native libraries: 1 ms (timestamps 2963-2964)
I/LibraryLoader( 6116): Expected native library version number "",actual native library version number ""
W/art     ( 6104): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6116): Binding Chromium to main looper Looper (main, tid 1) {1f0c85a6}
,I/LibraryLoader( 6116): Expected native library version number "",actual native library version number ""
,I/chromium( 6116): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6116): Initializing chromium process, singleProcess=true
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6116): ApplicationContext is null in ApplicationStatus
,W/chromium( 6116): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6116): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6116): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6116): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6116): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6116): Local Branch: 
I/Adreno-EGL( 6116): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6116): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6116):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6116): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6116): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6116): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6116): CordovaWebView is running on device made by: samsung
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6116): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1020): Activity pause timeout for ActivityRecord{4ddca59 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6116): Render dirty regions requested: true
,D/ActivityManager( 1020): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1020): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1020): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1020): handleActiveUserChange for user 0
,D/PersonaManagerService( 1020): getPersonasForUser(): returning null!
,W/chromium( 6116): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6116): updateVisibility : ActivityRecord{30daef73 token=android.os.BinderProxy@3ba880ad {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6116): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6116): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1020): Focus entered window: 6116
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6116): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6116): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6116): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6116): Enabling debug mode 0
,D/InputMethodManagerService( 1020): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1180): Icon Only,
D/PanelView( 1180): There is/are notification(s) 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6116): showStatusIcon on inactive InputConnection
,I/Timeline( 6116): Timeline: Activity_idle id: android.os.BinderProxy@3ba880ad time:153495
,I/ActivityManager( 1020): Displayed Component not be shown by security: +673ms (total +37s170ms)
,W/ActivityManager( 1020): mDVFSHelper.release()
I/Timeline( 1020): Timeline: Activity_windows_visible id: ActivityRecord{4ddca59 u0 com.test.thalitest/.MainActivity t20} time:153500
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  257): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1882): getCurrentCandidateView,
,D/SamsungIME( 1882): Dismiss ExpandCandiate
,I/SamsungIME( 1882): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1882): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1882): KeybaordView init() : load resources
,I/SamsungIME( 1882): getCurrentKeyboard
I/SamsungIME( 1882): getTextKeyboard
,D/SamsungIME( 1882): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/BindingManager( 6116): Cannot call determinedVisibility() - never saw a connection for the pid: 6116
,D/JsMessageQueue( 6116): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6116): JniHelper::setJavaVM(0xb7b3c448), pthread_self() = -1207349272
,D/JX-Cordova( 6116): jxcore cordova android initializing
,E/SMD     (  288): DCD OFF
,W/jxcore-log( 6116): Initializing JXcore engine
W/jxcore-log( 6116): JXcore engine is ready
,W/jxcore-log( 6116): Starting JXcore engine
,E/audit   ( 1877): type=1400 msg=audit(1452699390.467:205): avc:  denied  { ioctl } for  pid=6116 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1877):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1877): type=1300 msg=audit(1452699390.467:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bef4dd58 items=0 ppid=303 ppcomm=main pid=6116 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1877): type=1320 msg=audit(1452699390.467:205): 
,W/jxcore-log( 6116): Platform android
W/jxcore-log( 6116): 
W/jxcore-log( 6116): Process ARCH arm
W/jxcore-log( 6116): 
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6116): JXcore Cordova bridge is ready!
I/jxcore-log( 6116): 
,W/jxcore-log( 6116): JXcore engine is started
,I/chromium( 6116): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6116): Toggling radios to true
I/jxcore-log( 6116): 
,D/BluetoothAdapter( 6116): enable()
,D/BluetoothAdapter( 6116): enable(): BT is already enabled..!
,D/SecContentProvider( 1020): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1020): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1020): mCursor = null
,D/WifiService( 1020): setWifiEnabled: true pid=6116, uid=10338
,W/ActivityManager( 1020): Permission Denial: getCurrentUser() from pid=6116, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1020): Failed getting userId using ActivityManagerNative
W/WifiService( 1020): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6116, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1020): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1020): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1020): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1020): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1020): name = wifi_on
,I/WifiService( 1020): disconnect: pid=6116, uid=10338
,I/wpa_supplicant( 1392): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6116): Radios toggled
I/jxcore-log( 6116): 
,I/jxcore-log( 6116): My device name is: samsung-SM-A300FU
I/jxcore-log( 6116): 
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1020): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1392): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1392): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1392): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1392): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1392): Cmd 35605 not handled
,E/WifiStateMachine( 1020): WifiStateMachine: Leaving Connected state,
I/wpa_supplicant( 1392): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1392): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1392): P2P: Current p2p state = IDLE,
I/wpa_supplicant( 1392): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1392): First Scan Start
I/wpa_supplicant( 1392): Scan requested (ret=0) - scan timeout 30 seconds
,I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/Tethering( 1020): InitialState.processMessage what=4
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1020): interfaceLinkStateChanged wlan0, false,
,D/Tethering( 1020): interfaceStatusChanged wlan0, false,
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
,E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1020): No numeric data,
,D/Tethering( 1020): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1020): clearTetheredNotification()
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
,E/WifiNative-wlan0( 1020): do suspend true
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
D/HotspotTile( 1180): updateTetherState():false, false
D/CommandListener(  277): Clearing all IP addresses on wlan0
,V/NetworkStats( 1020): performPollLocked() took 8ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,V/NativeCrypto( 1729): Read error: ssl=0xb8080628: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1020): Start Disconnecting Watchdog 1
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/wpa_supplicant( 1392): wlan0: Setting scan request: 0 sec 0 usec
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
E/WifiNative-wlan0( 1020): do suspend true
I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/WifiP2pService( 1020): InactiveState{ what=143375 }
,I/rmt_storage(  267): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb888b7c8
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
I/rmt_storage(  267): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  267): wakelock acquired: 1, error no: 42
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1198999416)
,V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xb8080628: I/O error during system call, Broken pipe
,D/ConnectivityService( 1020): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-3ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1020): Tagging socket 330 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1020): Untagging socket 330
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #8
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1646): Message received 5007
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1198999416) wakelock released: 1, error no: 0
I/rmt_storage(  267): 
,I/rmt_storage(  267): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb888b7c8
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  277): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  277): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
D/ConnectivityService( 1020): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
D/ConnectivityService( 1020): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524292
D/ConnectivityService( 1020): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1020): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1020): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1462): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
,V/NetworkStats( 1020): updateIfacesLocked()
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/ConnectivityService( 1020): nai.networkMonitor.doQuit()
V/NetworkStats( 1020): performPollLocked() took 4ms
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): doQuit - quitNow()
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
D/WifiNetworkAgent( 1020): NetworkAgent: NetworkAgent channel lost
D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #9
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
,I/Hs20UtilService( 1646): Message received 5007
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1317): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3,
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ApplicationPolicy( 1020): updateDataUsageMap
D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_PushUtil( 5706): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5706): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5706): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5706): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
I/PCWCLIENTTRACE_SYSTEMReceiver( 5706): noConnectivity : true
I/ActivityManager( 1020): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6190 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6190): MountEmulatedStorage()
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD checking this for 10108
I/libpersona( 6190): KNOX_SDCARD not a persona
I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
D/ActivityThread( 6190): Added TimaKeyStore provider
I/MusicStore( 6190): Database version: 120
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/SSRM:n  ( 1020): SIOP:: AP = 290
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6190): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ResourcesManager( 6190): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6190): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6190): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
I/wpa_supplicant( 1392): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 1392): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1392): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1392): Trying to associate with  'G700'
I/wpa_supplicant( 1392): Re-associate with C0.AA.48
I/wpa_supplicant( 1392): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/SMD     (  288): DCD OFF
D/WifiMonitor( 1020): didn't find BSSID Trying to associate with SSID 'NG700'
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
W/ActivityThread( 6190): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6190): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a338e7f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6190): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6190): GMSCore installation verified
I/ConfigStore( 6190): Config Database version: 1
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
E/wpa_supplicant( 1392): Cmd 35605 not handled
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1392): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1392): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1392): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1392): Associated with C0.AA.48
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1392): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1392): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, false
D/Tethering( 1020): interfaceStatusChanged wlan0, false
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
E/Tethering( 1020): No numeric data
D/Tethering( 1020): sendTetherStateChangedBroadcast 1, 0, 0
I/wpa_supplicant( 1392): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1020): clearTetheredNotification()
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
I/wpa_supplicant( 1392): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1392): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1392): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1392): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1392): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1392): Blacklist: Clear (temp) 
I/wpa_supplicant( 1392): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1020): interfaceLinkStateChanged wlan0, true
D/Tethering( 1020): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1020): interfaceLinkStateChanged wlan0, true
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
D/HotspotTile( 1180): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1180): updateTetherState():false, false
V/NetworkStats( 1020): performPollLocked() took 4ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [50]
E/WifiConfigStore( 1020): setLastSelectedConfiguration -1
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1020): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1020): updateNetworkInfo()
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/WifiConfigStore( 1020): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
I/AudioService( 1020): getStreamVolume 3 index 70
I/MediaRouter( 6190): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/CommandListener(  277): Setting iface cfg
E/WifiStateMachine( 1020): Start Dhcp Watchdog 2
V/MusicLeanback( 6190): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
E/WifiNative-wlan0( 1020): do suspend false
D/SecContentProvider2( 1020): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1020): mCursor = null
D/WifiP2pService( 1020): InactiveState{ what=143375 }
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
D/WifiDisplayAdapter( 1020): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6217): MountEmulatedStorage()
E/Zygote  ( 6217): v2
I/libpersona( 6217): KNOX_SDCARD checking this for 10001
I/libpersona( 6217): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6217 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/GHttpClientFactory( 6190): Using our fixed implementation of GMSCore's GoogleHttpClient
D/TimaKeyStoreProvider( 6217): TimaSignature is unavailable
D/ActivityThread( 6217): Added TimaKeyStore provider
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
I/GoogleURLConnFactory( 6190): Using platform SSLCertificateSocketFactory
W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/ActivityManager( 1020): Killing 5624:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6236): MountEmulatedStorage()
E/Zygote  ( 6236): v2
I/libpersona( 6236): KNOX_SDCARD checking this for 1000
I/libpersona( 6236): KNOX_SDCARD not a persona
I/SELinux ( 6236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6236): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1020): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6236 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 4179:com.sec.spp.push/u0a32 (adj 15): empty #31
I/art     (  303): Explicit concurrent mark sweep GC freed 8709(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 27.904ms
E/dhcpcd  ( 6247): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6247): version 5.5.6 starting
E/dhcpcd  ( 6247): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 18.126ms
D/TimaKeyStoreProvider( 6236): TimaSignature is unavailable
D/ActivityThread( 6236): Added TimaKeyStore provider
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 678us total 18.334ms
,I/dhcpcd  ( 6247): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6247): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6247): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6247): bssid match
I/dhcpcd  ( 6247): wlan0: rebinding lease of 192.168.1.132
,I/DIAGMON_AGENT( 6236): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1020): failed to open /acct/uid_10139/pid_5624/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_4179/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6236): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
I/DIAGMON_AGENT( 6236): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6236): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6258 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5193:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,E/Zygote  ( 6258): MountEmulatedStorage()
I/libpersona( 6258): KNOX_SDCARD checking this for 10008
E/Zygote  ( 6258): v2
I/libpersona( 6258): KNOX_SDCARD not a persona
,I/SELinux ( 6258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6258): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6258): TimaSignature is unavailable
,D/ActivityThread( 6258): Added TimaKeyStore provider
,I/ActivityManager( 1020): Killing 5669:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:36:33 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6275): MountEmulatedStorage()
,E/Zygote  ( 6275): v2
I/libpersona( 6275): KNOX_SDCARD checking this for 10031
I/libpersona( 6275): KNOX_SDCARD not a persona
,I/SELinux ( 6275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6275 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 6275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6275): TimaSignature is unavailable
,D/ActivityThread( 6275): Added TimaKeyStore provider
,I/SO_AGENT( 6275): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5724): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5901): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5901): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5901): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5901): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5724): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5724): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SA      ( 5901): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5901): [OR] == isSIMCardReady false ==
,E/DBG_POLICYDM( 5724): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/SA      ( 5901): [SCU] == networkStateCheck == false
,I/SA      ( 5901): [OR] onReceive END
E/DBG_POLICYDM( 5724): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/ActivityManager( 1020): Killing 5281:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1572): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1572): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6292): MountEmulatedStorage()
,E/Zygote  ( 6292): v2
I/libpersona( 6292): KNOX_SDCARD checking this for 10121
I/SELinux ( 6292): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/libpersona( 6292): KNOX_SDCARD not a persona
I/ActivityManager( 1020): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6292 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 6292): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6292): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6292): TimaSignature is unavailable
,D/ActivityThread( 6292): Added TimaKeyStore provider
,W/ResourcesManager( 6292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6292): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6292): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6292): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,W/libprocessgroup( 1020): failed to open /acct/uid_10032/pid_5193/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_1000/pid_5669/cgroup.procs: No such file or directory
,I/QuickConnect( 6292): PeriphStartReceiver.onReceive - no need to start
,W/libprocessgroup( 1020): failed to open /acct/uid_10014/pid_5281/cgroup.procs: No such file or directory
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6307): MountEmulatedStorage(),
I/ActivityManager( 1020): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6307 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
E/Zygote  ( 6307): v2
I/libpersona( 6307): KNOX_SDCARD checking this for 10141,
I/SELinux ( 6307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6307): KNOX_SDCARD not a persona
,I/ActivityManager( 1020): Killing 5692:com.google.android.apps.docs/u0a87 (adj 15): empty #31,
,I/SELinux ( 6307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6307): TimaSignature is unavailable
,D/ActivityThread( 6307): Added TimaKeyStore provider
,W/ResourcesManager( 6307): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6307): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6307): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6307): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/BadgeProvider( 5817): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5817): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1481): reloadBadges entered.
,D/BadgeProvider( 5817): sendNotify, [notify] : null
D/BadgeProvider( 5817): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5817): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5817): update, [UpdateCount] : 1
,W/libprocessgroup( 1020): failed to open /acct/uid_10087/pid_5692/cgroup.procs: No such file or directory
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1020): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6331 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6331): MountEmulatedStorage()
I/libpersona( 6331): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6331): v2
I/libpersona( 6331): KNOX_SDCARD not a persona
,I/SELinux ( 6331): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Killing 5291:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31,
,I/SELinux ( 6331): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6331): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6331): TimaSignature is unavailable
,D/ActivityThread( 6331): Added TimaKeyStore provider
,D/SecurityLogAgent( 6331): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6331): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6331): StateMachine : Current State = 1
,D/SecurityLogAgent( 6331): StateMachine : Changed Current State = 1
,I/ActivityManager( 1020): Killing 5760:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2053): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2053): num queued entries: 0
,I/iu.UploadsManager( 2053): num updated entries: 0
,I/iu.SyncManager( 2053): NEXT; no task
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1020): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5116): connection state changed from CONNECTED to DISCONNECTED
,E/Zygote  ( 6350): MountEmulatedStorage(),
I/libpersona( 6350): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6350): v2
,I/libpersona( 6350): KNOX_SDCARD not a persona
I/SELinux ( 6350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1020): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6350 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6350): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1020): failed to open /acct/uid_10029/pid_5291/cgroup.procs: No such file or directory
,W/libprocessgroup( 1020): failed to open /acct/uid_10148/pid_5760/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6350): TimaSignature is unavailable
,D/ActivityThread( 6350): Added TimaKeyStore provider
,E/SPPClientService( 6350): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6350): [SystemStateMoniter] Current Time : 158679
,E/SPPClientService( 6350): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6350): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6350): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6350): PushLog.txt file is not deleted.
,D/SPPClientService( 6350): PushLog.txt file is not deleted.
,D/SPPClientService( 6350): ============PushLog. stop!
,E/Zygote  ( 6367): MountEmulatedStorage(),
E/Zygote  ( 6367): v2
I/libpersona( 6367): KNOX_SDCARD checking this for 10110
I/libpersona( 6367): KNOX_SDCARD not a persona
,I/SELinux ( 6367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6367 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1020): Killing 5783:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/SELinux ( 6367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6367): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimaKeyStoreProvider( 6367): TimaSignature is unavailable
,D/ActivityThread( 6367): Added TimaKeyStore provider
,E/SPPClientService( 6350): [[SystemStateMonitorService]] No Active Internet
,W/libprocessgroup( 1020): failed to open /acct/uid_10152/pid_5783/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6247): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,I/GAv4    ( 6367): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:,
I/GAv4    ( 6367):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6367):   adb logcat -s GAv4
W/ContextImpl( 6367): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6367): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6367): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/dhcpcd  ( 6247): wlan0: leased 192.168.1.132 for 86400 seconds
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6367): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6367): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6367): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6367): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,E/WifiNative-wlan0( 1020): do suspend true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1020): InactiveState{ what=143375 },
E/WifiStateMachine( 1020): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiP2pService( 1020): P2pEnabledState{ what=143375 }
E/WifiStateMachine( 1020): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1020): callSECApiInt - ID [210]
,E/ConnectivityService( 1020): updateNetworkInfo()
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1020): Adding iface wlan0 to network 503
,I/WebViewFactory( 6367): Loading com.google.android.webview version 44.0.2403.117 (code 240311700),
,D/ConnectivityService( 1020): Adding Route [fe80::/64 -> :: wlan0] to network 503
I/ServiceManager(  314): Waiting for service AtCmdFwd...
D/WifiWatchdogStateMachine( 1020): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.SingDnsChecker( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1020): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1020): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1020): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1020): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1020): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1020): LTETest block dns file not exists
,V/AlarmManager( 1020): waitForAlarm result :4
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1020): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/LibraryLoader( 6367): Time to load native libraries: 2 ms (timestamps 9312-9314),
I/LibraryLoader( 6367): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6367): Binding Chromium to main looper Looper (main, tid 1) {8de2454}
,E/ConnectivityService( 1020): updateNetworkInfo()
,I/LibraryLoader( 6367): Expected native library version number "",actual native library version number ""
,E/ConnectivityService( 1020): updateNetworkInfo()
D/ConnectivityService( 1020): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1020): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 1000
I/chromium( 6367): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService( 1020):    accepting network in place of null
,D/WIFI_P2P( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
E/CSLegacyTypeTracker( 1020): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1020): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1462): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1180): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WIFI    ( 1020): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/WifiTrafficPoller( 1020): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1020): mBoosterFLAG : 0
I/WifiTrafficPoller( 1020): current booster mode : FullMode
D/WifiNative-wlan0( 1020): callSECApiVoid - ID [212]
,I/BrowserStartupController( 6367): Initializing chromium process, singleProcess=true
,W/art     ( 6367): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6367): ApplicationContext is null in ApplicationStatus
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1020): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1020): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1020): MasterInitialState.processMessage what=3
,V/NetworkStats( 1020): updateIfacesLocked()
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
V/NetworkStats( 1020): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1020): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1020): UpdateStatsForKnox main else ---
,D/EntConnectivity( 1020): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,V/NetworkStats( 1020): performPollLocked() took 6ms
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,V/NetworkStats( 1020): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1020): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/chromium( 6367): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6367): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6367): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6367): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6367): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6367): Local Branch: 
I/Adreno-EGL( 6367): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6367): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6367):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/System.out( 1020): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:36:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699394674], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699394660]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
,D/ConnectivityService( 1020): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1180): EthernetConnected: false
,D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1180): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1180): updateDataNetType()
D/StatusBar.NetworkController( 1180): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1180): updateLTEICONDataNetType:0
,I/NSApplication( 6367): Starting up...
,D/StatusBar.NetworkController( 1180): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1180): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1180): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1180): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1180): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/AudioManagerAndroid( 6367): Requires BLUETOOTH permission
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6449): MountEmulatedStorage()
,E/Zygote  ( 6449): v2
I/libpersona( 6449): KNOX_SDCARD checking this for 10077
I/libpersona( 6449): KNOX_SDCARD not a persona
,I/SELinux ( 6449): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1020): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6449 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1020): Killing 5659:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 6449): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6449): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6449): TimaSignature is unavailable
,D/ActivityThread( 6449): Added TimaKeyStore provider
,D/CountryDetector( 1020): No listener is left
,W/libprocessgroup( 1020): failed to open /acct/uid_10041/pid_5659/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6009): notifyNetworkActivated
,W/ContextImpl( 6009): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1020): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ConnectivityService( 1020): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/hcjo    ( 6009): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6009): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6009): exit::IDLE
D/InitializeManagerStateMachine( 6009): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6009): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6009): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6009): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): entry::SUCCESS
D/hcjo    ( 6009): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6009): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6009): exit::SUCCESS
D/InitializeManagerStateMachine( 6009): entry::IDLE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #10
,I/Hs20UtilService( 1646): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/ActivityManager( 1020): Killing 5808:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/GpsLocationProvider( 1020): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6190): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #11
,I/Hs20UtilService( 1646): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/libprocessgroup( 1020): failed to open /acct/uid_10042/pid_5808/cgroup.procs: No such file or directory
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 70153(3MB) AllocSpace objects, 9(196KB) LOS objects, 33% free, 24MB/36MB, paused 2.569ms total 153.496ms
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #12
,I/Hs20UtilService( 1646): Message received 5007
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1646): Starting #13
,I/Hs20UtilService( 1646): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1020): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1020): mCursor = null
,D/SecContentProvider2( 1020): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1020): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5706): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5706): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5706): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5706): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1020): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1020): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1020): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6190): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 1020): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020
,I/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6236): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6236): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SRIB_DCS( 1180): log_dcs ThreadedRenderer::initialize entered! 
,E/SMD     (  288): DCD OFF
,I/DBG_POLICYDM( 5724): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5724): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5724): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 5724): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/FOTA_Client( 6258): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6258): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:36:35 GMT+01:00 2016
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService( 1020): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503],
,D/ConnectivityService( 1020): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().START
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524295
,I/KLMS-2.5.123: ( 3656): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService( 1020): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/KLMS-2.5.123: ( 3656): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3656): StateImplV2(): networkChangeListener().END
,D/GCM     ( 1729): Connected
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5724): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/GCM     ( 1729): Message class com.google.f.a.a.p
,I/SA      ( 5901): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5901): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5901): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5724): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5724): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5901): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5901): [OR] == isSIMCardReady false ==
,I/SA      ( 5901): [SCU] == networkStateCheck == true
,I/SA      ( 5901): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5901): isChinaCountryCode : false
I/SA      ( 5901): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5901): [OR] == networkStateCheck true ==
,E/DBG_POLICYDM( 5724): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5901): [OR] GetMyCountryZoneTask
I/DBG_POLICYDM( 5724): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5901): [OR] onReceive END
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5901): [SRS] prepareGetMyCountryZone
,D/accuweather( 1572): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5724): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1572): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
D/accuweather( 1572): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1572): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1572): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/SA      ( 5901): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5901): [SSP] query invoked
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/accuweather( 1572): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5724): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/SecContentProvider2( 1020): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1020): mCursor = null
,D/accuweather( 1572): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 5901): [TPMU] GetMccFromDB : null
I/SA      ( 5901): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5901): [TPM] isNoProxy(default) : true
,E/DBG_POLICYDM( 5724): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
D/QuickConnect( 6292): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6292): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6292): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,D/RCPManagerService( 1020): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5724): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5724): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,E/File    ( 5901): fail readDirectory() errno=2
,D/SecurityLogAgent( 6331): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6331): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6331): StateMachine : Current State = 1
,D/SecurityLogAgent( 6331): StateMachine : Changed Current State = 1
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1020): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1020): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1020): Tagging socket 345 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
,I/iu.Environment( 2053): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2053): num queued entries: 0
,I/iu.UploadsManager( 2053): num updated entries: 0
,I/qtaguid ( 1020): Untagging socket 345
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:36:35 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699395748], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699395732]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1020): Validated
D/ConnectivityService( 1020): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1020): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1020): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1180): CM callback handler got msg 524290
,I/iu.SyncManager( 2053): NEXT; no task
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6350): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6350): [SystemStateMoniter] Current Time : 160556
,E/SPPClientService( 6350): [SystemStateMoniter] No Connect : false
,I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5116): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 6009): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6009): execute::IDLE:EXECUTE
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/System.out( 5116): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/InitializeManagerStateMachine( 6009): exit::IDLE
D/InitializeManagerStateMachine( 6009): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6009): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6009): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6009): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6009): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6009): entry::SUCCESS
D/hcjo    ( 6009): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6009): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6009): exit::SUCCESS
D/InitializeManagerStateMachine( 6009): entry::IDLE
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/Babel   ( 5116): connection state changed from DISCONNECTED to CONNECTED
,W/Kids    ( 2053): [AccountUtils] Account not ready
W/Kids    ( 2053): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2053): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2053): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2053): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2053): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2053): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2053): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2053): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2053): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2053): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2053): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2053): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5901): [RC New] Execute method=[GET] start
,I/SA      ( 5901): [RC New] Security=[true]
,I/System.out( 5901): Thread-1005(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5901): Thread-1005(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5901): Thread-1005(ApacheHTTPLog):isShipBuild true
I/System.out( 5901): Thread-1005(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5901): Thread-1005(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10036
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/SA      ( 5901): [RC New] [v2liruge] api execute + 605
,I/SA      ( 5901): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5901): AsyncTask #1 calls detatch()
,I/SA      ( 5901): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5901): [OCP] update openData : PL
,I/SA      ( 5901): [TPMU] getNetworkMcc : 
,I/SA      ( 5901): [SCU] saveMccToPreferece Start
I/SA      ( 5901): [SCU] RegionMCC : 260
I/SA      ( 5901): [SSP] query invoked
,I/SA      ( 5901): [TPMU] GetMccFromDB : null
,I/SA      ( 5901): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5901): [SCU] saveMccToPreferece End
,I/SA      ( 5901): [RC New] executeRequest [v2liruge] end. 669
I/SA      ( 5901): [RC New] Execute end
,I/SA      ( 5901): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5901): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6247): wlan0: sending IPv6 Router Solicitation
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
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
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 3417): callingUid 10011, callindPid: 3417
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6190): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6190): Stop autocaching.
,E/GmsUtils( 6190): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6190): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  288): DCD OFF,
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  257): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1020): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1020) eventTime = 163670
,D/PowerManagerService( 1020): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1020 (0x0)
,D/PowerManagerService( 1020): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1020, ws=WorkSource{10049}) (elapsedTime=3487)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5706): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5706): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5706): [GetString-S]
,I/ReactiveServiceManager( 5706): Supported : 1
,D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1020): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1020): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1020): handleString: Failed to handle string(-4)
E/terrier ( 1020): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5706): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5706): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5706): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5706): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5706): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5706): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6247): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,I/jxcore-log( 6116): Test app app.js loaded
I/jxcore-log( 6116): 
,I/chromium( 6116): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SSRM:n  ( 1020): SIOP:: AP = 310
,V/AlarmManager( 1020): waitForAlarm result :4
,E/Watchdog( 1020): !@Sync 5
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5364): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5364): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5364): [1] 5.onFinished: Scheduling replication attempt 5.
,V/AlarmManager( 1020): waitForAlarm result :4
,D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,E/SMD     (  288): DCD OFF
,D/GCM     ( 1729): Connected
,W/ActivityManager( 1020): userId = 0, bbcId = -10000,
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1729): Message class com.google.f.a.a.p
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6009): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6009): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6009): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6009): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6009): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6009): entry::IDLE
,I/dhcpcd  ( 6247): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6247): wlan0: no IPv6 Routers available
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6009): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6009): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6009): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6009): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6009): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6009): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6009): entry::IDLE
,V/AlarmManager( 1020): waitForAlarm result :4
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1729): Vacuum at: now=1452699406992 tag=VacuumService
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,W/Uploader( 1729): No account for auth token provided
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1729): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1729): (HTTPLog)-Static: isShipBuild true
I/System.out( 1729): (HTTPLog)-Thread-208-743736627: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  277): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1729): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,I/qtaguid ( 1729): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011,
,E/SMD     (  288): DCD OFF
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729):  no longer exists, so no auth token.
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
,D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
E/Uploader( 1729): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1729): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1729): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1729): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1729): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1729): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1729): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1729): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1729): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 290
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  288): DCD OFF,
,I/PowerManagerService( 1020): [PWL] Off : 105s ago,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1020): waitForAlarm result :8
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 270
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5364): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5364): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5364): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 6
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,V/AlarmManager( 1020): waitForAlarm result :4
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF,
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  288): DCD OFF,
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1020): [PWL] Off : 140s ago
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF,
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/Watchdog( 1020): !@Sync 7
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  288): DCD OFF
,I/PowerManagerService( 1020): [PWL] Off : 180s ago
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/Watchdog( 1020): !@Sync 8
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1180): level :100 plugged : 2
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1020): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1180): handleTimeUpdate
,D/SecKeyguardClockView( 1180): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1180): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1180): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1180): *** don't update sliding image ***
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6038): Starting books sync for 61035162, extras: ade
,D/DateView( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1180): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1180): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6038): GmsCore Version = 7.8.99 (2134222-434)
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 40406(2MB) AllocSpace objects, 46(745KB) LOS objects, 33% free, 24MB/36MB, paused 2.429ms total 161.012ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1020): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1020): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1180): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1180): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1180): Icon Only
I/StatusBar( 1180): Icon Only
,D/PanelView( 1180): There is/are notification(s) 
D/PanelView( 1180): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6038): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6038): Soft error
E/BooksSync( 6038): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6038): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6038): Sync error
E/BooksSync( 6038): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6038): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6038): Finished books sync
,D/SyncManager( 1020): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 271648, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1180): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1020): mCursor = null
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  288): DCD OFF
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.,
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 9
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,E/SMD     (  288): DCD OFF
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,I/ServiceManager(  314): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1020): Plugged
I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/SMD     (  288): DCD OFF
,W/Atfwd_Sendcmd(  314): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :4,
,I/PowerManagerService( 1020): [PWL] Off : 225s ago
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,E/SMD     (  288): DCD OFF
,V/AlarmManager( 1020): waitForAlarm result :8
,E/SMD     (  288): DCD OFF
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/TimaService( 1020): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1020): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1020): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1020): initializing...
,I/TLC_TIMA_PKM_initialize( 1020): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1020): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1020): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1020): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1020): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1020): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1020): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: ( 1020): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1020): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1020): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1020): Trustlet response is completed
,W/ContextImpl( 1020): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  288): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1020): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1020): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1020): SIOP:: AP = 260
,D/BatteryService( 1020): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1020): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1020): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1020): stay LED for fully charged
,D/BatteryService( 1020): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1020): Plugged
,I/MotionRecognitionService( 1020): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1180): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1180): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1180): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1180): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1180): level :100 plugged : 2
,E/Watchdog( 1020): !@Sync 10
,E/SMD     (  288): DCD OFF
,E/SMD     (  288): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1020): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  314): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  314): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/jxcore-log( 6116): --= Surplus to requirements =--
I/jxcore-log( 6116): 
,I/jxcore-log( 6116): ****TEST TOOK:  ms ****
I/jxcore-log( 6116): 
I/jxcore-log( 6116): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6116): 
,E/SMD     (  288): DCD OFF
,D/AndroidRuntime( 6596): 
D/AndroidRuntime( 6596): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6596): CheckJNI is OFF,
D/AndroidRuntime( 6596): readGMSProperty: start
D/AndroidRuntime( 6596): readGMSProperty: already setted!!
D/AndroidRuntime( 6596): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6596): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6596): readGMSProperty: end
D/AndroidRuntime( 6596): addProductProperty: start
,E/AffinityControl( 6596): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6596): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1020): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1020): START PACKAGE DELETE: observer{175989395}
D/PackageManager( 1020): pkg{<packageName>}
D/PackageManager( 1020): user{0}
D/PackageManager( 1020): caller{2000}
D/PackageManager( 1020): flags{3}
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1020): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1020): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1020): [MSG] DELETE_PACKAGE_AS_USER,
D/PackageManagerService( 1020): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1020): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1020): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1020): Killing 6116:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/WindowState( 1020): WIN DEATH: Window{2957f783 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1020): Focus left window: 6116,
W/PackageSettings( 1020): Skipping PackageSetting{2363ffdb com.example.hello/10346} due to missing metadata
,I/SurfaceFlinger(  257): id=13 Removed NainActivit (-2/8)
,D/PointerIcon( 1020): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1020): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{4ddca59 u0 com.test.thalitest/.MainActivity t20},
,W/ActivityManager( 1020): Spurious death for ProcessRecord{3c1df2d0 6116:com.test.thalitest/u0a338}, curProc for 6116: null
,I/ActivityManager( 1020): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,I/ActivityManager( 1020):   Force finishing activity ActivityRecord{4ddca59 u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1020): Duplicate finish request for ActivityRecord{4ddca59 u0 com.test.thalitest/.MainActivity t20 f}
,W/ActivityManager( 1020): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1020): Focused application released
,I/InputReader( 1020): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1882): mOCRHelper is null
,I/art     ( 4032): Explicit concurrent mark sweep GC freed 3212(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 746us total 36.217ms
,W/GeofencerStateMachine( 1794): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:39:21 GMT+01:00 2016
,I/art     ( 5993): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 704us total 79.113ms
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
,W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3656): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1020): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1020): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1020): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1020): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6609): MountEmulatedStorage()
,E/Zygote  ( 6609): v2
I/libpersona( 6609): KNOX_SDCARD checking this for 10090
I/libpersona( 6609): KNOX_SDCARD not a persona
,I/SELinux ( 6609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1020): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6609 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/art     ( 1462): Background sticky concurrent mark sweep GC freed 61055(3MB) AllocSpace objects, 9(144KB) LOS objects, 38% free, 5MB/8MB, paused 12.360ms total 85.302ms
D/TimaKeyStoreProvider( 6609): TimaSignature is unavailable
,D/ActivityThread( 6609): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3656): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/SecContentProvider2( 1020): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1020): mCursor = null
,I/KLMS-2.5.123: ( 3656): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 21939(1836KB) AllocSpace objects, 27(436KB) LOS objects, 33% free, 23MB/35MB, paused 8.928ms total 185.165ms
,I/art     ( 1020): WaitForGcToComplete blocked for 101.278ms for cause Explicit
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): listeningToPackageRemoved().START
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/EnterpriseDeviceManagerService( 1020): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1020): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1020): no available spell checker services found
,D/RCPManagerService( 1020): PackageReceiver onReceive()
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/HarmonyEASService( 1020): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15121( 6609): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6609): ELMEngine.ELMEngine( context ).
D/KnoxMUMContainerPolicy( 1020): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6609): MDMBridge.setEnterpriseBridge()
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6609): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6609): ElmAgentService : onCreate()
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15121( 6609): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/KLMS-2.5.123: ( 3656): KLMSIntentService(): onDestroy()
D/elm:15121( 6609): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6609): MDMBridge.getInstance()
D/elm:15121( 6609): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6609): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6609): ElmAgentService : onDestroy().
,I/ActivityManager( 1020): Killing 5845:com.wsomacp/u0a23 (adj 15): empty #31
,W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourceType( 1020): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1020): Explicit concurrent mark sweep GC freed 8998(408KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.171ms total 184.514ms
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1020): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1020): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1020): delete codoeFile: 
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AASAuninstall( 1020): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1020): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1020): result of delete: 1{175989395}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/AndroidRuntime( 6596): Shutting down VM
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/BackupManagerService( 1020): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1020): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,W/Resources( 1020): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,D/UsbSettingsManager( 1020): clearDefaults: com.test.thalitest
,V/ApplicationPolicy( 1020): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,I/CrashAnrDetector( 1020): onPackageRemoved : com.test.thalitest
,D/TaskPersister( 1020): removeObsoleteFile: deleting file=20_task.xml
,W/libprocessgroup( 1020): failed to open /acct/uid_10023/pid_5845/cgroup.procs: No such file or directory
,D/SSRM:aZ ( 1020): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1020): uID is 10338
V/EnterpriseBillingPolicy( 1020): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1020): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1020): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1020): getBillingProfileForVpnEngine - end - null
,I/PCWCLIENTTRACE_PushUtil( 5706): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5706): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5706): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5706): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6626): MountEmulatedStorage()
,E/Zygote  ( 6626): v2
I/libpersona( 6626): KNOX_SDCARD checking this for 10029
I/libpersona( 6626): KNOX_SDCARD not a persona
,I/SELinux ( 6626): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1020): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6626 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6626): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6626): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6626): TimaSignature is unavailable
,D/ActivityThread( 6626): Added TimaKeyStore provider
,I/SA      ( 5901): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5901): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/FeatureConfig( 6626): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false],
,I/ActivityManager( 1020): Killing 5862:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1020): userId = 0, bbcId = -10000
W/ActivityManager( 1020): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1020): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6626): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/PackagesMonitor( 4971): PackagesMonitor onReceive :com.test.thalitest
,W/ResourcesManager( 6626): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/art     ( 6596): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6626): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1020): failed to open /acct/uid_10048/pid_5862/cgroup.procs: No such file or directory
,W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1020): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6626): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6626): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 6646): MountEmulatedStorage()
,E/Zygote  ( 6646): v2
I/libpersona( 6646): KNOX_SDCARD checking this for 10041
I/libpersona( 6646): KNOX_SDCARD not a persona
I/SELinux ( 6646): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1020): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6646 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/SELinux ( 6646): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6646): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6626): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6626): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
,I/art     (  303): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 21.705ms
,D/TimaKeyStoreProvider( 6646): TimaSignature is unavailable
W/ResourcesManager( 6626): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
D/ActivityThread( 6646): Added TimaKeyStore provider
W/ResourcesManager( 6626): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 16.620ms
,W/ResourcesManager( 6626): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6626): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6646): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 19.140ms
W/GalaxyFinderApplication( 6626): system/finder_cp/cpdata.xml file not found
,D/Mms/MmsApp( 6646): [start]    onCreate() consume time = 0.0

```
