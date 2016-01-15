#### Test 56151093f3290d6_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
D/AndroidRuntime( 6088): 
D/AndroidRuntime( 6088): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6088): CheckJNI is OFF
D/AndroidRuntime( 6088): readGMSProperty: start
D/AndroidRuntime( 6088): readGMSProperty: already setted!!
D/AndroidRuntime( 6088): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6088): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6088): readGMSProperty: end
D/AndroidRuntime( 6088): addProductProperty: start
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4340, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
E/AffinityControl( 6088): AffinityControl: registerfunction enter
D/AndroidRuntime( 6088): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
I/libpersona( 6100): KNOX_SDCARD checking this for 10338
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
I/libpersona( 6100): KNOX_SDCARD not a persona
E/Zygote  ( 6100): MountEmulatedStorage()
E/Zygote  ( 6100): v2
I/SELinux ( 6100): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6100): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6100): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6100 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1479
D/AndroidRuntime( 6088): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6100): TimaSignature is unavailable
D/ActivityThread( 6100): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1479): updateVisibility : ActivityRecord{3735708a token=android.os.BinderProxy@2b9107a4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1479): onTrimMemory. Level: 20
I/WebViewFactory( 6100): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6100): Time to load native libraries: 2 ms (timestamps 6846-6848)
I/LibraryLoader( 6100): Expected native library version number "",actual native library version number ""
W/art     ( 6088): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6100): Binding Chromium to main looper Looper (main, tid 1) {203172a0}
,I/LibraryLoader( 6100): Expected native library version number "",actual native library version number ""
,I/chromium( 6100): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6100): Initializing chromium process, singleProcess=true,
,W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6100): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6100): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6100): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6100): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6100): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6100): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6100): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6100): Local Branch: 
I/Adreno-EGL( 6100): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6100): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6100):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6100): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6100): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6100): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6100): CordovaWebView is running on device made by: samsung
W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6100): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{c46231a u0 com.test.thalitest/.MainActivity t20}
E/SMD     (  290): DCD OFF
D/OpenGLRenderer( 6100): Render dirty regions requested: true
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
W/chromium( 6100): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6100): updateVisibility : ActivityRecord{2539bf85 token=android.os.BinderProxy@eb959ef {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6100): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6100): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1018): Focus entered window: 6100
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/SRIB_DCS( 6100): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6100): Initialized EGL, version 1.4
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/OpenGLRenderer( 6100): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6100): Enabling debug mode 0
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1018): Displayed Component not be shown by security: +739ms (total +41s100ms)
W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{c46231a u0 com.test.thalitest/.MainActivity t20} time:157435
I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
W/IInputConnectionWrapper( 6100): showStatusIcon on inactive InputConnection
I/Timeline( 6100): Timeline: Activity_idle id: android.os.BinderProxy@eb959ef time:157447
I/SamsungIME( 1843): getCurrentCandidateView
W/BindingManager( 6100): Cannot call determinedVisibility() - never saw a connection for the pid: 6100
D/SamsungIME( 1843): Dismiss ExpandCandiate
I/SamsungIME( 1843): getDebugLevel  : 0x4f4c
D/JsMessageQueue( 6100): Set native->JS mode to OnlineEventsBridgeMode
I/SamsungIME( 1843): getDebugLevel  : 0x4f4c
I/SamsungIME( 1843): KeybaordView init() : load resources
I/SamsungIME( 1843): getCurrentKeyboard
I/SamsungIME( 1843): getTextKeyboard
D/SamsungIME( 1843): [SwiftkeyWrapper] currentLangauge : 1701729619
D/SSRM:n  ( 1018): SIOP:: AP = 260
D/jxcore_app_log( 6100): JniHelper::setJavaVM(0xb8229448), pthread_self() = -1200100496
D/JX-Cordova( 6100): jxcore cordova android initializing
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/art     ( 6100): Suspending all threads took: 12.204ms,
,W/jxcore-log( 6100): Initializing JXcore engine
W/jxcore-log( 6100): JXcore engine is ready,
,I/art     ( 6100): Background partial concurrent mark sweep GC freed 26459(1692KB) AllocSpace objects, 2(3MB) LOS objects, 39% free, 16MB/28MB, paused 13.377ms total 56.050ms
,W/jxcore-log( 6100): Starting JXcore engine,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/audit   ( 1871): type=1400 msg=audit(1452862932.059:205): avc:  denied  { ioctl } for  pid=6100 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1871):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1871): type=1300 msg=audit(1452862932.059:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=becd7d58 items=0 ppid=306 ppcomm=main pid=6100 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1871): type=1320 msg=audit(1452862932.059:205): 
,W/jxcore-log( 6100): Platform android
W/jxcore-log( 6100): 
,W/jxcore-log( 6100): Process ARCH arm
W/jxcore-log( 6100): 
,I/jxcore-log( 6100): JXcore Cordova bridge is ready!
I/jxcore-log( 6100): 
,W/jxcore-log( 6100): JXcore engine is started
,I/chromium( 6100): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/jxcore-log( 6100): Toggling radios to true,
I/jxcore-log( 6100): 
,D/BluetoothAdapter( 6100): enable(),
,D/BluetoothAdapter( 6100): enable(): BT is already enabled..!,
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled,
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6100, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6100, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6100, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6100, uid=10338
,I/wpa_supplicant( 1384): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6100): Radios toggled
I/jxcore-log( 6100): 
,I/jxcore-log( 6100): My device name is: samsung-SM-A300FU
I/jxcore-log( 6100): 
,I/wpa_supplicant( 1384): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1384): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1384): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
,I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/wpa_supplicant( 1384): Cmd 35605 not handled
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,I/wpa_supplicant( 1384): reset timer : RESET_TIMER 0
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1384): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1384): First Scan Start
I/wpa_supplicant( 1384): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): InitialState.processMessage what=4
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1018): clearTetheredNotification()
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1172): updateTetherState():false, false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated,
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,E/WifiNative-wlan0( 1018): do suspend true
,D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,V/NetworkStats( 1018): performPollLocked() took 17ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NativeCrypto( 1714): Read error: ssl=0xb87544d8: I/O error during system call, Connection timed out
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1714): SSL shutdown failed: ssl=0xb87544d8: I/O error during system call, Broken pipe
,E/ConnectivityService( 1018): updateNetworkInfo(),
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb70ba7c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223973576)
I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1018): Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1018): Untagging socket 348
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/Hs20UtilService( 1683): Starting #8
,I/Hs20UtilService( 1683): Message received 5007
,D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1338): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1338): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1338): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
V/AlarmManager( 1018): waitForAlarm result :4
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223973576) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb70ba7c8
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 10011
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524292
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1172): EthernetConnected: false
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/Hs20UtilService( 1683): Starting #9
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/Hs20UtilService( 1683): Message received 5007
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 1338): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1338): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1338): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1338): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/AlarmManager( 1018): waitForAlarm result :4
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
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,I/ApplicationPolicy( 1018): updateDataUsageMap
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): noConnectivity : true
,E/Zygote  ( 6181): MountEmulatedStorage()
,E/Zygote  ( 6181): v2
I/libpersona( 6181): KNOX_SDCARD checking this for 10108
I/libpersona( 6181): KNOX_SDCARD not a persona,
,I/SELinux ( 6181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6181 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6181): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6181): TimaSignature is unavailable
,D/ActivityThread( 6181): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,I/MusicStore( 6181): Database version: 120
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/wpa_supplicant( 1384): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 1384): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1384): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1384): Trying to associate with  'G700'
I/wpa_supplicant( 1384): Re-associate with C0.AA.48
I/wpa_supplicant( 1384): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6181): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/wpa_supplicant( 1384): Cmd 35605 not handled
I/wpa_supplicant( 1384): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1384): Associated with C0.AA.48
I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1384): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1384): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1384): wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1384): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true,
I/wpa_supplicant( 1384): Blacklist: Clear (temp) 
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/HotspotTile( 1172): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1172): updateTetherState():false, false
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,V/NetworkStats( 1018): performPollLocked() took 7ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,W/ActivityThread( 6181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d638031: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6181): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6181): GMSCore installation verified
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/ConfigStore( 6181): Config Database version: 1
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 6181): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6181): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6209): MountEmulatedStorage(),
E/Zygote  ( 6209): v2
,I/libpersona( 6209): KNOX_SDCARD checking this for 10001,
I/SELinux ( 6209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 6209): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6209 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6209): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,E/dhcpcd  ( 6219): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6219): version 5.5.6 starting
,I/GHttpClientFactory( 6181): Using our fixed implementation of GMSCore's GoogleHttpClient
,E/dhcpcd  ( 6219): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6181): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 6209): TimaSignature is unavailable
,D/ActivityThread( 6209): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6219): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6219): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6219): bssid match
,I/dhcpcd  ( 6219): wlan0: rebinding lease of 192.168.1.132
,I/ActivityManager( 1018): Killing 5608:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6235 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 4164:com.sec.spp.push/u0a32 (adj 15): empty #31
,E/Zygote  ( 6235): MountEmulatedStorage(),
E/Zygote  ( 6235): v2
,I/libpersona( 6235): KNOX_SDCARD checking this for 1000
I/libpersona( 6235): KNOX_SDCARD not a persona,
,I/SELinux ( 6235): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6235): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6235): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  306): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 647us total 25.755ms
,D/TimaKeyStoreProvider( 6235): TimaSignature is unavailable
,D/ActivityThread( 6235): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 610us total 22.131ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 813us total 16.886ms
,I/DIAGMON_AGENT( 6235): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5608/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4164/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6235): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6235): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6235): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6250): MountEmulatedStorage()
,E/Zygote  ( 6250): v2
I/libpersona( 6250): KNOX_SDCARD checking this for 10008
I/libpersona( 6250): KNOX_SDCARD not a persona
,I/SELinux ( 6250): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6250): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6250 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6250): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5178:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6250): TimaSignature is unavailable
,D/ActivityThread( 6250): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5265:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:02:15 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3642): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3642): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/KLMS-2.5.123: ( 3642): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,E/Zygote  ( 6266): MountEmulatedStorage()
E/Zygote  ( 6266): v2
I/libpersona( 6266): KNOX_SDCARD checking this for 10031
I/KLMS-2.5.123: ( 3642): StateImplV2(): networkChangeListener().END
I/libpersona( 6266): KNOX_SDCARD not a persona
,I/SELinux ( 6266): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6266): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6266): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6266 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6266): TimaSignature is unavailable
,D/ActivityThread( 6266): Added TimaKeyStore provider
,I/SO_AGENT( 6266): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5178/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5265/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5763): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5763): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5763): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5763): [SLFUCHKMGR] constructor called
,I/SA      ( 5763): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5763): [OR] == isSIMCardReady false ==
,I/SA      ( 5763): [SCU] == networkStateCheck == false
I/SA      ( 5763): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5652:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1589): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1589): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1589): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1589): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1589): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6283): MountEmulatedStorage(),
E/Zygote  ( 6283): v2
I/libpersona( 6283): KNOX_SDCARD checking this for 10121
,I/libpersona( 6283): KNOX_SDCARD not a persona
,I/SELinux ( 6283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6283 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6283): TimaSignature is unavailable
,D/ActivityThread( 6283): Added TimaKeyStore provider
,W/ResourcesManager( 6283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6283): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6283): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6283): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6283): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6283): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6298): MountEmulatedStorage()
,E/Zygote  ( 6298): v2
I/libpersona( 6298): KNOX_SDCARD checking this for 10141
I/libpersona( 6298): KNOX_SDCARD not a persona
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5652/cgroup.procs: No such file or directory
I/SELinux ( 6298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6298 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5676:com.google.android.apps.docs/u0a87 (adj 15): empty #31
E/SELinux ( 6298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6298): TimaSignature is unavailable
,D/ActivityThread( 6298): Added TimaKeyStore provider
,W/ResourcesManager( 6298): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6298): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6298): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5676/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5828): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5828): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5828): sendNotify, [notify] : null
,D/BadgeProvider( 5828): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5828): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 5828): update, [UpdateCount] : 1
,D/Launcher.Model( 1479): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6322): MountEmulatedStorage()
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 6322): v2
I/libpersona( 6322): KNOX_SDCARD checking this for 1000
I/libpersona( 6322): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5280:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
I/SELinux ( 6322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6322): TimaSignature is unavailable,
D/ActivityThread( 6322): Added TimaKeyStore provider,
,D/SecurityLogAgent( 6322): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6322): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6322): StateMachine : Current State = 1
,D/SecurityLogAgent( 6322): StateMachine : Changed Current State = 1
,I/ActivityManager( 1018): Killing 5740:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5740/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_5280/cgroup.procs: No such file or directory
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 54628(2MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 23MB/35MB, paused 2.597ms total 154.408ms
,I/iu.Environment( 2079): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2079): num queued entries: 0
,I/iu.UploadsManager( 2079): num updated entries: 0
,I/iu.SyncManager( 2079): NEXT; no task
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2079): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/Babel   ( 5101): connection state changed from CONNECTED to DISCONNECTED
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6341 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6341): MountEmulatedStorage()
I/libpersona( 6341): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6341): v2
I/libpersona( 6341): KNOX_SDCARD not a persona
I/SELinux ( 6341): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6341): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6341): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6341): TimaSignature is unavailable
,D/ActivityThread( 6341): Added TimaKeyStore provider
,E/SPPClientService( 6341): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6341): [SystemStateMoniter] Current Time : 163182
,E/SPPClientService( 6341): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6341): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6341): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6358): MountEmulatedStorage()
D/SPPClientService( 6341): PushLog.txt file is not deleted.
,E/Zygote  ( 6358): v2
I/libpersona( 6358): KNOX_SDCARD checking this for 10110
I/libpersona( 6358): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6358 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6358): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5779:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
I/SELinux ( 6358): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,E/SELinux ( 6358): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SPPClientService( 6341): PushLog.txt file is not deleted.
D/SPPClientService( 6341): ============PushLog. stop!
,E/SPPClientService( 6341): [[SystemStateMonitorService]] No Active Internet
,D/TimaKeyStoreProvider( 6358): TimaSignature is unavailable
,D/ActivityThread( 6358): Added TimaKeyStore provider
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5779/cgroup.procs: No such file or directory
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6358): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6358): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6358): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6358):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6358):   adb logcat -s GAv4
,W/GAv4    ( 6358): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6358): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6358): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6358): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6358): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/dhcpcd  ( 6219): wlan0: acknowledged 192.168.1.132 from 192.168.1.1,
,I/dhcpcd  ( 6219): wlan0: leased 192.168.1.132 for 86400 seconds,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6358): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6358): Time to load native libraries: 1 ms (timestamps 3803-3804)
,I/LibraryLoader( 6358): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6358): Binding Chromium to main looper Looper (main, tid 1) {3a8454de}
,I/LibraryLoader( 6358): Expected native library version number "",actual native library version number ""
,I/chromium( 6358): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6358): Initializing chromium process, singleProcess=true
,W/art     ( 6358): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6358): ApplicationContext is null in ApplicationStatus
,E/WifiNative-wlan0( 1018): do suspend true
,W/chromium( 6358): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6358): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6358): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6358): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6358): Local Branch: 
I/Adreno-EGL( 6358): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6358): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6358):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter,
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/ConnectivityService( 1018): updateNetworkInfo()
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1172): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,W/AudioManagerAndroid( 6358): Requires BLUETOOTH permission
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
V/NetworkStats( 1018): updateIfacesLocked()
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 3ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/NSApplication( 6358): Starting up...
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/StatusBar.NetworkController( 1172): EthernetConnected: false
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6440): MountEmulatedStorage(),
I/libpersona( 6440): KNOX_SDCARD checking this for 10077
E/Zygote  ( 6440): v2
,I/libpersona( 6440): KNOX_SDCARD not a persona
I/SELinux ( 6440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6440 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3506:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,I/SELinux ( 6440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6440): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 6440): TimaSignature is unavailable
,D/ActivityThread( 6440): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:02:16 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862936822], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862936802]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1172): EthernetConnected: false
,D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1172): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1172): updateDataNetType()
D/StatusBar.NetworkController( 1172): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1172): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1172): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1172): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1172): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1172): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1172): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_3506/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 5991): notifyNetworkActivated
,W/ContextImpl( 5991): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6181): type=WIFI subType= reason=null isConnected=true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5991): AutoUpdateManager:IDLE:execute
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/InitializeManagerStateMachine( 5991): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5991): exit::IDLE
D/InitializeManagerStateMachine( 5991): entry::NETWORK_CHECK
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 5991): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5991): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5991): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5991): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5991): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5991): entry::SUCCESS
D/hcjo    ( 5991): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1683): Starting #10
,D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/hcjo    ( 5991): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5991): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
V/NearbySettings( 1338): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1683): Message received 5007
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 5991): exit::SUCCESS
D/InitializeManagerStateMachine( 5991): entry::IDLE
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1338): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 5644:com.android.mms/u0a41 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1683): Starting #11
,I/Hs20UtilService( 1683): Message received 5007
,D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1338): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1683): Starting #12
,I/Hs20UtilService( 1683): Message received 5007
D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1338): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1338): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1338): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1683): Starting #13
,I/Hs20UtilService( 1683): Message received 5007
,D/NearbySettings( 1338): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1338): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/CountryDetector( 1018): No listener is left
,V/MusicLeanback( 6181): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5644/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
I/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6235): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6235): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/SRIB_DCS( 1172): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,D/GCM     ( 1714): Connected
,I/FOTA_Client( 6250): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/GCM     ( 1714): Message class com.google.f.a.a.p
,W/FOTA_Client( 6250): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:02:17 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3642): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3642): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3642): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3642): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3642): NetworkChangeOperations(): uploadRequestLog().START 
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 3642): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,I/KLMS-2.5.123: ( 3642): StateImplV2(): networkChangeListener().END
,I/SA      ( 5763): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5763): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5763): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/DBG_POLICYDM( 5722): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onDestroy()
,I/SA      ( 5763): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5763): [OR] == isSIMCardReady false ==
,I/SA      ( 5763): [SCU] == networkStateCheck == true
,I/SA      ( 5763): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5763): isChinaCountryCode : false
I/SA      ( 5763): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5763): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5722): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5763): [OR] GetMyCountryZoneTask
,I/SA      ( 5763): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/accuweather( 1589): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5763): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,I/DBG_POLICYDM( 5722): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
D/SecContentProvider2( 1018): mCursor = null
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/SA      ( 5763): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5763): [SSP] query invoked
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 11
,D/accuweather( 1589): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1589): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1589): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1589): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5722): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1589): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5763): [TPMU] GetMccFromDB : null
,D/accuweather( 1589): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6283): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5763): [SCU] getMccFromPreferece mcc = 260
I/QuickConnect( 6283): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6283): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 5763): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5722): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5722): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6322): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6322): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6322): StateMachine : Current State = 1
D/SecurityLogAgent( 6322): StateMachine : Changed Current State = 1
E/File    ( 5763): fail readDirectory() errno=2
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524295
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1018): Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,I/iu.Environment( 2079): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/qtaguid ( 1018): Untagging socket 348
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:02:17 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452862937827], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452862937813]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
I/iu.UploadsManager( 2079): num queued entries: 0
,D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
I/iu.UploadsManager( 2079): num updated entries: 0
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/iu.SyncManager( 2079): NEXT; no task
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2079): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2079): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6341): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6341): [SystemStateMoniter] Current Time : 165121
,E/SPPClientService( 6341): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 5101): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5101): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5991): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5991): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5991): exit::IDLE
D/InitializeManagerStateMachine( 5991): entry::NETWORK_CHECK
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/InitializeManagerStateMachine( 5991): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5991): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5991): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5991): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5991): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5991): entry::SUCCESS
D/hcjo    ( 5991): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5991): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5991): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5991): exit::SUCCESS
D/InitializeManagerStateMachine( 5991): entry::IDLE
,I/System.out( 5101): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2079): [AccountUtils] Account not ready
W/Kids    ( 2079): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2079): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2079): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2079): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2079): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2079): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2079): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2079): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2079): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2079): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2079): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2079): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 5101): connection state changed from DISCONNECTED to CONNECTED
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/chromium( 6100): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/SA      ( 5763): [RC New] Execute method=[GET] start
,I/SA      ( 5763): [RC New] Security=[true]
,I/System.out( 5763): Thread-975(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5763): Thread-975(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5763): Thread-975(ApacheHTTPLog):isShipBuild true
,I/System.out( 5763): Thread-975(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5763): Thread-975(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 5763): [RC New] [v2liruge] api execute + 633
,I/SA      ( 5763): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5763): AsyncTask #1 calls detatch()
,I/SA      ( 5763): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5763): [OCP] update openData : PL
,I/SA      ( 5763): [TPMU] getNetworkMcc : 
,I/SA      ( 5763): [SCU] saveMccToPreferece Start
,I/SA      ( 5763): [SCU] RegionMCC : 260
I/SA      ( 5763): [SSP] query invoked,
,I/SA      ( 5763): [TPMU] GetMccFromDB : null
,I/SA      ( 5763): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5763): [SCU] saveMccToPreferece End
,I/SA      ( 5763): [RC New] executeRequest [v2liruge] end. 700
I/SA      ( 5763): [RC New] Execute end
,I/SA      ( 5763): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5763): [OR] GetMyCountryZoneTask Success
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6181): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6181): Stop autocaching.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6495 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/Zygote  ( 6495): MountEmulatedStorage()
I/libpersona( 6495): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6495): v2
I/libpersona( 6495): KNOX_SDCARD not a persona
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/SELinux ( 6495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6495): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6495): TimaSignature is unavailable
,D/ActivityThread( 6495): Added TimaKeyStore provider
,W/ResourcesManager( 6495): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6495): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6495): VM with version 2.1.0 has multidex support
,I/MultiDex( 6495): install
I/MultiDex( 6495): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6495): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,W/ActivityThread( 6495): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());,
W/System  ( 6495): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15a24763: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6495): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,D/GCM     ( 1714): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1714): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2079): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6495): callingUid 10011, callindPid: 6495
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
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2079): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1829): Explicit concurrent mark sweep GC freed 16705(931KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 8MB/13MB, paused 1.063ms total 62.997ms
,E/DataBuffer( 1829): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2379e4b5)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1829): [208] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6181): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6181): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,E/Watchdog( 1018): !@Sync 5
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  259): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 168207
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3479)
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/GCM     ( 1714): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1714): Message class com.google.f.a.a.p
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1714): Explicit concurrent mark sweep GC freed 27151(1535KB) AllocSpace objects, 8(162KB) LOS objects, 39% free, 7MB/12MB, paused 1.006ms total 49.671ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 40593(2MB) AllocSpace objects, 5(84KB) LOS objects, 33% free, 23MB/35MB, paused 2.534ms total 143.318ms
,D/Finsky  ( 5349): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5349): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5349): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  290): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5688): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5688): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): [GetString-S]
,I/ReactiveServiceManager( 5688): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1018): handleString: Failed to handle string(-4)
,E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5688): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5688): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5688): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5688): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5688): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
,V/AlarmManager( 1018): waitForAlarm result :4,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1714): Vacuum at: now=1452862944382 tag=VacuumService
,I/ActivityManager( 1018): Killing 4954:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,E/SMD     (  290): DCD OFF
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_4954/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6219): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6219): wlan0: no IPv6 Routers available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5991): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5991): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5991): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5991): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5991): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5991): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5991): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5991): entry::IDLE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5991): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5991): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5991): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5991): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5991): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5991): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5991): entry::IDLE
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5349): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5349): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5349): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 270,
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 8,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,E/SMD     (  290): DCD OFF
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
,I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6020): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 280109, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin,
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6020): Finished books sync
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 313335, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 11
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GLSActivity( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1714): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1714): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1714): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1714): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5349): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5349): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5349): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5349): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5349): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5349): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5349): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5349): Ignoring header User-Agent because its value was null.
,I/System.out( 5349): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5349): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5349): (HTTPLog)-Static: isShipBuild true
I/System.out( 5349): (HTTPLog)-Thread-908-560189267: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5349): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10026
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,I/System.out( 5349): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1018): waitForAlarm result :4,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ProcessCpuTracker( 1018): Skipping unknown process pid 6623
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 12
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 48498(3MB) AllocSpace objects, 99(1602KB) LOS objects, 33% free, 23MB/35MB, paused 2.460ms total 146.084ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6020): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 406425, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4,
,E/Watchdog( 1018): !@Sync 14
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,E/Watchdog( 1018): !@Sync 15
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/bootchecker(  313): bootchecker wake up!!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 455s ago,
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only,
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6020): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 538678, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 18
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 19,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 20,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 21,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 600s ago,
,E/Watchdog( 1018): !@Sync 22,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 23
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 680s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 25,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 26,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,I/StatusBar( 1172): Icon Only
,D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6020): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 802663, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 27
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 765s ago,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 28
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 29,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 855s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 31
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 32
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 33,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,I/PowerManagerService( 1018): [PWL] Off : 950s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 34
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 35
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 1714): Using platform SSLCertificateSocketFactory
,D/Procstats( 2079): User is not opted-in to Usage & Diagnostics.
,W/Uploader( 1714): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1714): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1714): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1714): (HTTPLog)-Thread-210-572914097: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,V/NativeCrypto( 1714): Read error: ssl=0xb87faf20: I/O error during system call, Connection reset by peer
,I/System.out( 1714): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
V/NativeCrypto( 1714): SSL shutdown failed: ssl=0xb87faf20: I/O error during system call, Broken pipe
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 503]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/qtaguid ( 1714): Tagging socket 50 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,I/qtaguid ( 1018): Tagging socket 375 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1018): Untagging socket 375
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 13:17:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452863841628], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452863841614]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1172): CM callback handler got msg 524290
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714):  no longer exists, so no auth token.
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/Uploader( 1714): No account for auth token provided
,I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice,
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
E/Uploader( 1714): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1714): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1714): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1714): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1714): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1714): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
I/System.out( 1714): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1714): Tagging socket 59 with tag 120100000000{4609,0} for uid -1, pid: 1714, getuid(): 10011
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1714): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0,
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/GCM     ( 1714): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1714): Message class com.google.f.a.a.p
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 36
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 1050s ago
,E/Watchdog( 1018): !@Sync 37
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 39,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1452863988519
I/ApplicationPolicy( 1018): updateDataUsageMap
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1452863988845
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 40
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1155s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 41
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 42
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/Watchdog( 1018): !@Sync 43
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6020): Starting books sync for 61035162, extras: ade,
,I/BooksConfig( 6020): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1172): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1172): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1172): Icon Only
I/StatusBar( 1172): Icon Only
D/PanelView( 1172): There is/are notification(s) 
D/PanelView( 1172): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1714): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1714): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1714): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1714): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1714): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6020): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6020): Soft error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6020): Sync error
E/BooksSync( 6020): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6020): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6020): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1330193, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1172): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 1265s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1172): handleTimeUpdate
,D/SecKeyguardClockView( 1172): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1172): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1172): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1172): *** don't update sliding image ***
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1172): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1172): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 45,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 46,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 47,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1381s ago,
,E/Watchdog( 1018): !@Sync 48,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/Watchdog( 1018): !@Sync 49,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  290): DCD OFF,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 50
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 51
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1501s ago
,E/Watchdog( 1018): !@Sync 52,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1418): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1172): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1418): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1172): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,V/HeadsetService( 2631): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2631): Disconnected process message: 10
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1172): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1172): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1172): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 53,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 54,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 55,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 56
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/PowerManagerService( 1018): [PWL] Off : 1626s ago,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/Watchdog( 1018): !@Sync 57,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 58
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1018): !@Sync 59,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 60,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1756s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 61,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 62
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 63
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 64
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,TIME-OUT KILL (timeout was 1800000ms),E/Watchdog( 1018): !@Sync 65
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
I/PowerManagerService( 1018): [PWL] Off : 1891s ago
D/AndroidRuntime( 7293): 
D/AndroidRuntime( 7293): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7293): CheckJNI is OFF
D/AndroidRuntime( 7293): readGMSProperty: start
D/AndroidRuntime( 7293): readGMSProperty: already setted!!
D/AndroidRuntime( 7293): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7293): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7293): readGMSProperty: end
D/AndroidRuntime( 7293): addProductProperty: start
E/AffinityControl( 7293): AffinityControl: registerfunction enter
D/AndroidRuntime( 7293): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{11397200}
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
D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 6100:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{22c99ff5 com.example.hello/10346} due to missing metadata
I/ActivityManager( 1018): Killing 6322:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6298:com.android.email/u0a141 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6283:com.samsung.android.sconnect/u0a121 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 5763:com.osp.app.signin/u0a36 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 5722:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6266:com.sec.android.soagent/u0a31 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6250:com.sec.android.fotaclient/u0a8 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6235:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 6209:com.sec.android.cloudagent/u0a1 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 5688:com.sec.pcw.device/1000 (adj 15): empty for 1803s
I/ActivityManager( 1018): Killing 5828:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1805s
I/ActivityManager( 1018): Killing 5587:com.android.defcontainer/u0a3 (adj 15): empty for 1874s
I/ActivityManager( 1018): Killing 5975:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1883s
I/ActivityManager( 1018): Killing 5930:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1884s
I/ActivityManager( 1018): Killing 5911:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1884s
I/ActivityManager( 1018): Killing 5893:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1884s
I/ActivityManager( 1018): Killing 5872:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1884s
I/ActivityManager( 1018): Killing 5848:com.wsomacp/u0a23 (adj 15): empty for 1884s
I/ActivityManager( 1018): Killing 5818:com.sec.android.app.myfiles/u0a42 (adj 15): empty for 1885s
I/WindowState( 1018): WIN DEATH: Window{2371c89c u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{c46231a u0 com.test.thalitest/.MainActivity t20}
I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
D/InputDispatcher( 1018): Focus left window: 6100
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ProcessStatsService( 1018): Prepared write state in 14ms
D/InputDispatcher( 1018): Focused application released
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
I/art     ( 3994): Explicit concurrent mark sweep GC freed 3202(192KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 718us total 29.110ms
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
E/SamsungIME( 1843): mOCRHelper is null
W/GeofencerStateMachine( 1829): Ignoring removeGeofence because network location is disabled.
W/ResourcesManager( 1457): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 14:32:21 GMT+01:00 2016
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3642): KLMSAbstractReciever(): onReceive().END.
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onCreate()
I/KLMS-2.5.123: ( 3642): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.5.123: ( 3642): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): listeningToPackageRemoved().START
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7307): MountEmulatedStorage()
I/libpersona( 7307): KNOX_SDCARD checking this for 10090
E/Zygote  ( 7307): v2
I/libpersona( 7307): KNOX_SDCARD not a persona
I/SELinux ( 7307): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7307 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 7307): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7307): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7307): TimaSignature is unavailable
D/ActivityThread( 7307): Added TimaKeyStore provider
I/art     ( 1018): Explicit concurrent mark sweep GC freed 60325(6MB) AllocSpace objects, 318(5MB) LOS objects, 33% free, 24MB/36MB, paused 4.327ms total 240.992ms
I/art     ( 1018): WaitForGcToComplete blocked for 126.228ms for cause Explicit
D/RegisteredServicesCache( 1446): empty dynamic service
D/elm:15121( 7307): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7307): ELMEngine.ELMEngine( context ).
D/elm:15121( 7307): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7307): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/RCPManagerService( 1018): PackageReceiver onReceive()
D/elm:15121( 7307): ElmAgentService : onCreate()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/elm:15121( 7307): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 7307): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 7307): MDMBridge.getInstance()
I/KLMS-2.5.123: ( 3642): KLMSIntentService(): onDestroy()
D/elm:15121( 7307): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7307): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7307): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 6358:com.google.android.apps.magazines/u0a110 (adj 15): empty for 1803s
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
D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1018): uID is 10338
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7324): MountEmulatedStorage()
E/Zygote  ( 7324): v2
I/libpersona( 7324): KNOX_SDCARD checking this for 1000
I/libpersona( 7324): KNOX_SDCARD not a persona
I/SELinux ( 7324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7324 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7324): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  306): Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 21.111ms
I/art     ( 1018): Explicit concurrent mark sweep GC freed 12729(629KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.574ms total 185.604ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 601us total 23.368ms
D/TimaKeyStoreProvider( 7324): TimaSignature is unavailable
D/ActivityThread( 7324): Added TimaKeyStore provider
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 17.414ms
I/PCWCLIENTTRACE_LOG( 7324): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7324): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7324): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil( 7324): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7324): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7324): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7324): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7339): MountEmulatedStorage()
E/Zygote  ( 7339): v2
I/libpersona( 7339): KNOX_SDCARD checking this for 10029
I/libpersona( 7339): KNOX_SDCARD not a persona
I/SELinux ( 7339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7339 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/PackageManager( 1018): delete codoeFile: 
I/SELinux ( 7339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 6440:com.android.chrome/u0a77 (adj 15): empty for 1804s
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
E/SELinux ( 7339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/PackageManager( 1018): result of delete: 1{11397200}
D/AndroidRuntime( 7293): Shutting down VM
D/TimaKeyStoreProvider( 7339): TimaSignature is unavailable
D/ActivityThread( 7339): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/FeatureConfig( 7339): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/Zygote  ( 7356): MountEmulatedStorage()
E/Zygote  ( 7356): v2
I/libpersona( 7356): KNOX_SDCARD checking this for 10036
I/libpersona( 7356): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7356 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 7356): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5949:com.google.android.apps.plus/u0a117 (adj 15): empty for 1804s
I/SELinux ( 7356): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7356): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7339): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7356): TimaSignature is unavailable
D/ActivityThread( 7356): Added TimaKeyStore provider
W/ResourcesManager( 7339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7356): [SSP] onCreated
W/ResourcesManager( 7339): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/SA      ( 7356): [TPM] There is no property file
W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7356): [SCU] isHaveSA() - false
I/SA      ( 7356): [TPM] getModelProperty : null
I/SA      ( 7356): [TPM] getCSCProperty : null
I/SA      ( 7356): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7356): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7356): [DM] TFT FEATURE: false
W/ResourcesManager( 7339): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7356): [DM] init START
I/SA      ( 7356): [DM] This device is not a Vodafone
W/ResourceType( 7356): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourcesManager( 7339): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourceType( 7356): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7356): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7356): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourcesManager( 7339): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7339): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/GalaxyFinderApplication( 7339): system/finder_cp/cpdata.xml file not found
W/ResourceType( 7356): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7356): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 7356): [SCU] isHaveSA() - false
I/SA      ( 7356): support phone number id : false
I/SA      ( 7356): [DM] Supports Ref Jpn : true
I/SA      ( 7356): [DM] init END
I/SA      ( 7356): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7356): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 6181:com.google.android.music:main/u0a108 (adj 15): empty for 1802s
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
W/art     ( 7293): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7376): MountEmulatedStorage()
I/libpersona( 7376): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7376): v2
I/libpersona( 7376): KNOX_SDCARD not a persona
I/SELinux ( 7376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7376 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 7376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7376): TimaSignature is unavailable
D/ActivityThread( 7376): Added TimaKeyStore provider
W/ResourcesManager( 7376): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7376): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2016-01-14-19-22-15.bin
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 7376): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteDatabase( 7376): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 7376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7376): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 7376): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7376): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7376): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7376): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7376): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/NearbySource( 7376): Nearby Source Create!
D/NearbyContext( 7376): Nearby Context Create!
E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7376): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7376): Samsung link source created

```
