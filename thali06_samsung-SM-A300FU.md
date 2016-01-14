#### Test 55613145b105d0b_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
I/ServiceManager(  316): Waiting for service AtCmdFwd...
--------- beginning of system
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AndroidRuntime( 6061): 
D/AndroidRuntime( 6061): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6061): CheckJNI is OFF
D/AndroidRuntime( 6061): readGMSProperty: start
D/AndroidRuntime( 6061): readGMSProperty: already setted!!
D/AndroidRuntime( 6061): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6061): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6061): readGMSProperty: end
D/AndroidRuntime( 6061): addProductProperty: start
E/AffinityControl( 6061): AffinityControl: registerfunction enter
D/AndroidRuntime( 6061): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1021): inState():  stateMachine is null !!
I/PersonaManagerService( 1021): PersonaId don't exist
I/ActivityManager( 1021): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1021): mDVFSHelper.acquire()
D/FocusedStackFrame( 1021): Set to : 0
D/PhoneWindow( 1021): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1021): *FMB* installDecor flags : 25362712
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6073): MountEmulatedStorage()
E/Zygote  ( 6073): v2
I/libpersona( 6073): KNOX_SDCARD checking this for 10338
I/libpersona( 6073): KNOX_SDCARD not a persona
I/ActivityManager( 1021): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6073 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1021): Focused application set to: xxxx
D/InputDispatcher( 1021): Focus left window: 1484
I/SELinux ( 6073): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/AndroidRuntime( 6061): Shutting down VM
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1021): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6073): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6073): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6073): TimaSignature is unavailable
D/ActivityThread( 6073): Added TimaKeyStore provider
V/WindowManager( 1021): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1021): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/SSRM:n  ( 1021): SIOP:: AP = 260
D/PersonaManager( 1021): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1021):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{496152f token=android.os.BinderProxy@2986edc6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6073): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6073): Time to load native libraries: 2 ms (timestamps 3156-3158)
I/LibraryLoader( 6073): Expected native library version number "",actual native library version number ""
W/art     ( 6061): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6073): Binding Chromium to main looper Looper (main, tid 1) {bd5ee62}
I/LibraryLoader( 6073): Expected native library version number "",actual native library version number ""
I/chromium( 6073): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6073): Initializing chromium process, singleProcess=true
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6073): ApplicationContext is null in ApplicationStatus
W/chromium( 6073): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6073): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6073): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6073): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6073): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6073): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6073): Local Branch: 
I/Adreno-EGL( 6073): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6073): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6073):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
E/SMD     (  289): DCD OFF
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6073): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6073): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6073): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6073): CordovaWebView is running on device made by: samsung
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6073): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1021): Activity pause timeout for ActivityRecord{11c52662 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6073): Render dirty regions requested: true
D/ActivityManager( 1021): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1021): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1021): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1021): handleActiveUserChange for user 0
D/PersonaManagerService( 1021): getPersonasForUser(): returning null!
W/chromium( 6073): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6073): updateVisibility : ActivityRecord{8be8f3f token=android.os.BinderProxy@31acb099 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6073): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6073): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1021): Focus entered window: 6073
D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6073): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6073): Initialized EGL, version 1.4
D/OpenGLRenderer( 6073): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6073): Enabling debug mode 0
D/InputMethodManagerService( 1021): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
W/IInputConnectionWrapper( 6073): showStatusIcon on inactive InputConnection
I/Timeline( 6073): Timeline: Activity_idle id: android.os.BinderProxy@31acb099 time:163651
I/ActivityManager( 1021): Displayed Component not be shown by security: +649ms (total +47s928ms)
W/ActivityManager( 1021): mDVFSHelper.release()
I/Timeline( 1021): Timeline: Activity_windows_visible id: ActivityRecord{11c52662 u0 com.test.thalitest/.MainActivity t20} time:163662
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
I/SamsungIME( 1872): getCurrentCandidateView
D/SamsungIME( 1872): Dismiss ExpandCandiate
I/SamsungIME( 1872): getDebugLevel  : 0x4f4c
W/BindingManager( 6073): Cannot call determinedVisibility() - never saw a connection for the pid: 6073
I/SamsungIME( 1872): getDebugLevel  : 0x4f4c
I/SamsungIME( 1872): KeybaordView init() : load resources
I/SamsungIME( 1872): getCurrentKeyboard
I/SamsungIME( 1872): getTextKeyboard
D/SamsungIME( 1872): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6073): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager( 1021): waitForAlarm result :4
,D/jxcore_app_log( 6073): JniHelper::setJavaVM(0xb81e6448), pthread_self() = -1200366144
D/JX-Cordova( 6073): jxcore cordova android initializing
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 37702(2MB) AllocSpace objects, 32(520KB) LOS objects, 33% free, 23MB/35MB, paused 2.680ms total 146.449ms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5460): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5460): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5460): [1] 5.onFinished: Scheduling replication attempt 5.
,W/jxcore-log( 6073): Initializing JXcore engine,
W/jxcore-log( 6073): JXcore engine is ready
,W/jxcore-log( 6073): Starting JXcore engine
,E/audit   ( 1915): type=1400 msg=audit(1452763989.329:205): avc:  denied  { ioctl } for  pid=6073 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
E/audit   ( 1915):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1915): type=1300 msg=audit(1452763989.329:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=bedd9d58 items=0 ppid=307 ppcomm=main pid=6073 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1915): type=1320 msg=audit(1452763989.329:205): 
,W/jxcore-log( 6073): Platform android
W/jxcore-log( 6073): 
W/jxcore-log( 6073): Process ARCH arm
W/jxcore-log( 6073): 
,I/jxcore-log( 6073): JXcore Cordova bridge is ready!,
I/jxcore-log( 6073): 
W/jxcore-log( 6073): JXcore engine is started
,I/chromium( 6073): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  289): DCD OFF,
,I/jxcore-log( 6073): Toggling radios to true
I/jxcore-log( 6073): 
,D/BluetoothAdapter( 6073): enable()
,D/BluetoothAdapter( 6073): enable(): BT is already enabled..!
,D/SecContentProvider( 1021): uri = 18 selection = isWifiEnabled,
D/WifiService( 1021): setWifiEnabled: true pid=6073, uid=10338
D/SecContentProvider2( 1021): uri = 20 selection = isWifiStateChangeAllowed
W/ActivityManager( 1021): Permission Denial: getCurrentUser() from pid=6073, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,D/SecContentProvider2( 1021): mCursor = null
,W/WifiService( 1021): Failed getting userId using ActivityManagerNative,
W/WifiService( 1021): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6073, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1021): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1021): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1021): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1021): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1021): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1021): name = wifi_on,
I/WifiService( 1021): disconnect: pid=6073, uid=10338
,I/wpa_supplicant( 1387): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 6073): Radios toggled
I/jxcore-log( 6073): 
,I/jxcore-log( 6073): My device name is: samsung-SM-A300FU
I/jxcore-log( 6073): 
,I/wpa_supplicant( 1387): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1021): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1387): wlan0: State: COMPLETED -> DISCONNECTED,
I/wpa_supplicant( 1387): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1387): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1387): Cmd 35605 not handled
D/Tethering( 1021): InitialState.processMessage what=4
E/WifiStateMachine( 1021): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1387): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1387): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1387): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1387): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1387): First Scan Start
I/wpa_supplicant( 1387): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1021): interfaceStatusChanged wlan0, false
,E/Tethering( 1021): No numeric data
,D/Tethering( 1021): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1021): clearTetheredNotification()
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
E/WifiConfigStore( 1021): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/HotspotTile( 1176): updateTetherState():false, false
,V/NetworkStats( 1021): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,V/NetworkStats( 1021): performPollLocked() took 7ms
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1021): do suspend true,
,D/WifiP2pService( 1021): InactiveState{ what=143375 },
D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1736): Read error: ssl=0xb87432e8: I/O error during system call, Connection timed out
E/WifiStateMachine( 1021): Start Disconnecting Watchdog 1
I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb86707c8
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1201207160)
D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/wpa_supplicant( 1387): wlan0: Setting scan request: 0 sec 0 usec
D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiNative-wlan0( 1021): do suspend true
D/WifiP2pService( 1021): InactiveState{ what=143375 }
E/ConnectivityService( 1021): updateNetworkInfo()
D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
E/ConnectivityService( 1021): updateNetworkInfo()
I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xb87432e8: I/O error during system call, Broken pipe
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): DefaultState{ when=-23ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1021): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1021): Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1021, getuid(): 1000
D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/qtaguid ( 1021): Untagging socket 348
,I/System.out( 1021): (HTTPLog)-Static: isSBSettingEnabled false
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,I/Hs20UtilService( 1666): Starting #8
,I/Hs20UtilService( 1666): Message received 5007
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3012): Disconnected process message: 10
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1201207160) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb86707c8
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
D/CommandListener(  279): Clearing all IP addresses on wlan0,
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524292
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/WIFI_P2P( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1021): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 1021): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1021): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory( 1462): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker( 1021): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/CSLegacyTypeTracker( 1021): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/EntConnectivity( 1021): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): ValidatedState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/Zygote  ( 6131): MountEmulatedStorage()
I/libpersona( 6131): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6131): v2
I/libpersona( 6131): KNOX_SDCARD not a persona
,I/SELinux ( 6131): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6131 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService( 1021): nai.networkMonitor.doQuit()
D/WifiNetworkAgent( 1021): NetworkAgent: NetworkAgent channel lost
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): doQuit - quitNow()
,D/Tethering( 1021): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1021): MasterInitialState.processMessage what=3
,I/SELinux ( 6131): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6131): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/EntConnectivity( 1021): Not allowed due to - mEnabled false - primarySimSlot false,
,D/WIFI    ( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): updateIfacesLocked()
V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,V/NetworkStats( 1021): performPollLocked() took 7ms
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling
D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6131): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityThread( 6131): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,W/ResourcesManager( 6131): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PhoneApp( 1462): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,I/Babel_SMS( 6131): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6131): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6131): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6131): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6131): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6131): MmsConfig.loadFromResources
,E/Babel_SMS( 6131): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6131): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  284): getCameraInfo: X
,W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  284): getCameraInfo: X
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6131): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6131): startup - clean
,I/Babel   ( 6131): deleted: false for 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1666): Starting #9
,I/Hs20UtilService( 1666): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6131): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6131): Unsupported mime audio/evrc
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6131): Unsupported mime audio/qcelp
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6131): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6131): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6131): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6131): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6131): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6131): Unsupported mime audio/evrc
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6131): Unsupported mime video/wvc1
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/VideoCapabilities( 6131): Unsupported mime video/x-ms-wmv
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/NetworkChangeNotifierAutoDetect( 4684): Network connectivity changed, type is: 6
,I/ApplicationPolicy( 1021): updateDataUsageMap
,I/PCWCLIENTTRACE_PushUtil( 5790): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5790): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5790): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5790): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1021): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1021): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1021): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6131): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5790): noConnectivity : true
,W/VideoCapabilities( 6131): Unsupported mime video/wvc1
,W/VideoCapabilities( 6131): Unsupported mime video/x-ms-wmv
,E/Zygote  ( 6172): MountEmulatedStorage()
E/Zygote  ( 6172): v2
I/libpersona( 6172): KNOX_SDCARD checking this for 10108
I/libpersona( 6172): KNOX_SDCARD not a persona
,I/SELinux ( 6172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/VideoCapabilities( 6131): Unsupported mime video/x-ms-wmv7
,I/ActivityManager( 1021): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6172 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6172): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
W/VideoCapabilities( 6131): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6131): Unsupported mime video/mp43
,D/TimaKeyStoreProvider( 6172): TimaSignature is unavailable
,D/ActivityThread( 6172): Added TimaKeyStore provider
,W/VideoCapabilities( 6131): Unsupported mime video/sorenson,
,W/VideoCapabilities( 6131): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6131): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6131): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6131): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6131): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6131): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1021): Killing 5310:com.google.android.gm/u0a99 (adj 15): empty #31
,I/vclib   ( 6131): onServiceConnected
,W/Babel   ( 6131): Attempted to change video mute state without an active call.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MusicStore( 6172): Database version: 120
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6172): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6172): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1387): nl80211: Received scan results (6 BSSes),
I/wpa_supplicant( 1387): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1387): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1387): Trying to associate with  'G700'
I/wpa_supplicant( 1387): Re-associate with C0.AA.48
I/wpa_supplicant( 1387): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1021): didn't find BSSID Trying to associate with SSID 'NG700'
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1021): mCursor = null
,W/ContextImpl( 6172): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6172): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/libprocessgroup( 1021): failed to open /acct/uid_10099/pid_5310/cgroup.procs: No such file or directory
,E/wpa_supplicant( 1387): Cmd 35605 not handled
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1387): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1387): Associated with C0.AA.48
I/wpa_supplicant( 1387): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1387): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
D/Tethering( 1021): interfaceLinkStateChanged wlan0, false
D/Tethering( 1021): interfaceStatusChanged wlan0, false
D/Tethering( 1021): interfaceLinkStateChanged wlan0, true
D/Tethering( 1021): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, true
,E/Tethering( 1021): No numeric data
,D/Tethering( 1021): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1021): clearTetheredNotification()
,V/NetworkStats( 1021): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,D/HotspotTile( 1176): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1176): updateTetherState():false, false
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1021): mCursor = null
V/NetworkStats( 1021): performPollLocked() took 5ms
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,I/wpa_supplicant( 1387): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1387): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1387): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1387): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
I/wpa_supplicant( 1387): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
D/SecContentProvider2( 1021): mCursor = null
I/wpa_supplicant( 1387): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=],
,I/wpa_supplicant( 1387): Blacklist: Clear (temp) 
I/wpa_supplicant( 1387): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1021): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1021): interfaceLinkStateChanged wlan0, true
D/Tethering( 1021): interfaceStatusChanged wlan0, true
,D/WifiNative-wlan0( 1021): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1021): setLastSelectedConfiguration -1
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityThread( 6172): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6172): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d67060b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6172): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6172): GMSCore installation verified
,D/ConnectivityService( 1021): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1021): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1021): updateNetworkInfo()
D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/WifiConfigStore( 1021): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/ConfigStore( 6172): Config Database version: 1
,E/WifiConfigStore( 1021): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1021): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1021): mCursor = null
,E/WifiNative-wlan0( 1021): do suspend false
,D/WifiP2pService( 1021): InactiveState{ what=143375 }
,D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1021): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1021): mCursor = null
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1021): getStreamVolume 3 index 70
,I/MediaRouter( 6172): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6172): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1021): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6202): MountEmulatedStorage(),
I/libpersona( 6202): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6202): v2
,I/ActivityManager( 1021): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6202 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6202): KNOX_SDCARD not a persona
,I/SELinux ( 6202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6172): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6202): TimaSignature is unavailable
,D/ActivityThread( 6202): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6172): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/PowerManagerService( 1021): [PWL] Off : 105s ago
,I/PowerManagerService( 1021): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1021): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 1021): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1021, ws=null) (elapsedTime=1210)
,I/ActivityManager( 1021): Killing 5599:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,E/SQLiteLog( 1736): (10) POSIX Error : 11 SQLite Error : 3850
,E/dhcpcd  ( 6219): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6219): version 5.5.6 starting
,I/ActivityManager( 1021): Killing 5614:com.wssyncmldm/1000 (adj 15): empty #31,
,E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
E/dhcpcd  ( 6219): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/BroadcastQueue( 1021): Exception when sending broadcast to ComponentInfo{com.sec.android.diagmonagent/com.sec.android.diagmonagent.DiagMonRegistrationReceiver}
W/BroadcastQueue( 1021): android.os.TransactionTooLargeException
W/BroadcastQueue( 1021): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1021): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1021): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
W/BroadcastQueue( 1021): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
W/BroadcastQueue( 1021): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
W/BroadcastQueue( 1021): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20387)
W/BroadcastQueue( 1021): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
W/BroadcastQueue( 1021): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3368)
W/BroadcastQueue( 1021): 	at android.os.Binder.execTransact(Binder.java:461)
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6225): MountEmulatedStorage()
,E/Zygote  ( 6225): v2
I/libpersona( 6225): KNOX_SDCARD checking this for 1000
I/libpersona( 6225): KNOX_SDCARD not a persona
,I/SELinux ( 6225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6225): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1021): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6225 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6225): TimaSignature is unavailable,
I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6219): wlan0: sendmsg: Cannot assign requested address,
I/dhcpcd  ( 6219): if(wlan0) info get Success. (MAC : C0.AA.48)
D/ActivityThread( 6225): Added TimaKeyStore provider,
I/dhcpcd  ( 6219): bssid match
I/dhcpcd  ( 6219): wlan0: rebinding lease of 192.168.1.132
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5599/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5614/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6225): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,E/Watchdog( 1021): !@Sync 5,
,I/DIAGMON_AGENT( 6225): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6225): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
I/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6225): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6243): MountEmulatedStorage()
,E/Zygote  ( 6243): v2
I/libpersona( 6243): KNOX_SDCARD checking this for 10008
I/libpersona( 6243): KNOX_SDCARD not a persona
,I/SELinux ( 6243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6243 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1021): Killing 5638:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/SELinux ( 6243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6243): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6243): TimaSignature is unavailable
,D/ActivityThread( 6243): Added TimaKeyStore provider
,I/ActivityManager( 1021): Killing 4433:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 10:33:12 GMT+01:00 2016
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6259): MountEmulatedStorage()
E/Zygote  ( 6259): v2
I/libpersona( 6259): KNOX_SDCARD checking this for 10031
I/libpersona( 6259): KNOX_SDCARD not a persona
,I/SELinux ( 6259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/SELinux ( 6259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/SELinux ( 6259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6259 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().END
,D/TimaKeyStoreProvider( 6259): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
D/ActivityThread( 6259): Added TimaKeyStore provider
,I/SO_AGENT( 6259): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1021): failed to open /acct/uid_10139/pid_5638/cgroup.procs: No such file or directory
W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_4433/cgroup.procs: No such file or directory
,I/SA      ( 5925): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
I/SA      ( 5925): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5925): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5925): [SLFUCHKMGR] constructor called
,I/SA      ( 5925): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5925): [OR] == isSIMCardReady false ==
,I/SA      ( 5925): [SCU] == networkStateCheck == false
,I/SA      ( 5925): [OR] onReceive END
,I/ActivityManager( 1021): Killing 4804:com.android.mms/u0a41 (adj 15): empty #31
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1574): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1628): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1574): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1574): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1574): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1574): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1574): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1574): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6276): MountEmulatedStorage(),
I/ActivityManager( 1021): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6276 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/Zygote  ( 6276): v2
I/libpersona( 6276): KNOX_SDCARD checking this for 10121,
I/libpersona( 6276): KNOX_SDCARD not a persona
,I/SELinux ( 6276): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/CountryDetector( 1021): No listener is left
,I/SELinux ( 6276): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6276): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1021): failed to open /acct/uid_10041/pid_4804/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6276): TimaSignature is unavailable
,D/ActivityThread( 6276): Added TimaKeyStore provider
,W/ResourcesManager( 6276): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6276): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6276): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6276): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6276): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6276): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6291): MountEmulatedStorage(),
,E/Zygote  ( 6291): v2
I/libpersona( 6291): KNOX_SDCARD checking this for 10141
,I/libpersona( 6291): KNOX_SDCARD not a persona
,I/SELinux ( 6291): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6291): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1021): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6291 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 5277:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
E/SELinux ( 6291): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/art     (  307): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 23.064ms
D/TimaKeyStoreProvider( 6291): TimaSignature is unavailable
,D/ActivityThread( 6291): Added TimaKeyStore provider
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 577us total 16.622ms
,W/ResourcesManager( 6291): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6291): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6291): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6291): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 580us total 17.333ms
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,W/libprocessgroup( 1021): failed to open /acct/uid_10032/pid_5277/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6313): MountEmulatedStorage(),
E/Zygote  ( 6313): v2
I/libpersona( 6313): KNOX_SDCARD checking this for 10068
I/libpersona( 6313): KNOX_SDCARD not a persona
I/SELinux ( 6313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
D/RCPManagerService( 1021): exchangeData() failure , invalid userId
I/SELinux ( 6313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1021): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6313 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,E/SELinux ( 6313): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6313): TimaSignature is unavailable
,D/ActivityThread( 6313): Added TimaKeyStore provider
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6329): MountEmulatedStorage(),
,I/ActivityManager( 1021): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6329 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6329): v2
,I/libpersona( 6329): KNOX_SDCARD checking this for 1000
I/libpersona( 6329): KNOX_SDCARD not a persona,
D/BadgeProvider( 6313): onCreate
D/BadgeProvider( 6313): DatabaseHelper
,I/SELinux ( 6329): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1021): Killing 5742:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
I/ActivityManager( 1021): Killing 5720:com.samsung.helphub/1000 (adj 15): empty #32
,I/SELinux ( 6329): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6329): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 6313): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 6329): TimaSignature is unavailable
,D/ActivityThread( 6329): Added TimaKeyStore provider
,D/BadgeProvider( 6313): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 6313): sendNotify, [notify] : null
D/BadgeProvider( 6313): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6313): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6313): update, [UpdateCount] : 1
,D/Launcher.Model( 1484): reloadBadges entered.
,D/SecurityLogAgent( 6329): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6329): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6329): StateMachine : Current State = 1
,D/SecurityLogAgent( 6329): StateMachine : Changed Current State = 1
,I/ActivityManager( 1021): Killing 5757:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2071): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2071): num queued entries: 0
,I/iu.UploadsManager( 2071): num updated entries: 0
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 2071): NEXT; no task
,D/ChimeraCfgMgr( 2071): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/libprocessgroup( 1021): failed to open /acct/uid_1000/pid_5720/cgroup.procs: No such file or directory
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6348): MountEmulatedStorage()
,E/Zygote  ( 6348): v2
I/libpersona( 6348): KNOX_SDCARD checking this for 10032
I/libpersona( 6348): KNOX_SDCARD not a persona
,I/SELinux ( 6348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6348 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1021): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/SELinux ( 6348): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Babel   ( 6131): connection state changed from UNKNOWN to DISCONNECTED
,D/TimaKeyStoreProvider( 6348): TimaSignature is unavailable
,D/ActivityThread( 6348): Added TimaKeyStore provider
,W/libprocessgroup( 1021): failed to open /acct/uid_10042/pid_5742/cgroup.procs: No such file or directory
,W/libprocessgroup( 1021): failed to open /acct/uid_10087/pid_5757/cgroup.procs: No such file or directory
,E/SPPClientService( 6348): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6348): [SystemStateMoniter] Current Time : 169067
,E/SPPClientService( 6348): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6348): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6348): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6348): PushLog.txt file is not deleted.
,D/SPPClientService( 6348): PushLog.txt file is not deleted.
,D/SPPClientService( 6348): ============PushLog. stop!
,E/Zygote  ( 6365): MountEmulatedStorage()
,E/Zygote  ( 6365): v2
I/libpersona( 6365): KNOX_SDCARD checking this for 10110
I/libpersona( 6365): KNOX_SDCARD not a persona
,I/ActivityManager( 1021): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6365 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1021): Killing 5711:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
E/SELinux ( 6365): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6365): TimaSignature is unavailable
,D/ActivityThread( 6365): Added TimaKeyStore provider
,E/SPPClientService( 6348): [[SystemStateMonitorService]] No Active Internet
,W/libprocessgroup( 1021): failed to open /acct/uid_10014/pid_5711/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6365): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6365): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6365): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6365):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6365):   adb logcat -s GAv4
,W/GAv4    ( 6365): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6365): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6365): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6365): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6365): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6365): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6365): Time to load native libraries: 2 ms (timestamps 9685-9687)
,I/LibraryLoader( 6365): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6365): Binding Chromium to main looper Looper (main, tid 1) {19d3ad70}
,I/LibraryLoader( 6365): Expected native library version number "",actual native library version number ""
I/chromium( 6365): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6365): Initializing chromium process, singleProcess=true
,W/art     ( 6365): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6365): ApplicationContext is null in ApplicationStatus
,W/chromium( 6365): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6365): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6365): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6365): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6365): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6365): Local Branch: 
I/Adreno-EGL( 6365): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6365): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6365):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/dhcpcd  ( 6219): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,W/AudioManagerAndroid( 6365): Requires BLUETOOTH permission
,I/NSApplication( 6365): Starting up...
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6421): MountEmulatedStorage()
E/Zygote  ( 6421): v2
I/libpersona( 6421): KNOX_SDCARD checking this for 10077
,I/libpersona( 6421): KNOX_SDCARD not a persona
I/SELinux ( 6421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6421): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6421 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1021): Killing 5806:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31,
,D/TimaKeyStoreProvider( 6421): TimaSignature is unavailable
,D/ActivityThread( 6421): Added TimaKeyStore provider
,I/dhcpcd  ( 6219): wlan0: leased 192.168.1.132 for 86400 seconds
,W/libprocessgroup( 1021): failed to open /acct/uid_10148/pid_5806/cgroup.procs: No such file or directory
,E/WifiNative-wlan0( 1021): do suspend true
,D/WifiP2pService( 1021): InactiveState{ what=143375 }
,D/WifiP2pService( 1021): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1021): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1021): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1021): callSECApiInt - ID [210]
,E/ConnectivityService( 1021): updateNetworkInfo()
,D/ConnectivityService( 1021): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1021): Adding iface wlan0 to network 503
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine( 1021): updateDnsLinkProperty: enter,
,D/WifiWatchdogStateMachine.DnsPinger( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1021): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): Adding Route [fe80::/64 -> :: wlan0] to network 503
,I/ActivityManager( 1021): Killing 5390:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/ConnectivityService( 1021): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1021): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1021): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1021): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1021): LTETest block dns file not exists
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1666): Starting #10
,E/WifiStateMachine( 1021): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/Hs20UtilService( 1666): Message received 5007
,E/JavaBinder( 1021): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 1021): Failed to clear dns cache for: com.samsung.android.app.galaxyfinder
,D/ConnectivityService( 1021): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,E/WifiStateMachine( 1021): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/WifiStateMachine( 1021): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
E/ConnectivityService( 1021): updateNetworkInfo()
D/ConnectivityService( 1021): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1021): updateNetworkInfo()
D/ConnectivityService( 1021): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1021): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1021): (HTTPLog)-Static: isSBSettingEnabled false
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1320): MountReceiver.mPrefHandler - 7002
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling
,D/ConnectivityService( 1021):    accepting network in place of null
,D/WIFI    ( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/WIFI_P2P( 1021): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1462): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1462): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1021): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1021): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1176): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1021): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1021): mBoosterFLAG : 0
I/WifiTrafficPoller( 1021): current booster mode : FullMode
,D/WifiNative-wlan0( 1021): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1021): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/Tethering( 1021): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1021): MasterInitialState.processMessage what=3
D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,V/NetworkStats( 1021): updateIfacesLocked()
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
V/NetworkStats( 1021): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1021): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,V/NetworkStats( 1021): performPollLocked() took 5ms
V/NetworkStats( 1021): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,W/libprocessgroup( 1021): failed to open /acct/uid_10029/pid_5390/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1021): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1666): Starting #11
,I/Hs20UtilService( 1666): Message received 5007
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1666): Starting #12
I/Hs20UtilService( 1666): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1320): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1320): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1666): Starting #13
,I/Hs20UtilService( 1666): Message received 5007
,D/NearbySettings( 1320): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1320): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1021): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1021): mCursor = null
,I/System.out( 1021): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1021): mCursor = null
,D/SecContentProvider2( 1021): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1021): mCursor = null
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast,
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 09:33:14 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452763994268], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452763994247]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1021): Validated
,D/ConnectivityService( 1021): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1021): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1021): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1021): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524290
,D/PowerManagerService( 1021): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021
,D/SRIB_DCS( 1176): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1176): EthernetConnected: false
,D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1176): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1176): updateDataNetType()
D/StatusBar.NetworkController( 1176): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1176): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1176): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1176): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1176): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1176): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1176): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1021): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/NetworkChangeNotifierAutoDetect( 4684): Network connectivity changed, type is: 2
,I/PCWCLIENTTRACE_PushUtil( 5790): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5790): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5790): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5790): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1021): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
,I/splitIntent( 1021): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1021): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1021): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6172): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6225): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6225): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 66724(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 24MB/36MB, paused 2.576ms total 153.557ms
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1021): mCursor = null
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6243): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6243): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 10:33:14 GMT+01:00 2016
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5839): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5925): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5925): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5925): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().END
,I/SA      ( 5925): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5925): [OR] == isSIMCardReady false ==
,I/SA      ( 5925): [SCU] == networkStateCheck == true
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
,I/SA      ( 5925): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5925): isChinaCountryCode : false
I/SA      ( 5925): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5925): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5839): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5925): [OR] GetMyCountryZoneTask
,I/SA      ( 5925): [OR] onReceive END,
,I/SA      ( 5925): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1230): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/accuweather( 1574): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5839): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/daemonapp( 1628): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,I/SA      ( 5925): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5925): [SSP] query invoked
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1574): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1574): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1574): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1574): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1021): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1021): mCursor = null
,E/DBG_POLICYDM( 5839): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1574): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1574): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 5925): [TPMU] GetMccFromDB : null
,D/QuickConnect( 6276): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6276): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6276): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 5925): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5925): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5839): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5839): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1021): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6329): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6329): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6329): StateMachine : Current State = 1
,D/SecurityLogAgent( 6329): StateMachine : Changed Current State = 1
,E/File    ( 5925): fail readDirectory() errno=2
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,D/ConnectivityService( 1021): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/iu.Environment( 2071): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2071): num queued entries: 0
,I/iu.UploadsManager( 2071): num updated entries: 0
,I/iu.SyncManager( 2071): NEXT; no task
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2071): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2071): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6348): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6348): [SystemStateMoniter] Current Time : 171308
,E/SPPClientService( 6348): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6131): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6131): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6131): (HTTPLog)-Static: isShipBuild true
I/System.out( 6131): (HTTPLog)-Thread-1027-782862901: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6131): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/WaitQueueForNetworkActivate( 5964): notifyNetworkActivated
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6131): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/Babel   ( 6131): connection state changed from DISCONNECTED to CONNECTED
I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2071): [AccountUtils] Account not ready
W/Kids    ( 2071): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2071): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2071): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2071): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2071): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2071): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2071): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2071): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2071): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2071): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2071): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2071): 	at java.lang.Thread.run(Thread.java:818)
,W/ContextImpl( 5964): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1021): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1736): Connected,
,D/GCM     ( 1736): Message class com.google.f.a.a.p
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/hcjo    ( 5964): AutoUpdateManager:IDLE:execute
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5964): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5964): exit::IDLE
D/InitializeManagerStateMachine( 5964): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5964): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5964): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5964): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5964): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5964): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5964): entry::SUCCESS
D/hcjo    ( 5964): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5964): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5964): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5964): exit::SUCCESS
D/InitializeManagerStateMachine( 5964): entry::IDLE
,I/SA      ( 5925): [RC New] Execute method=[GET] start
,I/SA      ( 5925): [RC New] Security=[true]
,I/System.out( 5925): Thread-1000(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5925): Thread-1000(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5925): Thread-1000(ApacheHTTPLog):isShipBuild true
I/System.out( 5925): Thread-1000(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5925): Thread-1000(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,D/ConnectivityService( 1021): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1021): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,D/ConnectivityService( 1021): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1176): CM callback handler got msg 524295
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  289): DCD OFF
,I/SA      ( 5925): [RC New] [v2liruge] api execute + 646
,I/SA      ( 5925): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5925): AsyncTask #1 calls detatch()
,I/SA      ( 5925): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5925): [OCP] update openData : PL
,I/SA      ( 5925): [TPMU] getNetworkMcc : 
,I/SA      ( 5925): [SCU] saveMccToPreferece Start
,I/SA      ( 5925): [SCU] RegionMCC : 260
I/SA      ( 5925): [SSP] query invoked
,I/SA      ( 5925): [TPMU] GetMccFromDB : null
,I/SA      ( 5925): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5925): [SCU] saveMccToPreferece End
,I/SA      ( 5925): [RC New] executeRequest [v2liruge] end. 702
I/SA      ( 5925): [RC New] Execute end
,I/SA      ( 5925): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5925): [OR] GetMyCountryZoneTask Success
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4916): callingUid 10011, callindPid: 4916
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6172): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6172): Stop autocaching.
,E/GmsUtils( 6172): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6172): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager( 1021): waitForAlarm result :4
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SSRM:n  ( 1021): SIOP:: AP = 320
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1736): Vacuum at: now=1452763996967 tag=VacuumService
,I/GoogleURLConnFactory( 1736): Using platform SSLCertificateSocketFactory
,W/Uploader( 1736): No account for auth token provided
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1736): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1736): (HTTPLog)-Static: isShipBuild true
I/System.out( 1736): (HTTPLog)-Thread-206-681695194: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1736): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,I/qtaguid ( 1736): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,W/Uploader( 1736): No account for auth token provided
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,W/Uploader( 1736): No account for auth token provided
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,W/Uploader( 1736): No account for auth token provided
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,W/Uploader( 1736): No account for auth token provided
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,W/Uploader( 1736):  no longer exists, so no auth token.
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,I/art     ( 1736): Background sticky concurrent mark sweep GC freed 39699(2MB) AllocSpace objects, 45(2MB) LOS objects, 35% free, 8MB/12MB, paused 7.312ms total 38.671ms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1736): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1736): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1736): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1736): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1736): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1736): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1736): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1736): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1736): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1736): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1736, getuid(): 10011
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1736): (10) POSIX Error : 11 SQLite Error : 3850
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1021): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1021) eventTime = 173871
,D/PowerManagerService( 1021): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1021 (0x0)
,D/PowerManagerService( 1021): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1021, ws=WorkSource{10049}) (elapsedTime=3477)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SMD     (  289): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5790): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5790): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5790): [GetString-S]
,I/ReactiveServiceManager( 5790): Supported : 1
,D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1021): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1021): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1021): handleString: Failed to handle string(-4)
E/terrier ( 1021): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5790): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5790): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5790): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5790): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5790): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5790): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 6073): Test app app.js loaded,
I/jxcore-log( 6073): 
,I/chromium( 6073): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  289): DCD OFF
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6219): wlan0: no IPv6 Routers available
,E/SMD     (  289): DCD OFF
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5964): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5964): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5964): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5964): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5964): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5964): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5964): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5964): entry::IDLE
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :4
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5460): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5460): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5460): [1] 5.onFinished: Giving up after 6 failures.
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SQLiteLog( 1736): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3012): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF,
,V/AlarmManager( 1021): waitForAlarm result :4
,D/SSRM:n  ( 1021): SIOP:: AP = 290
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3012): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 1021): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1021): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
I/MotionRecognitionService( 1021): Plugged,
I/MotionRecognitionService( 1021): mGripSensorEnabled= false,
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3012): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1021): waitForAlarm result :8
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Watchdog( 1021): !@Sync 7,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1021): [PWL] Off : 180s ago
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1021): !@Sync 8
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1021): [PWL] Off : 225s ago
,E/Watchdog( 1021): !@Sync 9
,V/AlarmManager( 1021): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1176): handleTimeUpdate
,D/SecKeyguardClockView( 1176): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1176): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1176): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1176): *** don't update sliding image ***
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1176): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1176): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 5992): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 5992): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1021): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1021): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1176): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
I/StatusBar( 1176): Icon Only
D/PanelView( 1176): There is/are notification(s) 
D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1176): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1176): Icon Only
,I/StatusBar( 1176): Icon Only
,D/PanelView( 1176): There is/are notification(s) 
,D/PanelView( 1176): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1736): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1736): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1736): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1736): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1021): userId = 0, bbcId = -10000,
W/ActivityManager( 1021): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 5992): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 5992): Soft error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 5992): Sync error
E/BooksSync( 5992): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 5992): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 5992): Finished books sync
,D/PanelView( 1176): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1021): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 288206, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/TimaService( 1021): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1021): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1021): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1021): initializing...
,I/TLC_TIMA_PKM_initialize( 1021): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1021): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1021): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1021): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1021): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1021): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1021): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1021): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1021): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1021): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1021): Trustlet response is completed
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1021): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1021): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1021): stay LED for fully charged
D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3012): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1176): level :100 plugged : 2
,E/Watchdog( 1021): !@Sync 10
,V/AlarmManager( 1021): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1021): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1021): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1021): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1021): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1021): stay LED for fully charged
D/BatteryService( 1021): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1021): Plugged
I/MotionRecognitionService( 1021): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1176): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1176): handleBatteryUpdate
,V/EmergencyMode( 1422): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1422): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3012): Disconnected process message: 10
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1176): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1176): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1176): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1021): Do not check CP during LCD off.
,D/SSRM:n  ( 1021): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/jxcore-log( 6073): --= Surplus to requirements =--
I/jxcore-log( 6073): 
I/jxcore-log( 6073): ****TEST TOOK:  ms ****
I/jxcore-log( 6073): 
I/jxcore-log( 6073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6073): 
,D/AndroidRuntime( 6588): ,
D/AndroidRuntime( 6588): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6588): CheckJNI is OFF,
D/AndroidRuntime( 6588): readGMSProperty: start
D/AndroidRuntime( 6588): readGMSProperty: already setted!!
D/AndroidRuntime( 6588): propertySet: couldn't set property (it is from app),
D/AndroidRuntime( 6588): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6588): readGMSProperty: end
D/AndroidRuntime( 6588): addProductProperty: start
,E/AffinityControl( 6588): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6588): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1021): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1021): START PACKAGE DELETE: observer{967712566}
D/PackageManager( 1021): pkg{<packageName>}
,D/PackageManager( 1021): user{0}
D/PackageManager( 1021): caller{2000}
D/PackageManager( 1021): flags{3}
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1021): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1021): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1021): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1021): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1021): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1021): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1021): Killing 6073:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1021): Skipping PackageSetting{2a45f22f com.example.hello/10346} due to missing metadata
,I/WindowState( 1021): WIN DEATH: Window{23ed1ca4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1021): Focus left window: 6073
,D/PointerIcon( 1021): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 1021): setMouseCustomIcon IconType is same.101
,D/InputDispatcher( 1021): Focused application released,
I/ActivityManager( 1021):   Force finishing activity ActivityRecord{11c52662 u0 com.test.thalitest/.MainActivity t20}
I/ActivityManager( 1021): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1021): CustomStartingWindow se packge removed so remove capture also
,W/ActivityManager( 1021): Spurious death for ProcessRecord{3669ee37 6073:com.test.thalitest/u0a338}, curProc for 6073: null
,I/art     ( 2772): Explicit concurrent mark sweep GC freed 21976(1214KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 927us total 50.321ms
,I/InputReader( 1021): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1872): mOCRHelper is null
,I/art     ( 4684): Explicit concurrent mark sweep GC freed 19912(1259KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 5.959ms total 85.368ms
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 10:35:59 GMT+01:00 2016
,D/RegisteredServicesCache( 1446): empty dynamic service
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 52336(3MB) AllocSpace objects, 75(1213KB) LOS objects, 33% free, 24MB/36MB, paused 2.704ms total 198.854ms
,I/art     ( 1021): WaitForGcToComplete blocked for 145.878ms for cause Explicit
,D/RCPManagerService( 1021): PackageReceiver onReceive()
,I/HarmonyEASService( 1021): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1021): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService( 1021): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1021): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1021): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1021): uID is 10338
V/EnterpriseBillingPolicy( 1021): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1021): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1021): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1021): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1021): getBillingProfileForVpnEngine - end - null
D/TaskPersister( 1021): removeObsoleteFile: deleting file=20_task.xml
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 13748(716KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 24MB/36MB, paused 4.278ms total 170.064ms
,D/SecContentProvider2( 1021): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1021): mCursor = null
I/art     ( 1021): WaitForGcToComplete blocked for 309.759ms for cause Explicit
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
D/EnterpriseDeviceManagerService( 1021): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1021): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1021): no available spell checker services found
,I/splitIntent( 1021): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1021): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1021): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1021): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6601): MountEmulatedStorage(),
E/Zygote  ( 6601): v2
I/libpersona( 6601): KNOX_SDCARD checking this for 10090
I/libpersona( 6601): KNOX_SDCARD not a persona
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/SELinux ( 6601): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1021): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6601 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6601): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 6601): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): listeningToPackageRemoved().START
,V/AlarmManager( 1021): waitForAlarm result :8
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6601): TimaSignature is unavailable
,D/ActivityThread( 6601): Added TimaKeyStore provider
,D/elm:15121( 6601): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6601): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6601): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15121( 6601): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6601): ElmAgentService : onCreate()
,D/elm:15121( 6601): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6601): MainReceiver.listeningToPackageRemoved()
,D/elm:15121( 6601): MDMBridge.getInstance()
D/elm:15121( 6601): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6601): MDMBridge.getAllLicenseInfoFromSDK()
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
,I/PCWCLIENTTRACE_PushUtil( 5790): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5790): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5790): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5790): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/ResourceType( 1021): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 6618): MountEmulatedStorage()
E/Zygote  ( 6618): v2
I/libpersona( 6618): KNOX_SDCARD checking this for 10029
I/libpersona( 6618): KNOX_SDCARD not a persona
,I/SELinux ( 6618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ResourcesManager( 1021): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1021): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1021): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6618 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:15121( 6601): ElmAgentService : onDestroy().
,I/art     ( 1021): Explicit concurrent mark sweep GC freed 5814(329KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.104ms total 173.843ms
,I/ActivityManager( 1021): Killing 5822:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6618): TimaSignature is unavailable
D/ActivityThread( 6618): Added TimaKeyStore provider
,I/FeatureConfig( 6618): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5925): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5925): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1021): Killing 5863:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/PackageManager( 1021): delete codoeFile: 
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/AASAuninstall( 1021): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1021): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1021): result of delete: 1{967712566}
,W/Resources( 1021): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1021): clearDefaults: com.test.thalitest
,I/PackagesMonitor( 5092): PackagesMonitor onReceive :com.test.thalitest
,I/CrashAnrDetector( 1021): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1021): failed to open /acct/uid_10152/pid_5822/cgroup.procs: No such file or directory
,D/AndroidRuntime( 6588): Shutting down VM
,W/ResourcesManager( 6618): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1021): failed to open /acct/uid_10048/pid_5863/cgroup.procs: No such file or directory
,W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1021): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6637): MountEmulatedStorage()
W/ResourcesManager( 6618): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
E/Zygote  ( 6637): v2
I/libpersona( 6637): KNOX_SDCARD checking this for 10041
I/libpersona( 6637): KNOX_SDCARD not a persona
,I/SELinux ( 6637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SELinux ( 6637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6637): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1021): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6637 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,W/ResourcesManager( 6618): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6618): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6637): TimaSignature is unavailable
,D/ActivityThread( 6637): Added TimaKeyStore provider
,W/ResourcesManager( 6618): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6637): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6637): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6637): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6637): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6618): system/finder_cp/cpdata.xml file not found
,W/ActivityManager( 1021): userId = 0, bbcId = -10000
,W/ActivityManager( 1021): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1021): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,W/art     ( 6588): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/Mms/MmsApp( 6637): [start]    onCreate() consume time = 0.0

```
