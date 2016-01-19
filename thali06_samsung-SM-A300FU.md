#### Test 564317025f150b2_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 6124): 
D/AndroidRuntime( 6124): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6124): CheckJNI is OFF
D/AndroidRuntime( 6124): readGMSProperty: start
D/AndroidRuntime( 6124): readGMSProperty: already setted!!
D/AndroidRuntime( 6124): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6124): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6124): readGMSProperty: end
D/AndroidRuntime( 6124): addProductProperty: start
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
E/AffinityControl( 6124): AffinityControl: registerfunction enter
D/AndroidRuntime( 6124): Calling main entry com.android.commands.am.Am
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
E/Zygote  ( 6136): MountEmulatedStorage()
E/Zygote  ( 6136): v2
I/libpersona( 6136): KNOX_SDCARD checking this for 10338
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
I/libpersona( 6136): KNOX_SDCARD not a persona
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6136 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1491
I/SELinux ( 6136): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 6124): Shutting down VM
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6136): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6136): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6136): TimaSignature is unavailable
D/ActivityThread( 6136): Added TimaKeyStore provider
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1491): updateVisibility : ActivityRecord{1b009dbb token=android.os.BinderProxy@3ad5b364 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1491): onTrimMemory. Level: 20
I/WebViewFactory( 6136): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6136): Time to load native libraries: 1 ms (timestamps 6853-6854)
I/LibraryLoader( 6136): Expected native library version number "",actual native library version number ""
W/art     ( 6124): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6136): Binding Chromium to main looper Looper (main, tid 1) {267e6a60}
I/LibraryLoader( 6136): Expected native library version number "",actual native library version number ""
I/chromium( 6136): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6136): Initializing chromium process, singleProcess=true
W/art     ( 6136): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6136): ApplicationContext is null in ApplicationStatus
W/chromium( 6136): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6136): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6136): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6136): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6136): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6136): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6136): Local Branch: 
I/Adreno-EGL( 6136): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6136): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6136):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/art     ( 6136): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6136): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6136): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6136): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6136): CordovaWebView is running on device made by: samsung
W/art     ( 6136): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6136): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{19499ca6 u0 com.test.thalitest/.MainActivity t20}
E/SMD     (  289): DCD OFF
D/OpenGLRenderer( 6136): Render dirty regions requested: true
D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
W/chromium( 6136): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6136): updateVisibility : ActivityRecord{11b27845 token=android.os.BinderProxy@3595b4af {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6136): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6136): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1016): Focus entered window: 6136
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 6136): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6136): Initialized EGL, version 1.4
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 6136): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6136): Enabling debug mode 0
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
I/ActivityManager( 1016): Displayed Component not be shown by security: +692ms (total +40s917ms)
W/ActivityManager( 1016): mDVFSHelper.release()
W/IInputConnectionWrapper( 6136): showStatusIcon on inactive InputConnection
I/Timeline( 6136): Timeline: Activity_idle id: android.os.BinderProxy@3595b4af time:157397
I/SamsungIME( 1850): getCurrentCandidateView
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{19499ca6 u0 com.test.thalitest/.MainActivity t20} time:157396
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SamsungIME( 1850): Dismiss ExpandCandiate
I/SamsungIME( 1850): getDebugLevel  : 0x4f4c
I/SamsungIME( 1850): getDebugLevel  : 0x4f4c
I/SamsungIME( 1850): KeybaordView init() : load resources
W/BindingManager( 6136): Cannot call determinedVisibility() - never saw a connection for the pid: 6136
I/SamsungIME( 1850): getCurrentKeyboard
I/SamsungIME( 1850): getTextKeyboard
D/SamsungIME( 1850): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6136): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6136): JniHelper::setJavaVM(0xb8683448), pthread_self() = -1195529824
D/JX-Cordova( 6136): jxcore cordova android initializing
I/io.jxcore.node.ConnectionHelper( 6136): Build version SDK_INT: 21
I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/jxcore-log( 6136): Initializing JXcore engine
W/jxcore-log( 6136): JXcore engine is ready
,W/jxcore-log( 6136): Starting JXcore engine
,E/audit   ( 1848): type=1400 msg=audit(1453190805.384:205): avc:  denied  { ioctl } for  pid=6136 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1848):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1848): type=1300 msg=audit(1453190805.384:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bed92d58 items=0 ppid=310 ppcomm=main pid=6136 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1848): type=1320 msg=audit(1453190805.384:205): 
,W/jxcore-log( 6136): Platform android
W/jxcore-log( 6136): 
,W/jxcore-log( 6136): Process ARCH arm
W/jxcore-log( 6136): 
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/jxcore-log( 6136): JXcore Cordova bridge is ready!,
I/jxcore-log( 6136): 
W/jxcore-log( 6136): JXcore engine is started
,I/Choreographer( 6136): Skipped 140 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6136): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,I/jxcore-log( 6136): Toggling radios to true,
I/jxcore-log( 6136): 
,D/BluetoothAdapter( 6136): enable()
,D/BluetoothAdapter( 6136): enable(): BT is already enabled..!
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: true pid=6136, uid=10338
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=6136, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1016): Failed getting userId using ActivityManagerNative,
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6136, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	,at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1016): name = wifi_on
I/WifiService( 1016): disconnect: pid=6136, uid=10338
,I/wpa_supplicant( 1395): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6136): Radios toggled
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): My device name is: samsung-SM-A300FU
I/jxcore-log( 6136): 
,I/wpa_supplicant( 1395): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1395): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1395): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1395): wlan0: State: DISCONNECTED -> DISCONNECTED
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
D/Tethering( 1016): InitialState.processMessage what=4
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1395): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1395): wlan0: Setting scan request: 0 sec 0 usec
E/wpa_supplicant( 1395): Cmd 35605 not handled
I/wpa_supplicant( 1395): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1395): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1395): First Scan Start
I/wpa_supplicant( 1395): Scan requested (ret=0) - scan timeout 30 seconds
E/Tethering( 1016): No numeric data
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false,
E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/HotspotTile( 1171): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1171): updateTetherState():false, false
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false,
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,V/NetworkStats( 1016): performPollLocked() took 4ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1710): Read error: ssl=0xb8b7dfb8: I/O error during system call, Connection timed out
,V/NativeCrypto( 1710): SSL shutdown failed: ssl=0xb8b7dfb8: I/O error during system call, Broken pipe,
,E/ConnectivityService( 1016): updateNetworkInfo()
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1016): Start Disconnecting Watchdog 1
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/wpa_supplicant( 1395): wlan0: Setting scan request: 0 sec 0 usec
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7f197c8
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1208903544)
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1016): Tagging socket 349 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1016, getuid(): 1000
,E/WifiNative-wlan0( 1016): do suspend true
,I/qtaguid ( 1016): Untagging socket 349
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2103): Starting #8
I/Hs20UtilService( 2103): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1208903544) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7f197c8
,E/Zygote  ( 6190): MountEmulatedStorage(),
I/libpersona( 6190): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6190): v2
I/libpersona( 6190): KNOX_SDCARD not a persona
I/SELinux ( 6190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6190 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/SELinux ( 6190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6190): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1469): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1469): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
V/NetworkStats( 1016): updateIfacesLocked()
D/Tethering( 1016): MasterInitialState.processMessage what=3
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1171): EthernetConnected: false
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1171): updateLTEICONDataNetType:0
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
V/NetworkStats( 1016): performPollLocked() took 5ms
D/SecContentProvider2( 1016): mCursor = null
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null,
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6190): TimaSignature is unavailable
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/ActivityThread( 6190): Added TimaKeyStore provider
,W/ResourcesManager( 6190): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,D/PhoneApp( 1469): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1469): FileWriteThread : threadType = 3
,I/Babel_SMS( 6190): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6190): MmsConfig.loadMmsSettings
I/Babel_SMS( 6190): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6190): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6190): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6190): MmsConfig.loadFromResources
,E/Babel_SMS( 6190): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6190): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  284): getCameraInfo: X
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6190): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6190): startup - clean
,I/Babel   ( 6190): deleted: false for 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/Hs20UtilService( 2103): Starting #9
,I/NearbySettings( 1301): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1301): MountReceiver.mPrefHandler - 7002
I/Hs20UtilService( 2103): Message received 5007
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
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6190): Unsupported mime audio/evrc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6190): Unsupported mime audio/qcelp
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/AudioCapabilities( 6190): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6190): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6190): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6190): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6190): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6190): Unsupported mime audio/evrc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1016): updateDataUsageMap
,W/VideoCapabilities( 6190): Unsupported mime video/wvc1
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6190): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6190): Unsupported mime video/wvc1
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6190): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6190): Unsupported mime video/mp43
,W/VideoCapabilities( 6190): Unsupported mime video/sorenson
,W/VideoCapabilities( 6190): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6190): Unsupported profile 4 for video/mp4v-es
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6190): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1016): Killing 5232:com.google.android.gm/u0a99 (adj 15): empty #31
I/vclib   ( 6190): onServiceConnected
W/Babel   ( 6190): Attempted to change video mute state without an active call.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10099/pid_5232/cgroup.procs: No such file or directory
,I/wpa_supplicant( 1395): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 1395): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1395): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1395): Trying to associate with  'G700'
,I/wpa_supplicant( 1395): Re-associate with C0.AA.48
I/wpa_supplicant( 1395): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5710): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5710): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5710): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5710): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1016): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5710): noConnectivity : true,
I/libpersona( 6235): KNOX_SDCARD checking this for 10108
E/Zygote  ( 6235): MountEmulatedStorage()
I/libpersona( 6235): KNOX_SDCARD not a persona
E/Zygote  ( 6235): v2
,I/SELinux ( 6235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6235 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6235): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6235): TimaSignature is unavailable
,D/ActivityThread( 6235): Added TimaKeyStore provider
,E/wpa_supplicant( 1395): Cmd 35605 not handled
I/wpa_supplicant( 1395): wlan0: State: ASSOCIATING -> ASSOCIATED
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1395): Associated with C0.AA.48
I/wpa_supplicant( 1395): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1395): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,E/Tethering( 1016): No numeric data
I/wpa_supplicant( 1395): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1395): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,I/wpa_supplicant( 1395): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1395): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1395): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1395): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1395): Blacklist: Clear (temp) 
I/wpa_supplicant( 1395): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
,D/Tethering( 1016): clearTetheredNotification()
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/HotspotTile( 1171): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1171): updateTetherState():false, false
,V/NetworkStats( 1016): performPollLocked() took 5ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,E/WifiNative-wlan0( 1016): do suspend false
,I/MusicStore( 6235): Database version: 120
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6235): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6235): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6235): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6235): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6235): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6235): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850,
,E/dhcpcd  ( 6259): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6259): version 5.5.6 starting,
,E/dhcpcd  ( 6259): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ActivityThread( 6235): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6235): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@307c74f1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6235): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6235): GMSCore installation verified
,I/ConfigStore( 6235): Config Database version: 1
,I/dhcpcd  ( 6259): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6259): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6259): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6259): bssid match
,I/dhcpcd  ( 6259): wlan0: rebinding lease of 192.168.1.132
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 70
,I/MediaRouter( 6235): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6235): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6270): MountEmulatedStorage()
E/Zygote  ( 6270): v2
I/libpersona( 6270): KNOX_SDCARD checking this for 10001
I/libpersona( 6270): KNOX_SDCARD not a persona
,I/SELinux ( 6270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6270 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  310): Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 21.534ms,
,D/TimaKeyStoreProvider( 6270): TimaSignature is unavailable
,D/ActivityThread( 6270): Added TimaKeyStore provider
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 16.654ms
I/GHttpClientFactory( 6235): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.751ms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6235): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6289): MountEmulatedStorage()
,E/Zygote  ( 6289): v2
I/libpersona( 6289): KNOX_SDCARD checking this for 1000
,I/SELinux ( 6289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6289): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4196:com.sec.spp.push/u0a32 (adj 15): empty #31
I/ActivityManager( 1016): Killing 5606:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6289): TimaSignature is unavailable
,D/ActivityThread( 6289): Added TimaKeyStore provider
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/DIAGMON_AGENT( 6289): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4196/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_5606/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6289): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6289): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6289): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6304): MountEmulatedStorage(),
E/Zygote  ( 6304): v2
I/libpersona( 6304): KNOX_SDCARD checking this for 10008
I/SELinux ( 6304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/libpersona( 6304): KNOX_SDCARD not a persona
,I/SELinux ( 6304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6304): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6304 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5309:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6304): TimaSignature is unavailable
,D/ActivityThread( 6304): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 5692:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:06:48 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 6320): MountEmulatedStorage()
,E/Zygote  ( 6320): v2
I/libpersona( 6320): KNOX_SDCARD checking this for 10031
,I/libpersona( 6320): KNOX_SDCARD not a persona
,I/SELinux ( 6320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6320 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3674): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/SELinux ( 6320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6320): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_5309/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6320): TimaSignature is unavailable
,D/ActivityThread( 6320): Added TimaKeyStore provider
,I/SO_AGENT( 6320): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5812): [SLFUCHKMGR] constructor called
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5812): [OR] == isSIMCardReady false ==
,I/SA      ( 5812): [SCU] == networkStateCheck == false
,I/SA      ( 5812): [OR] onReceive END
,I/ActivityManager( 1016): Killing 5213:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,D/accuweather( 1552): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5692/cgroup.procs: No such file or directory
,D/daemonapp( 1616): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1552): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1552): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1552): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1552): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1552): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1552): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6337): MountEmulatedStorage()
,I/libpersona( 6337): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6337): v2
I/libpersona( 6337): KNOX_SDCARD not a persona
,I/SELinux ( 6337): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6337 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6337): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6337): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6337): TimaSignature is unavailable
,D/ActivityThread( 6337): Added TimaKeyStore provider,
,W/ResourcesManager( 6337): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6337): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6337): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5213/cgroup.procs: No such file or directory
,D/QuickConnect( 6337): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6337): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6337): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6352): MountEmulatedStorage()
,E/Zygote  ( 6352): v2
I/libpersona( 6352): KNOX_SDCARD checking this for 10141
I/libpersona( 6352): KNOX_SDCARD not a persona
,I/SELinux ( 6352): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6352 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,I/SELinux ( 6352): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6352): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 5725:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6352): TimaSignature is unavailable
,D/ActivityThread( 6352): Added TimaKeyStore provider
,W/ResourcesManager( 6352): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6352): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6352): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/libprocessgroup( 1016): failed to open /acct/uid_10087/pid_5725/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 5846): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 5846): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5846): sendNotify, [notify] : null
D/BadgeProvider( 5846): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5846): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5846): update, [UpdateCount] : 1
,D/Launcher.Model( 1491): reloadBadges entered.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6375): MountEmulatedStorage(),
,E/Zygote  ( 6375): v2,
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6375 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/libpersona( 6375): KNOX_SDCARD checking this for 1000
,I/libpersona( 6375): KNOX_SDCARD not a persona
,I/SELinux ( 6375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6375): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6375): TimaSignature is unavailable
,D/ActivityThread( 6375): Added TimaKeyStore provider
,D/SecurityLogAgent( 6375): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6375): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6375): StateMachine : Current State = 1
,D/SecurityLogAgent( 6375): StateMachine : Changed Current State = 1
,I/ActivityManager( 1016): Killing 5324:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,I/iu.Environment( 1934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1934): num queued entries: 0
,I/iu.UploadsManager( 1934): num updated entries: 0
,I/iu.SyncManager( 1934): NEXT; no task
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1016): failed to open /acct/uid_10029/pid_5324/cgroup.procs: No such file or directory
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 56436(3MB) AllocSpace objects, 12(244KB) LOS objects, 33% free, 23MB/35MB, paused 2.920ms total 226.815ms
,I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6395 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6395): MountEmulatedStorage()
I/libpersona( 6395): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6395): v2
I/libpersona( 6395): KNOX_SDCARD not a persona
,I/SELinux ( 6395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SELinux ( 6395): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Babel   ( 6190): connection state changed from UNKNOWN to DISCONNECTED,
,I/ActivityManager( 1016): Killing 5773:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/dhcpcd  ( 6259): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,D/TimaKeyStoreProvider( 6395): TimaSignature is unavailable
,D/ActivityThread( 6395): Added TimaKeyStore provider
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4,
,W/libprocessgroup( 1016): failed to open /acct/uid_10148/pid_5773/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6259): wlan0: leased 192.168.1.132 for 86400 seconds,
,E/SPPClientService( 6395): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6395): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6395): [SystemStateMoniter] Current Time : 163251
E/SPPClientService( 6395): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6395): [SystemStateMoniter] No Connect : true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6395): PushLog.txt file is not deleted.,
D/SPPClientService( 6395): PushLog.txt file is not deleted.
D/SPPClientService( 6395): ============PushLog. stop!
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6418 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6418): MountEmulatedStorage(),
E/Zygote  ( 6418): v2
I/libpersona( 6418): KNOX_SDCARD checking this for 10110
I/libpersona( 6418): KNOX_SDCARD not a persona,
I/SELinux ( 6418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,E/SPPClientService( 6395): [[SystemStateMonitorService]] No Active Internet
,I/SELinux ( 6418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6418): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5797:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6418): TimaSignature is unavailable,
,D/ActivityThread( 6418): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5797/cgroup.procs: No such file or directory
,I/GAv4    ( 6418): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6418):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6418):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6418): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6418): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6418): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6418): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1016): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1016): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1016): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1016): LTETest block dns file not exists
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/ConnectivityService( 1016): updateNetworkInfo()
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1016):    accepting network in place of null
,D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1469): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/TelephonyNetworkFactory( 1469): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::aec:a9ff:fe50:7542/64,192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
I/WifiTrafficPoller( 1016): current booster mode : FullMode
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1016): updateIfacesLocked()
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,V/NetworkStats( 1016): performPollLocked() took 3ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1171): EthernetConnected: false
,D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1171): updateDataNetType()
,D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1171): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 19 Jan 2016 08:06:49 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453190809897], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453190809881]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
,D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1171): EthernetConnected: false,
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1171): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1171): updateDataNetType()
D/StatusBar.NetworkController( 1171): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1171): updateLTEICONDataNetType:0
D/ConnectivityManager.CallbackHandler( 1171): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1171): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1171): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1171): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1171): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6418): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6418): Time to load native libraries: 2 ms (timestamps 3892-3894)
,I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6418): Binding Chromium to main looper Looper (main, tid 1) {3d3329e}
,I/LibraryLoader( 6418): Expected native library version number "",actual native library version number ""
,I/chromium( 6418): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6418): Initializing chromium process, singleProcess=true
,W/art     ( 6418): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6418): ApplicationContext is null in ApplicationStatus
,W/chromium( 6418): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6418): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6418): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6418): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6418): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6418): Local Branch: 
I/Adreno-EGL( 6418): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6418): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6418):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/NSApplication( 6418): Starting up...
,W/AudioManagerAndroid( 6418): Requires BLUETOOTH permission
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6494): MountEmulatedStorage(),
,E/Zygote  ( 6494): v2,
,I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6494 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 6494): KNOX_SDCARD checking this for 10077
I/libpersona( 6494): KNOX_SDCARD not a persona
,I/SELinux ( 6494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Killing 4873:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,I/SELinux ( 6494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6494): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6494): TimaSignature is unavailable
,D/ActivityThread( 6494): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10011/pid_4873/cgroup.procs: No such file or directory
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6235): type=WIFI subType= reason=null isConnected=true
,D/WaitQueueForNetworkActivate( 6028): notifyNetworkActivated
,W/ContextImpl( 6028): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6028): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6028): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6028): exit::IDLE
D/InitializeManagerStateMachine( 6028): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6028): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6028): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6028): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6028): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6028): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6028): entry::SUCCESS
D/hcjo    ( 6028): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2103): Starting #10
,D/hcjo    ( 6028): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6028): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6028): exit::SUCCESS
D/InitializeManagerStateMachine( 6028): entry::IDLE
,I/Hs20UtilService( 2103): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1016): Killing 5677:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2103): Starting #11
,I/Hs20UtilService( 2103): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2103): Starting #12
,I/Hs20UtilService( 2103): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1301): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1301): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1301): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 2103): Starting #13
,I/Hs20UtilService( 2103): Message received 5007
,D/NearbySettings( 1301): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1301): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1016): mCursor = null
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
,I/PCWCLIENTTRACE_PushUtil( 5710): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5710): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5710): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5710): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1016): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1016): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6235): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/CountryDetector( 1016): No listener is left
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6289): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6289): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1016): failed to open /acct/uid_10041/pid_5677/cgroup.procs: No such file or directory
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1171): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6304): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6304): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:06:50 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3674): NetworkChangeOperations(): uploadRequestLog().START 
,D/ConnectivityService( 1016): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3674): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3674): StateImplV2(): networkChangeListener().END
,I/SA      ( 5812): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5812): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5812): [OR] == isSIMCardReady false ==
,I/SA      ( 5812): [SCU] == networkStateCheck == true
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
I/DBG_POLICYDM( 5755): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 5812): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5812): isChinaCountryCode : false
I/SA      ( 5812): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5812): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5755): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6136): 
,I/DBG_POLICYDM( 5755): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5812): [OR] GetMyCountryZoneTask
,I/SA      ( 5812): [OR] onReceive END
,V/DownloadManager( 1222): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5812): [SRS] prepareGetMyCountryZone
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1552): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5812): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5812): [SSP] query invoked
,I/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/SA      ( 5812): [TPMU] GetMccFromDB : null
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5812): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/daemonapp( 1616): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
I/DBG_POLICYDM( 5755): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5755): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/accuweather( 1552): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1552): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1552): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1552): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1552): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1552): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6337): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6337): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6337): PeriphStartReceiver.onReceive - no need to start
,E/DBG_POLICYDM( 5755): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,E/File    ( 5812): fail readDirectory() errno=2
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6375): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6375): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6375): StateMachine : Current State = 1
,D/SecurityLogAgent( 6375): StateMachine : Changed Current State = 1
,I/DBG_POLICYDM( 5755): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5755): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,V/AlarmManager( 1016): waitForAlarm result :4
,I/iu.Environment( 1934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1934): num queued entries: 0
,I/iu.UploadsManager( 1934): num updated entries: 0
,I/iu.SyncManager( 1934): NEXT; no task
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1934): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6395): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6395): [SystemStateMoniter] Current Time : 164924
E/SPPClientService( 6395): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6190): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6190): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6190): (HTTPLog)-Static: isShipBuild true
I/System.out( 6190): (HTTPLog)-Thread-1052-95333547: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6190): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/hcjo    ( 6028): AutoUpdateManager:IDLE:execute
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/InitializeManagerStateMachine( 6028): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6028): exit::IDLE
D/InitializeManagerStateMachine( 6028): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6028): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6028): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6028): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6028): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6028): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6028): entry::SUCCESS
D/hcjo    ( 6028): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6028): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6028): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6028): exit::SUCCESS
D/InitializeManagerStateMachine( 6028): entry::IDLE
,I/System.out( 6190): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 6190): connection state changed from DISCONNECTED to CONNECTED
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 1934): [AccountUtils] Account not ready
W/Kids    ( 1934): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1934): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1934): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1934): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1934): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1934): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1934): 	at java.lang.Thread.run(Thread.java:818)
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/GCM     ( 1710): Connected
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1710): Message class com.google.f.a.a.p
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1934): Message from null null
,E/GCM     ( 1934): Dropping message from null
,I/SA      ( 5812): [RC New] Execute method=[GET] start
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/SA      ( 5812): [RC New] Security=[true]
,I/System.out( 5812): Thread-980(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/System.out( 5812): Thread-980(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5812): Thread-980(ApacheHTTPLog):isShipBuild true
I/System.out( 5812): Thread-980(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5812): Thread-980(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5393): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5393): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5393): [1] 5.onFinished: Scheduling replication attempt 5.
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6136): 
,I/SA      ( 5812): [RC New] [v2liruge] api execute + 640
,I/SA      ( 5812): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5812): AsyncTask #1 calls detatch()
,I/SA      ( 5812): [ODM] saveOpenData( GEO_IP, PL ),
,I/SA      ( 5812): [OCP] update openData : PL
,I/SA      ( 5812): [TPMU] getNetworkMcc : 
,I/SA      ( 5812): [SCU] saveMccToPreferece Start
,I/SA      ( 5812): [SCU] RegionMCC : 260
I/SA      ( 5812): [SSP] query invoked
,I/SA      ( 5812): [TPMU] GetMccFromDB : null
,I/SA      ( 5812): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5812): [SCU] saveMccToPreferece End
,I/SA      ( 5812): [RC New] executeRequest [v2liruge] end. 707
I/SA      ( 5812): [RC New] Execute end
,I/SA      ( 5812): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5812): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6259): wlan0: sending IPv6 Router Solicitation
,I/jxcore-log( 6136): Test app app.js loaded,
I/jxcore-log( 6136): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6136): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6136): BLE advertisement is supported
I/jxcore-log( 6136): 
,I/Choreographer( 6136): Skipped 352 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6136): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6235): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6235): Stop autocaching.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6547): MountEmulatedStorage()
,I/libpersona( 6547): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6547): v2
I/libpersona( 6547): KNOX_SDCARD not a persona
I/SELinux ( 6547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6547 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6547): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000,
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6547): TimaSignature is unavailable
,D/ActivityThread( 6547): Added TimaKeyStore provider
,W/ResourcesManager( 6547): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6547): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6547): VM with version 2.1.0 has multidex support
,I/MultiDex( 6547): install
I/MultiDex( 6547): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6547): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6547): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6547): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5aa0623: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6547): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1710): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1710): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 1934): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6547): callingUid 10011, callindPid: 6547
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 1934): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1680): [183] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
E/GmsUtils( 6235): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
E/GmsUtils( 6235): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 168024
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0),
D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10049}) (elapsedTime=3470),
,E/Watchdog( 1016): !@Sync 5
,E/SMD     (  289): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5710): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5710): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5710): [GetString-S]
,I/ReactiveServiceManager( 5710): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5710): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5710): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5710): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5710): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5710): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5710): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6259): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1016): waitForAlarm result :4
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 39436(2MB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 23MB/35MB, paused 2.479ms total 149.306ms,
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1710): Vacuum at: now=1453190818451 tag=VacuumService
,I/ActivityManager( 1016): Killing 5862:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/GoogleURLConnFactory( 1710): Using platform SSLCertificateSocketFactory
,W/Uploader( 1710): No account for auth token provided
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1710): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1710): (HTTPLog)-Static: isShipBuild true
I/System.out( 1710): (HTTPLog)-Thread-202-717159547: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5862/cgroup.procs: No such file or directory
,I/System.out( 1710): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,I/qtaguid ( 1710): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,W/Uploader( 1710): No account for auth token provided
,I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,W/Uploader( 1710): No account for auth token provided
,I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,W/Uploader( 1710):  no longer exists, so no auth token.
,I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,W/Uploader( 1710): No account for auth token provided
,I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
,E/Uploader( 1710): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1710): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1710): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1710): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1710): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1710): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1710): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1710): Tagging socket 57 with tag 120100000000{4609,0} for uid -1, pid: 1710, getuid(): 10011
,D/SSRM:n  ( 1016): SIOP:: AP = 300
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1710): (10) POSIX Error : 11 SQLite Error : 3850
,V/AlarmManager( 1016): waitForAlarm result :8
,I/dhcpcd  ( 6259): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6259): wlan0: no IPv6 Routers available
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6028): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6028): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6028): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6028): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6028): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6028): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6028): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6028): entry::IDLE
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6028): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6028): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6028): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6028): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6028): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6028): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6028): entry::IDLE
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager( 1016): waitForAlarm result :4
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5393): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5393): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5393): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,V/EmergencyMode( 1430): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1430): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2652): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2652): Disconnected process message: 10
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1171): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1171): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1016): !@Sync 8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6056): Starting books sync for 61035162, extras: ade
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksConfig( 6056): GmsCore Version = 7.8.99 (2134222-434)
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1710): Background sticky concurrent mark sweep GC freed 38043(2035KB) AllocSpace objects, 46(2MB) LOS objects, 35% free, 8MB/12MB, paused 8.609ms total 41.367ms
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1171): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
D/PersonaManager( 1171): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
,D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1171): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1171): Icon Only
I/StatusBar( 1171): Icon Only
D/PanelView( 1171): There is/are notification(s) 
D/PanelView( 1171): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1710): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1710): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1710): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1710): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1710): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6056): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6056): Soft error
E/BooksSync( 6056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6056): Sync error
E/BooksSync( 6056): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6056): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6056): Finished books sync
,D/SyncManager( 1016): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274327, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1171): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1016): mCursor = null
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1016): [PWL] Off : 225s ago
,E/Watchdog( 1016): !@Sync 9
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,V/AlarmManager( 1016): waitForAlarm result :8
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1171): handleTimeUpdate
,D/SecKeyguardClockView( 1171): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1171): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1171): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1171): *** don't update sliding image ***
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1171): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1171): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/TimaService( 1016): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1016): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1016): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1016): initializing...
I/TLC_TIMA_PKM_initialize( 1016): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1016): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1016): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1016): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1016): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1016): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1016): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1016): Trustlet response is completed
,I/jxcore-log( 6136): --= Surplus to requirements =--
I/jxcore-log( 6136): 
,I/jxcore-log( 6136): ****TEST TOOK:  ms ****
I/jxcore-log( 6136): 
I/jxcore-log( 6136): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6136): 
,D/AndroidRuntime( 6653): 
D/AndroidRuntime( 6653): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6653): CheckJNI is OFF
,D/AndroidRuntime( 6653): readGMSProperty: start
D/AndroidRuntime( 6653): readGMSProperty: already setted!!
D/AndroidRuntime( 6653): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6653): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6653): readGMSProperty: end
D/AndroidRuntime( 6653): addProductProperty: start
,E/AffinityControl( 6653): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6653): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1016): START PACKAGE DELETE: observer{1063400803}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1016): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1016): Killing 6136:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{313996d com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{19499ca6 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1016): Focus left window: 6136
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1016): Focused application released
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 4026): Explicit concurrent mark sweep GC freed 3116(187KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 4.195ms total 30.753ms,
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5938): Explicit concurrent mark sweep GC freed 2968(160KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 900us total 27.649ms
,W/GeofencerStateMachine( 1680): Ignoring removeGeofence because network location is disabled.
,E/SamsungIME( 1850): mOCRHelper is null
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jan 19 09:09:22 GMT+01:00 2016
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3674): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1016): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1016): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1016): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onCreate()
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3674): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3674): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6667): MountEmulatedStorage()
,E/Zygote  ( 6667): v2
I/libpersona( 6667): KNOX_SDCARD checking this for 10090
I/libpersona( 6667): KNOX_SDCARD not a persona
,I/SELinux ( 6667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6667 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 6667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
,I/art     ( 6012): Explicit concurrent mark sweep GC freed 95(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 917us total 159.828ms,
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin,
D/SecContentProvider2( 1016): mCursor = null
,I/art     (  310): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 778us total 26.321ms,
,D/TimaKeyStoreProvider( 6667): TimaSignature is unavailable
D/ActivityThread( 6667): Added TimaKeyStore provider,
,D/RegisteredServicesCache( 1460): empty dynamic service,
I/KLMS-2.5.123: ( 3674): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): listeningToPackageRemoved().START
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.075ms total 20.279ms
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 38209(2MB) AllocSpace objects, 67(1081KB) LOS objects, 33% free, 24MB/36MB, paused 2.980ms total 212.342ms
,I/art     ( 1016): WaitForGcToComplete blocked for 155.467ms for cause Explicit
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.890ms
,D/elm:15121( 6667): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6667): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6667): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6667): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6667): ElmAgentService : onCreate()
,D/elm:15121( 6667): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6667): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6667): MDMBridge.getInstance()
,D/elm:15121( 6667): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6667): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): listeningToPackageRemoved().END
,E/SMD     (  289): DCD OFF
,I/KLMS-2.5.123: ( 3674): KLMSIntentService(): onDestroy()
,D/elm:15121( 6667): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 5021:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1016): no available spell checker services found
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 11573(544KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.226ms total 182.221ms
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 1016): delete codoeFile: 
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,I/AASA_removePackage( 1016): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1016): result of delete: 1{1063400803}
,D/AndroidRuntime( 6653): Shutting down VM
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10338
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/TaskPersister( 1016): removeObsoleteFile: deleting file=20_task.xml
,D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1016): uID is 10338
,V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PCWCLIENTTRACE_PushUtil( 5710): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5710): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5710): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5710): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6684): MountEmulatedStorage()
,E/Zygote  ( 6684): v2
I/libpersona( 6684): KNOX_SDCARD checking this for 10029
I/libpersona( 6684): KNOX_SDCARD not a persona
,I/SELinux ( 6684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6684 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/SELinux ( 6684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1016): failed to open /acct/uid_10039/pid_5021/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6684): TimaSignature is unavailable
,D/ActivityThread( 6684): Added TimaKeyStore provider
,I/FeatureConfig( 6684): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5812): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5812): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1016): Killing 5880:com.wsomacp/u0a23 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6684): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6702): MountEmulatedStorage()
I/libpersona( 6702): KNOX_SDCARD checking this for 10039
E/Zygote  ( 6702): v2
I/libpersona( 6702): KNOX_SDCARD not a persona
I/SELinux ( 6702): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6702 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6702): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6702): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,W/ResourcesManager( 6684): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6702): TimaSignature is unavailable
,D/ActivityThread( 6702): Added TimaKeyStore provider
,W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6702): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6702): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6702): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6702): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/art     ( 6653): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,W/ResourcesManager( 6684): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10023/pid_5880/cgroup.procs: No such file or directory
,W/ResourcesManager( 6684): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6684): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6684): system/finder_cp/cpdata.xml file not found
,E/SQLiteLog( 6702): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6702): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6702): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6702): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6702): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6702): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6702): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6702): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6702): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/NearbySource( 6702): Nearby Source Create!
D/NearbyContext( 6702): Nearby Context Create!
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6702): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6702): Samsung link source created
,E/SQLiteLog( 6702): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
,D/ContactProvider( 6702): getAllContactInfoList Start
,E/SQLiteDatabase( 6702): Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
E/SQLiteDatabase( 6702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteDatabase( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteDatabase( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteDatabase( 6702): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteDatabase( 6702): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteDatabase( 6702): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6702): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6702): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6702): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6702): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6702): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6702): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SQLiteOpenHelper( 6702): Couldn't open local.db for writing (will try read-only):
E/SQLiteOpenHelper( 6702): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteOpenHelper( 6702): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteOpenHelper( 6702): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6702): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
E/SQLiteOpenHelper( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
E/SQLiteOpenHelper( 6702): 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
E/SQLiteOpenHelper( 6702): 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
E/SQLiteOpenHelper( 6702): 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
E/SQLiteOpenHelper( 6702): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 6702): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
E/SQLiteOpenHelper( 6702): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteOpenHelper( 6702): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteOpenHelper( 6702): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 6702): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteOpenHelper( 6702): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteOpenHelper( 6702): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteOpenHelper( 6702): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteOpenHelper( 6702): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteOpenHelper( 6702): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/SQLiteOpenHelper( 6702): Opened local.db in read-only mode

```
