#### Test 5065027857de7f1_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  292): DCD OFF
,D/AndroidRuntime( 6147): 
D/AndroidRuntime( 6147): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6147): CheckJNI is OFF
D/AndroidRuntime( 6147): readGMSProperty: start
D/AndroidRuntime( 6147): readGMSProperty: already setted!!
D/AndroidRuntime( 6147): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6147): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6147): readGMSProperty: end
D/AndroidRuntime( 6147): addProductProperty: start
E/AffinityControl( 6147): AffinityControl: registerfunction enter
D/AndroidRuntime( 6147): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6159): MountEmulatedStorage()
E/Zygote  ( 6159): v2
I/libpersona( 6159): KNOX_SDCARD checking this for 10338
I/libpersona( 6159): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6159 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1482
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
D/AndroidRuntime( 6147): Shutting down VM
I/SELinux ( 6159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6159): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6159): TimaSignature is unavailable
D/ActivityThread( 6159): Added TimaKeyStore provider
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1482): updateVisibility : ActivityRecord{3f261f4e token=android.os.BinderProxy@1ea0bceb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1482): onTrimMemory. Level: 20
I/WebViewFactory( 6159): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6159): Time to load native libraries: 2 ms (timestamps 5699-5701)
I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6159): Binding Chromium to main looper Looper (main, tid 1) {10fde84}
I/LibraryLoader( 6159): Expected native library version number "",actual native library version number ""
I/chromium( 6159): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 6147): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 6159): Initializing chromium process, singleProcess=true
,W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6159): ApplicationContext is null in ApplicationStatus
,W/chromium( 6159): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6159): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6159): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6159): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6159): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6159): Local Branch: 
I/Adreno-EGL( 6159): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6159): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6159):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6159): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6159): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6159): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6159): CordovaWebView is running on device made by: samsung
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6159): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{1f9fddaf u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6159): Render dirty regions requested: true
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/chromium( 6159): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6159): updateVisibility : ActivityRecord{164f91d9 token=android.os.BinderProxy@9138723 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6159): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6159): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1017): Focus entered window: 6159
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 6159): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6159): Initialized EGL, version 1.4
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 6159): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6159): Enabling debug mode 0
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1017): Displayed Component not be shown by security: +720ms (total +39s390ms)
W/ActivityManager( 1017): mDVFSHelper.release()
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{1f9fddaf u0 com.test.thalitest/.MainActivity t20} time:156283
W/IInputConnectionWrapper( 6159): showStatusIcon on inactive InputConnection
I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
I/Timeline( 6159): Timeline: Activity_idle id: android.os.BinderProxy@9138723 time:156293
I/SamsungIME( 1850): getCurrentCandidateView
W/BindingManager( 6159): Cannot call determinedVisibility() - never saw a connection for the pid: 6159
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/SamsungIME( 1850): Dismiss ExpandCandiate
I/SamsungIME( 1850): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6159): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1850): getDebugLevel  : 0x4f4c
I/SamsungIME( 1850): KeybaordView init() : load resources
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
I/SamsungIME( 1850): getCurrentKeyboard
I/SamsungIME( 1850): getTextKeyboard
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
D/SamsungIME( 1850): [SwiftkeyWrapper] currentLangauge : 1701729619
D/jxcore_app_log( 6159): JniHelper::setJavaVM(0xb818c448), pthread_self() = -1201993312
D/JX-Cordova( 6159): jxcore cordova android initializing
,E/SMD     (  292): DCD OFF
,W/jxcore-log( 6159): Initializing JXcore engine
W/jxcore-log( 6159): JXcore engine is ready
,W/jxcore-log( 6159): Starting JXcore engine
,E/audit   ( 1856): type=1400 msg=audit(1449832359.468:205): avc:  denied  { ioctl } for  pid=6159 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1856):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1856): type=1300 msg=audit(1449832359.468:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=2 a3=bebcbd58 items=0 ppid=315 ppcomm=main pid=6159 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1856): type=1320 msg=audit(1449832359.468:205): 
,W/jxcore-log( 6159): Platform android
W/jxcore-log( 6159): 
W/jxcore-log( 6159): Process ARCH arm
W/jxcore-log( 6159): 
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,I/jxcore-log( 6159): JXcore Cordova bridge is ready!
I/jxcore-log( 6159): 
,W/jxcore-log( 6159): JXcore engine is started
,I/chromium( 6159): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6159): Toggling radios to true,
I/jxcore-log( 6159): 
,D/BluetoothAdapter( 6159): enable(),
,D/BluetoothAdapter( 6159): enable(): BT is already enabled..!,
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6159, uid=10338
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6159, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6159, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6159, uid=10338
,I/wpa_supplicant( 1384): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6159): Radios toggled
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): Got Device Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): Perf Test app loaded loaded
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): check test folder
I/jxcore-log( 6159): 
,I/jxcore-log( 6159): found test : ./testFindPeers.js
I/jxcore-log( 6159): 
,I/wpa_supplicant( 1384): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/SMD     (  292): DCD OFF,
I/wpa_supplicant( 1384): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1384): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1384): Cmd 35605 not handled
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1384): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1384): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> SCANNING
D/Tethering( 1017): InitialState.processMessage what=4
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1384): First Scan Start
I/wpa_supplicant( 1384): Scan requested (ret=0) - scan timeout 30 seconds
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
E/Tethering( 1017): No numeric data
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1017): clearTetheredNotification()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit,
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1017): performPollLocked() took 7ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
E/WifiNative-wlan0( 1017): do suspend true
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
I/jxcore-log( 6159): found test : ./testSendData.js
I/jxcore-log( 6159): 
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1711): Read error: ssl=0xb86d9760: I/O error during system call, Connection timed out
E/ConnectivityService( 1017): updateNetworkInfo()
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NativeCrypto( 1711): SSL shutdown failed: ssl=0xb86d9760: I/O error during system call, Broken pipe
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
E/WifiNative-wlan0( 1017): do suspend true
I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb79307c8
D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
D/WifiP2pService( 1017): InactiveState{ what=143375 }
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1215101640)
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation,
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1017): Tagging socket 334 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1017): Untagging socket 334
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
I/Hs20UtilService( 1682): Starting #8
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,I/Hs20UtilService( 1682): Message received 5007
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory( 1456): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1215101640) wakelock released: 1, error no: 0
I/rmt_storage(  273): 
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb79307c8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #9
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
I/Hs20UtilService( 1682): Message received 5007
D/Tethering( 1017): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
V/NetworkStats( 1017): performPollLocked() took 5ms
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/chromium( 6159): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
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
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3,
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,D/PhoneApp( 1456): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1456): FileWriteThread : threadType = 3
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ApplicationPolicy( 1017): updateDataUsageMap
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,I/PCWCLIENTTRACE_PushUtil( 5745): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5745): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5745): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): noConnectivity : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6232): MountEmulatedStorage(),
,I/libpersona( 6232): KNOX_SDCARD checking this for 10108
,E/Zygote  ( 6232): v2
I/libpersona( 6232): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6232 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/SELinux ( 6232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6232): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 721us total 27.170ms
,D/TimaKeyStoreProvider( 6232): TimaSignature is unavailable
,D/ActivityThread( 6232): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 699us total 20.149ms
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 684us total 19.896ms
,I/MusicStore( 6232): Database version: 120
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6232): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6232): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,I/wpa_supplicant( 1384): nl80211: Received scan results (8 BSSes),
I/wpa_supplicant( 1384): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1384): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1384): Trying to associate with  'G700'
I/wpa_supplicant( 1384): Re-associate with C0.AA.48,
I/wpa_supplicant( 1384): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,W/ActivityThread( 6232): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6232): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@185ce4c5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6232): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6232): GMSCore installation verified
,I/ConfigStore( 6232): Config Database version: 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/wpa_supplicant( 1384): Cmd 35605 not handled
,I/wpa_supplicant( 1384): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1384): Associated with C0.AA.48
,I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1384): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/Tethering( 1017): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1384): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1384): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1384): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1384): Blacklist: Clear (temp) 
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1017): interfaceStatusChanged wlan0, true
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/AudioService( 1017): getStreamVolume 3 index 70
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/HotspotTile( 1178): updateTetherState():false, false
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
V/NetworkStats( 1017): performPollLocked() took 3ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,I/MediaRouter( 6232): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
V/MusicLeanback( 6232): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiNative-wlan0( 1017): do suspend false,
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6261): MountEmulatedStorage(),
I/libpersona( 6261): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6261): v2
I/libpersona( 6261): KNOX_SDCARD not a persona
I/SELinux ( 6261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6261 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6261): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/GHttpClientFactory( 6232): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6261): TimaSignature is unavailable
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6261): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6232): Using platform SSLCertificateSocketFactory,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1017): Killing 5666:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6280): MountEmulatedStorage()
,E/Zygote  ( 6280): v2
I/libpersona( 6280): KNOX_SDCARD checking this for 1000
I/libpersona( 6280): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6280 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 4207:com.sec.spp.push/u0a32 (adj 15): empty #31
,I/SELinux ( 6280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6280): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6280): TimaSignature is unavailable
,D/ActivityThread( 6280): Added TimaKeyStore provider,
,E/dhcpcd  ( 6295): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6295): version 5.5.6 starting
,E/dhcpcd  ( 6295): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/DIAGMON_AGENT( 6280): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,I/dhcpcd  ( 6295): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6295): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6295): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 6295): bssid match
I/dhcpcd  ( 6295): wlan0: rebinding lease of 192.168.1.132
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1017): failed to open /acct/uid_10139/pid_5666/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_4207/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6280): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6280): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6280): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6302): MountEmulatedStorage(),
E/Zygote  ( 6302): v2
I/libpersona( 6302): KNOX_SDCARD checking this for 10008,
I/libpersona( 6302): KNOX_SDCARD not a persona
I/SELinux ( 6302): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6302 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6302): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6302): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 5238:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6302): TimaSignature is unavailable
,D/ActivityThread( 6302): Added TimaKeyStore provider
,I/ActivityManager( 1017): Killing 5326:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:12:43 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5238/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3576): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3576): KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,E/Zygote  ( 6318): MountEmulatedStorage()
E/Zygote  ( 6318): v2
I/libpersona( 6318): KNOX_SDCARD checking this for 10031
I/libpersona( 6318): KNOX_SDCARD not a persona
,I/SELinux ( 6318): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6318 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6318): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6318): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3576): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3576): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6318): TimaSignature is unavailable
,D/ActivityThread( 6318): Added TimaKeyStore provider
,I/SO_AGENT( 6318): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5781): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5781): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5844): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5844): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5844): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5781): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,E/DBG_POLICYDM( 5781): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,I/SA      ( 5844): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5781): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5326/cgroup.procs: No such file or directory
,I/SA      ( 5844): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5844): [OR] == isSIMCardReady false ==
,I/SA      ( 5844): [SCU] == networkStateCheck == false
,I/SA      ( 5844): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5709:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1597): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1597): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
,E/Zygote  ( 6335): MountEmulatedStorage(),
E/Zygote  ( 6335): v2
I/libpersona( 6335): KNOX_SDCARD checking this for 10121
I/libpersona( 6335): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6335 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6335): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6335): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6335): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6335): TimaSignature is unavailable
,D/ActivityThread( 6335): Added TimaKeyStore provider
,W/ResourcesManager( 6335): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6335): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6335): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6335): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6335): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6335): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5709/cgroup.procs: No such file or directory
,E/Zygote  ( 6350): MountEmulatedStorage()
,I/libpersona( 6350): KNOX_SDCARD checking this for 10141
E/Zygote  ( 6350): v2
I/libpersona( 6350): KNOX_SDCARD not a persona
I/SELinux ( 6350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6350 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5735:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,I/SELinux ( 6350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6350): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6350): TimaSignature is unavailable
,D/ActivityThread( 6350): Added TimaKeyStore provider
,W/ResourcesManager( 6350): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6350): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_5735/cgroup.procs: No such file or directory
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/BadgeProvider( 5866): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId,
,D/BadgeProvider( 5866): sendNotify entered. [uri] : content://com.sec.badge/apps/1,
D/BadgeProvider( 5866): sendNotify, [notify] : null
D/BadgeProvider( 5866): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5866): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5866): update, [UpdateCount] : 1
D/Launcher.Model( 1482): reloadBadges entered.
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6373): MountEmulatedStorage()
,E/Zygote  ( 6373): v2,
I/libpersona( 6373): KNOX_SDCARD checking this for 1000
I/libpersona( 6373): KNOX_SDCARD not a persona
,I/SELinux ( 6373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6373 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Killing 5342:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6373): TimaSignature is unavailable
,D/ActivityThread( 6373): Added TimaKeyStore provider
,D/SecurityLogAgent( 6373): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6373): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6373): StateMachine : Current State = 1
,D/SecurityLogAgent( 6373): StateMachine : Changed Current State = 1
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5342/cgroup.procs: No such file or directory
,I/ActivityManager( 1017): Killing 5797:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2024): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2024): num queued entries: 0
,I/iu.UploadsManager( 2024): num updated entries: 0
,I/iu.SyncManager( 2024): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2024): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/Babel   ( 5159): connection state changed from CONNECTED to DISCONNECTED
,E/Zygote  ( 6392): MountEmulatedStorage(),
E/Zygote  ( 6392): v2
I/libpersona( 6392): KNOX_SDCARD checking this for 10032
I/libpersona( 6392): KNOX_SDCARD not a persona,
,I/SELinux ( 6392): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6392 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 6392): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6392): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6392): TimaSignature is unavailable
,D/ActivityThread( 6392): Added TimaKeyStore provider,
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_5797/cgroup.procs: No such file or directory
,E/SPPClientService( 6392): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6392): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6392): [SystemStateMoniter] Current Time : 162752
,E/SPPClientService( 6392): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6392): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6392): PushLog.txt file is not deleted.
D/SPPClientService( 6392): PushLog.txt file is not deleted.
D/SPPClientService( 6392): ============PushLog. stop!
,E/Zygote  ( 6409): MountEmulatedStorage()
E/Zygote  ( 6409): v2
I/libpersona( 6409): KNOX_SDCARD checking this for 10110
I/libpersona( 6409): KNOX_SDCARD not a persona
,I/SELinux ( 6409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6409): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6409 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5815:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/TimaKeyStoreProvider( 6409): TimaSignature is unavailable
,D/ActivityThread( 6409): Added TimaKeyStore provider
,E/SPPClientService( 6392): [[SystemStateMonitorService]] No Active Internet
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5815/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6295): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6409): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/dhcpcd  ( 6295): wlan0: leased 192.168.1.132 for 86400 seconds,
,W/ContextImpl( 6409): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
I/GAv4    ( 6409): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6409):   adb shell setprop log.tag.GAv4 DEBUG,
I/GAv4    ( 6409):   adb logcat -s GAv4
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6409): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6409): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6409): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,W/GAv4    ( 6409): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6409): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6409): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6409): Time to load native libraries: 1 ms (timestamps 3307-3308),
I/LibraryLoader( 6409): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6409): Binding Chromium to main looper Looper (main, tid 1) {24cbe162}
,I/LibraryLoader( 6409): Expected native library version number "",actual native library version number ""
I/chromium( 6409): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6409): Initializing chromium process, singleProcess=true
,W/art     ( 6409): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6409): ApplicationContext is null in ApplicationStatus
,E/SMD     (  292): DCD OFF
,E/WifiNative-wlan0( 1017): do suspend true
,D/WifiP2pService( 1017): InactiveState{ what=143375 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK,
E/WifiStateMachine( 1017): VerifyingLinkState enter
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,W/chromium( 6409): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
,E/libEGL  ( 6409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6409): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,I/Adreno-EGL( 6409): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6409): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6409): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6409): Local Branch: 
I/Adreno-EGL( 6409): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6409): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6409):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,E/ConnectivityService( 1017): updateNetworkInfo()
,E/ConnectivityService( 1017): updateNetworkInfo()
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling,
,D/ConnectivityService( 1017):    accepting network in place of null
,D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1456): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1456): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
,I/WifiTrafficPoller( 1017): current booster mode : FullMode
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 3ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/AudioManagerAndroid( 6409): Requires BLUETOOTH permission
I/NSApplication( 6409): Starting up...
I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6491): MountEmulatedStorage()
,E/Zygote  ( 6491): v2
I/libpersona( 6491): KNOX_SDCARD checking this for 10077
I/libpersona( 6491): KNOX_SDCARD not a persona
,I/SELinux ( 6491): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6491 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6491): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6491): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Killing 3417:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 11 Dec 2015 11:12:45 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1449832365123], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1449832365104]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/TimaKeyStoreProvider( 6491): TimaSignature is unavailable
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/ActivityThread( 6491): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1017): failed to open /acct/uid_10011/pid_3417/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6050): notifyNetworkActivated
,W/ContextImpl( 6050): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6050): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6050): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6050): exit::IDLE
D/InitializeManagerStateMachine( 6050): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6050): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6050): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6050): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6050): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6050): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6050): entry::SUCCESS
D/hcjo    ( 6050): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #10
,I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,D/hcjo    ( 6050): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6050): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 6050): exit::SUCCESS
D/InitializeManagerStateMachine( 6050): entry::IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/Hs20UtilService( 1682): Starting #11
,I/Hs20UtilService( 1682): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1017): Killing 5702:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,I/NetworkMonitor( 6232): type=WIFI subType= reason=null isConnected=true
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #12
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 1682): Message received 5007
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1682): Starting #13
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/Hs20UtilService( 1682): Message received 5007
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState,
D/SecContentProvider2( 1017): mCursor = null
D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1017): mCursor = null
D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState,
D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5745): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5745): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5745): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6232): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/CountryDetector( 1017): No listener is left
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_5702/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 72231(4MB) AllocSpace objects, 10(212KB) LOS objects, 33% free, 23MB/35MB, paused 2.519ms total 170.241ms
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6280): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6280): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,V/AlarmManager( 1017): waitForAlarm result :4
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,I/DBG_POLICYDM( 5781): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5781): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5781): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5781): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6302): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6302): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:12:45 GMT+01:00 2015
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3576): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3576): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3576): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/KLMS-2.5.123: ( 3576): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3576): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5781): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3576): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3576): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5781): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5781): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 5844): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5844): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5844): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5781): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5844): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5844): [OR] == isSIMCardReady false ==
,I/SA      ( 5844): [SCU] == networkStateCheck == true
,I/SA      ( 5844): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5844): isChinaCountryCode : false
I/SA      ( 5844): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5844): [OR] == networkStateCheck true ==
,I/SA      ( 5844): [OR] GetMyCountryZoneTask
,I/SA      ( 5844): [OR] onReceive END
,I/DBG_POLICYDM( 5781): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5844): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1225): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5844): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5844): [SSP] query invoked
,I/DBG_POLICYDM( 5781): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/SA      ( 5844): [TPMU] GetMccFromDB : null
I/SA      ( 5844): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5844): [TPM] isNoProxy(default) : true
,D/accuweather( 1597): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5781): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,E/File    ( 5844): fail readDirectory() errno=2
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1017): mCursor = null
,D/accuweather( 1597): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1597): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1597): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1597): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6335): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5781): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/QuickConnect( 6335): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6335): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,I/DBG_POLICYDM( 5781): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5781): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/SecurityLogAgent( 6373): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6373): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6373): StateMachine : Current State = 1
,D/SecurityLogAgent( 6373): StateMachine : Changed Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 2024): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/iu.UploadsManager( 2024): num queued entries: 0
,I/iu.UploadsManager( 2024): num updated entries: 0
,I/iu.SyncManager( 2024): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2024): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2024): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SPPClientService( 6392): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6392): [SystemStateMoniter] Current Time : 164640
,E/SPPClientService( 6392): [SystemStateMoniter] No Connect : false
,I/System.out( 5159): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5159): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6050): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6050): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6050): exit::IDLE
D/InitializeManagerStateMachine( 6050): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6050): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6050): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6050): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6050): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6050): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6050): entry::SUCCESS
D/hcjo    ( 6050): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6050): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6050): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
I/System.out( 5159): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/InitializeManagerStateMachine( 6050): exit::SUCCESS
D/InitializeManagerStateMachine( 6050): entry::IDLE
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/Babel   ( 5159): connection state changed from DISCONNECTED to CONNECTED
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2024): [AccountUtils] Account not ready
W/Kids    ( 2024): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2024): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2024): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2024): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2024): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2024): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2024): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2024): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2024): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2024): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2024): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2024): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1711): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1711): Message class com.google.f.a.a.p
,I/SA      ( 5844): [RC New] Execute method=[GET] start
,I/SA      ( 5844): [RC New] Security=[true]
,I/System.out( 5844): Thread-990(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5844): Thread-990(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5844): Thread-990(ApacheHTTPLog):isShipBuild true
I/System.out( 5844): Thread-990(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5844): Thread-990(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,I/jxcore-log( 6159): BLE supported!!
I/jxcore-log( 6159): 
,I/SA      ( 5844): [RC New] [v2liruge] api execute + 666
,I/SA      ( 5844): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5844): AsyncTask #1 calls detatch()
,I/SA      ( 5844): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5844): [OCP] update openData : PL
,I/SA      ( 5844): [TPMU] getNetworkMcc : ,
,I/SA      ( 5844): [SCU] saveMccToPreferece Start
,I/SA      ( 5844): [SCU] RegionMCC : 260
,I/SA      ( 5844): [SSP] query invoked
,I/SA      ( 5844): [TPMU] GetMccFromDB : null
,I/SA      ( 5844): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5844): [SCU] saveMccToPreferece End
,I/SA      ( 5844): [RC New] executeRequest [v2liruge] end. 720,
I/SA      ( 5844): [RC New] Execute end
I/SA      ( 5844): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5844): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6295): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6544): MountEmulatedStorage()
,I/libpersona( 6544): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6544): v2
I/libpersona( 6544): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6544 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
I/SELinux ( 6544): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
I/MusicLeanback( 6232): Conditions not met for autocaching. okToAttempt=false
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/MusicLeanback( 6232): Stop autocaching.
,I/SELinux ( 6544): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6544): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  315): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 24.377ms
,D/TimaKeyStoreProvider( 6544): TimaSignature is unavailable
,D/ActivityThread( 6544): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 667us total 17.486ms
,W/ResourcesManager( 6544): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6544): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.551ms
,I/MultiDex( 6544): VM with version 2.1.0 has multidex support
,I/MultiDex( 6544): install
I/MultiDex( 6544): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6544): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6544): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6544): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3ad13857: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6544): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1017): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,D/GCM     ( 1711): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1017): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1017): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1711): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2024): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
D/WearableService( 6544): callingUid 10011, callindPid: 6544
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2024): Restart initialization of location
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1812): [203] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 6232): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6232): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 167552
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3307)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/Watchdog( 1017): !@Sync 5
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5745): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5745): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5745): [GetString-S]
,I/ReactiveServiceManager( 5745): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5745): getString is null,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5745): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 5745): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5745): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5745): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5745): [ensureRegistration] - No Samsung account
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5410): [1] 5.onFinished: Scheduling replication attempt 5.,
,I/dhcpcd  ( 6295): wlan0: sending IPv6 Router Solicitation,
,I/ActivityManager( 1017): Killing 5886:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5886/cgroup.procs: No such file or directory
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1711): Vacuum at: now=1449832374381 tag=VacuumService
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6578): MountEmulatedStorage()
E/Zygote  ( 6578): v2
I/libpersona( 6578): KNOX_SDCARD checking this for 10161
I/libpersona( 6578): KNOX_SDCARD not a persona
,I/SELinux ( 6578): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6578): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.google.android.youtube for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator: pid=6578 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6578): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6578): TimaSignature is unavailable
,D/ActivityThread( 6578): Added TimaKeyStore provider
,W/ResourcesManager( 6578): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6578): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6578): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6578): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6578): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31887a29: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6578): Installed default security provider GmsCore_OpenSSL
,W/art     ( 6578): Suspending all threads took: 5.717ms,
,W/ResourcesManager( 6578): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6578): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/YouTube MDX( 6578): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 6603): ----------------------------------------------------
I/dex2oat ( 6603): <SS>: S T A R T I N G . . .
I/dex2oat ( 6603): <SS>: Zip is absent. Canceled.
,I/dex2oat ( 6603): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-30238556.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads-30238556.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/dex2oat ( 6603): dex2oat took 50.133ms (threads: 4)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/InstanceID/Rpc( 6578): Found 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/,
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6578): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6050): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6050): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6050): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6050): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6050): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6050): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6050): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6050): entry::IDLE
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,D/AndroidHttpClient( 6578): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 6578): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,I/System.out( 6578): Thread-1167(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6578): Thread-1167(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6578): Thread-1167(ApacheHTTPLog):isShipBuild true
I/System.out( 6578): Thread-1167(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6578): Thread-1167(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10161
,I/dhcpcd  ( 6295): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6295): wlan0: no IPv6 Routers available
,I/System.out( 6578): Thread-1167 calls detatch()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6050): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6050): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6050): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6050): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6050): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6050): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6050): entry::IDLE
,E/SMD     (  292): DCD OFF
,I/System.out( 6578): Thread-1157(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 6578): Thread-1157(ApacheHTTPLog):isShipBuild true
I/System.out( 6578): Thread-1157(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6578): Thread-1157(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10161
,I/qtaguid ( 6578): Tagging socket 51 with tag 0{0,0} for uid -1, pid: 6578, getuid(): 10161
,I/qtaguid ( 6578): Untagging socket 51
,I/System.out( 6578): Thread-1157 calls detatch()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1017): Killing 5906:com.wsomacp/u0a23 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1711): Using platform SSLCertificateSocketFactory
,W/Uploader( 1711): No account for auth token provided
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_5906/cgroup.procs: No such file or directory
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 32756(1609KB) AllocSpace objects, 5(84KB) LOS objects, 33% free, 23MB/35MB, paused 2.446ms total 160.166ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1711): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1711): (HTTPLog)-Static: isShipBuild true
I/System.out( 1711): (HTTPLog)-Thread-203-881235942: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1711): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,I/qtaguid ( 1711): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,W/Uploader( 1711): No account for auth token provided
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,W/Uploader( 1711): No account for auth token provided
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,W/Uploader( 1711): No account for auth token provided
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,W/Uploader( 1711):  no longer exists, so no auth token.
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,W/Uploader( 1711): No account for auth token provided
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1711): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1711): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1711): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1711): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/System.out( 1711): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1711): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1711, getuid(): 10011
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :8
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1017): waitForAlarm result :4
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5410): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5410): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5410): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,E/SMD     (  292): DCD OFF
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 8
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 274212, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 9
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,E/SMD     (  292): DCD OFF
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1017): initializing...
I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 10
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/jxcore-log( 6159): Connected to the server!
I/jxcore-log( 6159): 
,I/chromium( 6159): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6080): Finished books sync
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305619, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 11
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,W/GLSActivity( 1711): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1711): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1711): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1711): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1711): 	at android.os.Binder.execTransact(Binder.java:461)
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
E/PlayEventLogger( 5410): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5410): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5410): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5410): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5410): ,	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5410): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5410): 	at android.os.Binder.execTransact(Binder.java:461),
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/System  ( 5410): Ignoring header User-Agent because its value was null.
,I/System.out( 5410): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5410): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5410): (HTTPLog)-Static: isShipBuild true
I/System.out( 5410): (HTTPLog)-Thread-918-591062343: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5410): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5410): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 12
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :4
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 396823, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 13
,I/PowerManagerService( 1017): [PWL] Off : 330s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 2629): Disconnected process message: 10
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 14
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 15
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1017): [PWL] Off : 390s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/bootchecker(  323): bootchecker wake up!!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...,
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 16,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***,
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 57823(4MB) AllocSpace objects, 148(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.452ms total 165.175ms
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 521420, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 17
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  292): DCD OFF
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1017): [PWL] Off : 455s ago
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/Atfwd_Daemon(  326): Stop the daemon....,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 19
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,I/PowerManagerService( 1017): [PWL] Off : 525s ago
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 20
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 21
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 22,
,I/PowerManagerService( 1017): [PWL] Off : 600s ago
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 23,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 24,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1017): stay LED for fully charged
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 680s ago,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 25
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 770681, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 26
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 27
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 766s ago
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 28
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 29
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1017): !@Sync 30
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 856s ago
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 31,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1017): !@Sync 32
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 33,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 951s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 34,
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,V/AlarmManager( 1017): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManagerEXT( 1017): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1017): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.youtube
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/ads_measurement
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/ads_measurement without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1711): Message class com.google.f.a.a.i
,E/Ads     ( 2024): [JAMS] Failed to get OAuth token: com.google.android.gms.auth.ad: BadAuthentication
,I/System.out( 6578): Thread-1156(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6578): Thread-1156(ApacheHTTPLog):isShipBuild true
I/System.out( 6578): Thread-1156(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6578): Thread-1156(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 6578): Tagging socket 51 with tag 0{0,0} for uid -1, pid: 6578, getuid(): 10161
,I/qtaguid ( 6578): Tagging socket 54 with tag 0{0,0} for uid -1, pid: 6578, getuid(): 10161
,I/qtaguid ( 6578): Untagging socket 51,
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10161
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 6578): Tagging socket 51 with tag 0{0,0} for uid -1, pid: 6578, getuid(): 10161
,I/qtaguid ( 6578): Untagging socket 51
,I/System.out( 6578): Thread-1156 calls detatch()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 35
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 36
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 37,
,I/PowerManagerService( 1017): [PWL] Off : 1051s ago
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 38
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 39,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1017): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1017): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1017): Updating Usage Statistics in DB @ 1449833417456
,I/ApplicationPolicy( 1017): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1017): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1017): ::isTableExists: Table exists 
,I/ApplicationUsage( 1017): Done Updating Usage Statistics in DB @ 1449833417815
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 40
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1017): [PWL] Off : 1156s ago
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 41
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF,
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6080): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6080): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6080): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6080): Soft error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6080): Sync error
E/BooksSync( 6080): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6080): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6080): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1268621, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 42
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 43
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF,
,E/Watchdog( 1017): !@Sync 44
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 1266s ago
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 45
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 46
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 47
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 48
,I/PowerManagerService( 1017): [PWL] Off : 1381s ago
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 49
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1017): !@Sync 50
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 51
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 52
,I/PowerManagerService( 1017): [PWL] Off : 1501s ago
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 53
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 54
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 55
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 56
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 1626s ago
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/Watchdog( 1017): !@Sync 57
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/Watchdog( 1017): !@Sync 58
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/Watchdog( 1017): !@Sync 59
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 60
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10,
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 270
,I/PowerManagerService( 1017): [PWL] Off : 1756s ago,
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 61
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 62
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 63
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1017): !@Sync 64
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,E/SMD     (  292): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2629): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  292): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  292): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
I/ActivityManager( 1017): Killing 6409:com.google.android.apps.magazines/u0a110 (adj 15): empty for 1800s
,I/ActivityManager( 1017): Killing 6373:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,I/ActivityManager( 1017): Killing 6350:com.android.email/u0a141 (adj 15): empty for 1800s
,I/ActivityManager( 1017): Killing 6335:com.samsung.android.sconnect/u0a121 (adj 15): empty for 1800s
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
I/ActivityManager( 1017): Killing 5844:com.osp.app.signin/u0a36 (adj 15): empty for 1800s
,I/ActivityManager( 1017): Killing 5781:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1017): Killing 6318:com.sec.android.soagent/u0a31 (adj 15): empty for 1800s
I/ActivityManager( 1017): Killing 6302:com.sec.android.fotaclient/u0a8 (adj 15): empty for 1800s
I/ActivityManager( 1017): Killing 6280:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1017): Killing 6261:com.sec.android.cloudagent/u0a1 (adj 15): empty for 1801s
I/ActivityManager( 1017): Killing 5745:com.sec.pcw.device/1000 (adj 15): empty for 1801s
,I/ActivityManager( 1017): Killing 5866:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1802s
I/ActivityManager( 1017): Killing 5645:com.android.defcontainer/u0a3 (adj 15): empty for 1870s
I/ActivityManager( 1017): Killing 6033:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1879s
,I/ActivityManager( 1017): Killing 5987:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1880s
I/ActivityManager( 1017): Killing 5968:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1880s
I/ActivityManager( 1017): Killing 5947:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1880s
,I/ActivityManager( 1017): Killing 5015:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1880s
I/ActivityManager( 1017): Killing 5924:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1880s
D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService( 1017): Prepared write state in 14ms
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,V/NetworkStats( 1017): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 6ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/EventLogService( 2024): Aggregate from 1449832029186 (log), 1449832029186 (data)
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1711): Message class com.google.f.a.a.i
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1711): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1711): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1711): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1711): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1711): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1711): Explicit concurrent mark sweep GC freed 47354(2MB) AllocSpace objects, 19(516KB) LOS objects, 39% free, 7MB/13MB, paused 1.036ms total 46.731ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1017): Pruning old procstats: /data/system/procstats/state-2015-12-10-15-42-20.bin
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5968/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10001/pid_6261/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10110/pid_6409/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10003/pid_5645/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6373/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_5866/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5947/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5781/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10098/pid_5987/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10031/pid_6318/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10039/pid_5015/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_5924/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10121/pid_6335/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10141/pid_6350/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10008/pid_6302/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10052/pid_6033/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_6280/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5745/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10036/pid_5844/cgroup.procs: No such file or directory
,E/SQLiteLog( 1711): (10) POSIX Error : 11 SQLite Error : 3850
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7442): 
D/AndroidRuntime( 7442): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7442): CheckJNI is OFF
D/AndroidRuntime( 7442): readGMSProperty: start
D/AndroidRuntime( 7442): readGMSProperty: already setted!!
D/AndroidRuntime( 7442): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7442): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7442): readGMSProperty: end
D/AndroidRuntime( 7442): addProductProperty: start
E/SMD     (  292): DCD OFF
E/AffinityControl( 7442): AffinityControl: registerfunction enter
D/AndroidRuntime( 7442): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 1017): START PACKAGE DELETE: observer{851028290}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1017): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1017): Killing 6159:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1017): Skipping PackageSetting{33463705 com.example.hello/10345} due to missing metadata
I/WindowState( 1017): WIN DEATH: Window{21565469 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1017): Focus left window: 6159
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1f9fddaf u0 com.test.thalitest/.MainActivity t20}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
W/ActivityManager( 1017): Spurious death for ProcessRecord{15ab5d53 6159:com.test.thalitest/u0a338}, curProc for 6159: null
I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
I/ActivityManager( 1017):   Force finishing activity ActivityRecord{1f9fddaf u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1017): Duplicate finish request for ActivityRecord{1f9fddaf u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
D/InputDispatcher( 1017): Focused application released
E/SamsungIME( 1850): mOCRHelper is null
I/art     ( 3861): Explicit concurrent mark sweep GC freed 3212(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 768us total 32.609ms
I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1812): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Dec 11 12:42:49 GMT+01:00 2015
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
I/KLMS-2.5.123: ( 3576): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onCreate()
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
E/Zygote  ( 7455): MountEmulatedStorage()
E/Zygote  ( 7455): v2
I/libpersona( 7455): KNOX_SDCARD checking this for 10090
I/libpersona( 7455): KNOX_SDCARD not a persona
I/SELinux ( 7455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7455 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3576): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/KLMS-2.5.123: ( 3576): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/TimaKeyStoreProvider( 7455): TimaSignature is unavailable
D/ActivityThread( 7455): Added TimaKeyStore provider
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
D/RegisteredServicesCache( 1439): empty dynamic service
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 7455): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7455): ELMEngine.ELMEngine( context ).
D/elm:15121( 7455): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:15121( 7455): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7455): ElmAgentService : onCreate()
D/elm:15121( 7455): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7455): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7455): MDMBridge.getInstance()
D/elm:15121( 7455): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7455): MDMBridge.getAllLicenseInfoFromSDK()
I/art     ( 1017): Explicit concurrent mark sweep GC freed 58726(6MB) AllocSpace objects, 281(4MB) LOS objects, 33% free, 24MB/36MB, paused 2.899ms total 242.064ms
I/art     ( 1017): WaitForGcToComplete blocked for 187.975ms for cause Explicit
D/elm:15121( 7455): ElmAgentService : onDestroy().
I/ActivityManager( 1017): Killing 6491:com.android.chrome/u0a77 (adj 15): empty for 1803s
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): listeningToPackageRemoved().END
I/KLMS-2.5.123: ( 3576): KLMSIntentService(): onDestroy()
W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/RCPManagerService( 1017): PackageReceiver onReceive()
I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/art     ( 1017): Explicit concurrent mark sweep GC freed 13208(631KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 4.131ms total 169.473ms
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1017): failed to open /acct/uid_10077/pid_6491/cgroup.procs: No such file or directory
D/PackageManager( 1017): delete codoeFile: 
D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10338 Target=com.test.thalitest
D/PackageManager( 1017): result of delete: 1{851028290}
D/BackupManagerService( 1017): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1017): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
D/AndroidRuntime( 7442): Shutting down VM
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
D/TaskPersister( 1017): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7472): MountEmulatedStorage()
E/Zygote  ( 7472): v2
I/libpersona( 7472): KNOX_SDCARD checking this for 1000
I/libpersona( 7472): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7472 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7472): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7472): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7472): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7472): TimaSignature is unavailable
D/ActivityThread( 7472): Added TimaKeyStore provider
I/PCWCLIENTTRACE_LOG( 7472): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7472): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7472): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7472): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7472): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7472): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7472): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7487): MountEmulatedStorage()
E/Zygote  ( 7487): v2
I/libpersona( 7487): KNOX_SDCARD checking this for 10029
I/libpersona( 7487): KNOX_SDCARD not a persona
I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7487 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 6007:com.google.android.apps.plus/u0a117 (adj 15): empty for 1803s
I/SELinux ( 7487): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7487): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7487): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7487): TimaSignature is unavailable
D/ActivityThread( 7487): Added TimaKeyStore provider
I/FeatureConfig( 7487): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7504): MountEmulatedStorage()
I/libpersona( 7504): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7504): v2
I/libpersona( 7504): KNOX_SDCARD not a persona
I/SELinux ( 7504): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7504): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7504 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1017): Killing 5159:com.google.android.talk/u0a102 (adj 15): empty for 1803s
E/SELinux ( 7504): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7487): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7504): TimaSignature is unavailable
W/ResourcesManager( 7487): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 7504): Added TimaKeyStore provider
W/ResourcesManager( 7487): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/art     ( 7442): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/ResourcesManager( 7487): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7504): [SSP] onCreated
W/ResourcesManager( 7487): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7504): [TPM] There is no property file
I/SA      ( 7504): [SCU] isHaveSA() - false
I/SA      ( 7504): [TPM] getModelProperty : null
I/SA      ( 7504): [TPM] getCSCProperty : null
I/SA      ( 7504): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7504): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7504): [DM] TFT FEATURE: false
I/SA      ( 7504): [DM] init START
I/SA      ( 7504): [DM] This device is not a Vodafone
W/ResourceType( 7504): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7504): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7504): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourcesManager( 7487): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourceType( 7504): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourcesManager( 7487): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourceType( 7504): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourcesManager( 7487): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourceType( 7504): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 7504): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourcesManager( 7487): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 7504): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7504): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 7504): [SCU] isHaveSA() - false
I/SA      ( 7504): support phone number id : false
I/SA      ( 7504): [DM] Supports Ref Jpn : true
I/SA      ( 7504): [DM] init END
I/SA      ( 7504): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
W/ResourcesManager( 7487): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/SA      ( 7504): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1017): Killing 6232:com.google.android.music:main/u0a108 (adj 15): empty for 1801s
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/Watchdog( 1017): !@Sync 65
W/libprocessgroup( 1017): failed to open /acct/uid_10117/pid_6007/cgroup.procs: No such file or directory
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1017): failed to open /acct/uid_10102/pid_5159/cgroup.procs: No such file or directory
W/GalaxyFinderApplication( 7487): system/finder_cp/cpdata.xml file not found
E/Zygote  ( 7525): MountEmulatedStorage()
I/libpersona( 7525): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7525): v2
I/libpersona( 7525): KNOX_SDCARD not a persona
I/SELinux ( 7525): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7525): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7525): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1017): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7525 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2629): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2629): Disconnected process message: 10
D/TimaKeyStoreProvider( 7525): TimaSignature is unavailable
D/ActivityThread( 7525): Added TimaKeyStore provider
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2

```
