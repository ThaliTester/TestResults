#### Test 506502789b39735_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
,E/SMD     (  289): DCD OFF
D/AndroidRuntime( 6085): 
D/AndroidRuntime( 6085): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6085): CheckJNI is OFF
D/AndroidRuntime( 6085): readGMSProperty: start
D/AndroidRuntime( 6085): readGMSProperty: already setted!!
D/AndroidRuntime( 6085): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6085): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6085): readGMSProperty: end
D/AndroidRuntime( 6085): addProductProperty: start
E/AffinityControl( 6085): AffinityControl: registerfunction enter
D/AndroidRuntime( 6085): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/Zygote  ( 6097): MountEmulatedStorage()
E/Zygote  ( 6097): v2
I/libpersona( 6097): KNOX_SDCARD checking this for 10338
I/libpersona( 6097): KNOX_SDCARD not a persona
I/SELinux ( 6097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6097 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1498
I/SELinux ( 6097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6097): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
D/AndroidRuntime( 6085): Shutting down VM
I/SurfaceFlinger(  258): id=12 createSurf (1x1),1 flag=404, uhalitest
D/TimaKeyStoreProvider( 6097): TimaSignature is unavailable
D/ActivityThread( 6097): Added TimaKeyStore provider
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1498): updateVisibility : ActivityRecord{4716e00 token=android.os.BinderProxy@ba0003f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1498): onTrimMemory. Level: 20
I/WebViewFactory( 6097): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6097): Time to load native libraries: 1 ms (timestamps 4851-4852)
I/LibraryLoader( 6097): Expected native library version number "",actual native library version number ""
W/art     ( 6085): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6097): Binding Chromium to main looper Looper (main, tid 1) {ddb5e21}
I/LibraryLoader( 6097): Expected native library version number "",actual native library version number ""
I/chromium( 6097): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6097): Initializing chromium process, singleProcess=true
,W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6097): ApplicationContext is null in ApplicationStatus,
,W/chromium( 6097): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6097): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6097): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6097): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6097): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6097): Local Branch: 
I/Adreno-EGL( 6097): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6097): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6097):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6097): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6097): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6097): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6097): CordovaWebView is running on device made by: samsung
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6097): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{145519d3 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6097): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/chromium( 6097): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6097): updateVisibility : ActivityRecord{32fb8e82 token=android.os.BinderProxy@4370f64 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6097): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6097): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6097
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/SRIB_DCS( 6097): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6097): Initialized EGL, version 1.4
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/OpenGLRenderer( 6097): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6097): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6097): showStatusIcon on inactive InputConnection,
W/ActivityManager( 1018): mDVFSHelper.release()
I/ActivityManager( 1018): Displayed Component not be shown by security: +748ms (total +39s198ms)
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{145519d3 u0 com.test.thalitest/.MainActivity t20} time:155458
I/Timeline( 6097): Timeline: Activity_idle id: android.os.BinderProxy@4370f64 time:155459
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1874): getCurrentCandidateView
,W/BindingManager( 6097): Cannot call determinedVisibility() - never saw a connection for the pid: 6097
,D/SamsungIME( 1874): Dismiss ExpandCandiate
,I/SamsungIME( 1874): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1874): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1874): KeybaordView init() : load resources
,D/JsMessageQueue( 6097): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1874): getCurrentKeyboard
,I/SamsungIME( 1874): getTextKeyboard
,D/SamsungIME( 1874): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/jxcore_app_log( 6097): JniHelper::setJavaVM(0xb748c448), pthread_self() = -1214371544
,D/JX-Cordova( 6097): jxcore cordova android initializing
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/jxcore-log( 6097): Initializing JXcore engine
W/jxcore-log( 6097): JXcore engine is ready
W/jxcore-log( 6097): Starting JXcore engine
E/SMD     (  289): DCD OFF
E/audit   ( 1872): type=1400 msg=audit(1450229679.709:205): avc:  denied  { ioctl } for  pid=6097 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1872):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1872): type=1300 msg=audit(1450229679.709:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=b a1=5451 a2=2 a3=becc6d58 items=0 ppid=304 ppcomm=main pid=6097 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1872): type=1320 msg=audit(1450229679.709:205): 
D/SSRM:n  ( 1018): SIOP:: AP = 290
W/jxcore-log( 6097): Platform android
W/jxcore-log( 6097): 
W/jxcore-log( 6097): Process ARCH arm
W/jxcore-log( 6097): 
,I/jxcore-log( 6097): JXcore Cordova bridge is ready!
I/jxcore-log( 6097): 
,W/jxcore-log( 6097): JXcore engine is started
I/Choreographer( 6097): Skipped 126 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6097): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/jxcore-log( 6097): Toggling radios to true,
I/jxcore-log( 6097): 
,D/BluetoothAdapter( 6097): enable(),
,D/BluetoothAdapter( 6097): enable(): BT is already enabled..!,
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6097, uid=10338,
W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6097, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6097, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6097, uid=10338
,I/wpa_supplicant( 1394): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6097): Radios toggled
I/jxcore-log( 6097): 
,I/jxcore-log( 6097): Got Device Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6097): 
,I/jxcore-log( 6097): Perf Test app loaded loaded
I/jxcore-log( 6097): 
,I/jxcore-log( 6097): check test folder
I/jxcore-log( 6097): 
,I/jxcore-log( 6097): found test : ./testFindPeers.js
I/jxcore-log( 6097): 
,I/wpa_supplicant( 1394): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1394): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1394): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48,
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/wpa_supplicant( 1394): Cmd 35605 not handled
I/wpa_supplicant( 1394): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1394): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1394): First Scan Start
I/wpa_supplicant( 1394): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering( 1018): InitialState.processMessage what=4
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1018): clearTetheredNotification()
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 5ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/jxcore-log( 6097): found test : ./testSendData.js
I/jxcore-log( 6097): 
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/CommandListener(  279): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1715): Read error: ssl=0xb79dde80: I/O error during system call, Connection timed out
,V/NativeCrypto( 1715): SSL shutdown failed: ssl=0xb79dde80: I/O error during system call, Broken pipe
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1,
,I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1018): Tagging socket 327 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,E/WifiNative-wlan0( 1018): do suspend true
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,I/qtaguid ( 1018): Untagging socket 327
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7bff7c8
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1212156616)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1681): Starting #8
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 1681): Message received 5007
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1212156616) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7bff7c8
,D/CommandListener(  279): Clearing all IP addresses on wlan0,
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 1000
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502],
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1474): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1474): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 5ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/Hs20UtilService( 1681): Starting #9,
I/Choreographer( 6097): Skipped 106 frames!  The application may be doing too much work on its main thread.
I/Hs20UtilService( 1681): Message received 5007
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/chromium( 6097): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
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
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,D/PhoneApp( 1474): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1474): FileWriteThread : threadType = 3
,V/AlarmManager( 1018): waitForAlarm result :4
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 0 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/SMD     (  289): DCD OFF
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_PushUtil( 5686): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5686): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5686): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5686): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5686): noConnectivity : true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6174): MountEmulatedStorage()
E/Zygote  ( 6174): v2
I/libpersona( 6174): KNOX_SDCARD checking this for 10108
,I/libpersona( 6174): KNOX_SDCARD not a persona
,I/SELinux ( 6174): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/SELinux ( 6174): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6174 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6174): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6174): TimaSignature is unavailable
,D/ActivityThread( 6174): Added TimaKeyStore provider
,I/MusicStore( 6174): Database version: 120
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/wpa_supplicant( 1394): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 1394): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1394): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1394): Trying to associate with  'G700'
I/wpa_supplicant( 1394): Re-associate with C0.AA.48
I/wpa_supplicant( 1394): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled,
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6174): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6174): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6174): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/wpa_supplicant( 1394): Cmd 35605 not handled
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1394): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,I/wpa_supplicant( 1394): wlan0: State: ASSOCIATING -> ASSOCIATED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1394): Associated with C0.AA.48
I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1394): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,E/Tethering( 1018): No numeric data
I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1394): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 1394): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true,
I/wpa_supplicant( 1394): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1394): Blacklist: Clear (temp) ,
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated,
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---,
D/HotspotTile( 1177): updateTetherState():false, false
V/JNIHelp ( 6174): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 5ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  279): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/ActivityThread( 6174): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6174): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@362aa43e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6174): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6174): GMSCore installation verified
,I/ConfigStore( 6174): Config Database version: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 6174): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6174): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6202): MountEmulatedStorage(),
E/Zygote  ( 6202): v2
I/libpersona( 6202): KNOX_SDCARD checking this for 10001
I/libpersona( 6202): KNOX_SDCARD not a persona,
I/SELinux ( 6202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6202 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GHttpClientFactory( 6174): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/TimaKeyStoreProvider( 6202): TimaSignature is unavailable
D/ActivityThread( 6202): Added TimaKeyStore provider
,E/dhcpcd  ( 6217): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6217): version 5.5.6 starting
,I/GoogleURLConnFactory( 6174): Using platform SSLCertificateSocketFactory
,E/dhcpcd  ( 6217): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5605:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/dhcpcd  ( 6217): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6217): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6217): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6217): bssid match
,I/dhcpcd  ( 6217): wlan0: rebinding lease of 192.168.1.132
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6229): MountEmulatedStorage()
,E/Zygote  ( 6229): v2
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6229 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/libpersona( 6229): KNOX_SDCARD checking this for 1000
I/libpersona( 6229): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 4190:com.sec.spp.push/u0a32 (adj 15): empty #31
I/SELinux ( 6229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 6229): TimaSignature is unavailable,
D/ActivityThread( 6229): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 35.041ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.492ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.459ms
,I/DIAGMON_AGENT( 6229): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/dhcpcd  ( 6217): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,I/dhcpcd  ( 6217): wlan0: leased 192.168.1.132 for 86400 seconds,
,W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_5605/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_4190/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6229): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6229): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6229): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6257): MountEmulatedStorage()
,E/Zygote  ( 6257): v2
I/libpersona( 6257): KNOX_SDCARD checking this for 10008
I/libpersona( 6257): KNOX_SDCARD not a persona
,I/SELinux ( 6257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6257): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6257 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1018): Killing 5171:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6257): TimaSignature is unavailable
,D/ActivityThread( 6257): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5260:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 02:34:44 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onCreate()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3694): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3694): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3694): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3694): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6282): MountEmulatedStorage()
E/Zygote  ( 6282): v2
I/libpersona( 6282): KNOX_SDCARD checking this for 10031
I/libpersona( 6282): KNOX_SDCARD not a persona
I/SELinux ( 6282): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6282 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 6282): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6282): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6282): TimaSignature is unavailable
,D/ActivityThread( 6282): Added TimaKeyStore provider
,I/SO_AGENT( 6282): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5705): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5705): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 5761): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5761): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5761): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5761): [SLFUCHKMGR] constructor called
,I/DBG_POLICYDM( 5705): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5705): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5705): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5171/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5260/cgroup.procs: No such file or directory
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5761): [OR] == isSIMCardReady false ==
,I/SA      ( 5761): [SCU] == networkStateCheck == false
I/SA      ( 5761): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5651:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/WifiNative-wlan0( 1018): do suspend true
,D/daemonapp( 1653): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3,
,D/accuweather( 1600): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1600): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/Zygote  ( 6299): MountEmulatedStorage()
,E/Zygote  ( 6299): v2
I/libpersona( 6299): KNOX_SDCARD checking this for 10121
I/libpersona( 6299): KNOX_SDCARD not a persona
,I/SELinux ( 6299): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6299): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6299): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6299 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check,
D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503,
E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1],
D/ConnectivityService( 1018): LTETest block dns file not exists
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,D/TimaKeyStoreProvider( 6299): TimaSignature is unavailable
,D/ActivityThread( 6299): Added TimaKeyStore provider
,W/ActivityManager( 1018): Failed to clear dns cache for: com.samsung.helphub
,E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1018):    accepting network in place of null
D/TelephonyNetworkFactory( 1474): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1474): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 1000
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ResourcesManager( 6299): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6299): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6299): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5651/cgroup.procs: No such file or directory
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
,I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
V/NetworkStats( 1018): updateIfacesLocked()
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 8ms
I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/QuickConnect( 6299): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/QuickConnect( 6299): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,I/QuickConnect( 6299): PeriphStartReceiver.onReceive - no need to start
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Zygote  ( 6319): MountEmulatedStorage()
,E/Zygote  ( 6319): v2
I/libpersona( 6319): KNOX_SDCARD checking this for 10141
I/libpersona( 6319): KNOX_SDCARD not a persona
,I/SELinux ( 6319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6319 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 5673:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,E/SELinux ( 6319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6319): TimaSignature is unavailable
,D/ActivityThread( 6319): Added TimaKeyStore provider
,W/ResourcesManager( 6319): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6319): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6319): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6319): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 01:34:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450229684406], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450229684384]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
,E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId,
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5673/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/BadgeProvider( 5812): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 5812): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 5812): sendNotify, [notify] : null
D/BadgeProvider( 5812): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5812): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5812): update, [UpdateCount] : 1
D/Launcher.Model( 1498): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6342): MountEmulatedStorage()
E/Zygote  ( 6342): v2
I/libpersona( 6342): KNOX_SDCARD checking this for 1000
I/libpersona( 6342): KNOX_SDCARD not a persona
,I/SELinux ( 6342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6342 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6342): TimaSignature is unavailable
,D/ActivityThread( 6342): Added TimaKeyStore provider
,D/SecurityLogAgent( 6342): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6342): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6342): StateMachine : Current State = 1
,D/SecurityLogAgent( 6342): StateMachine : Changed Current State = 1
,I/ActivityManager( 1018): Killing 5271:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2042): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2042): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 68241(3MB) AllocSpace objects, 17(324KB) LOS objects, 33% free, 24MB/36MB, paused 3.026ms total 174.108ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 5089): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5089): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10102
I/libpersona( 6364): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6364): MountEmulatedStorage()
I/libpersona( 6364): KNOX_SDCARD not a persona
E/Zygote  ( 6364): v2
,I/SELinux ( 6364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6364 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_5271/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6364): TimaSignature is unavailable
I/System.out( 5089): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityThread( 6364): Added TimaKeyStore provider
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6174): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2042): [AccountUtils] Account not ready
W/Kids    ( 2042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2042): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2042): 	at java.lang.Thread.run(Thread.java:818)
,E/SPPClientService( 6364): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6364): [SystemStateMoniter] Current Time : 162244
E/SPPClientService( 6364): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6364): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6364): [SystemStateMoniter] No Connect : true
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/SPPClientService( 6364): PushLog.txt file is not deleted.
,D/SPPClientService( 6364): PushLog.txt file is not deleted.
,D/SPPClientService( 6364): ============PushLog. stop!
,E/Zygote  ( 6382): MountEmulatedStorage(),
I/libpersona( 6382): KNOX_SDCARD checking this for 10110
E/Zygote  ( 6382): v2
I/libpersona( 6382): KNOX_SDCARD not a persona
,I/SELinux ( 6382): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6382 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5745:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/SELinux ( 6382): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
E/SELinux ( 6382): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,D/TimaKeyStoreProvider( 6382): TimaSignature is unavailable
,D/ActivityThread( 6382): Added TimaKeyStore provider
,E/SPPClientService( 6364): [[SystemStateMonitorService]] No Active Internet
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
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
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5745/cgroup.procs: No such file or directory
,W/GAv4    ( 6382): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6382): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/WebViewFactory( 6382): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6382): Time to load native libraries: 1 ms (timestamps 2745-2746)
I/LibraryLoader( 6382): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6382): Binding Chromium to main looper Looper (main, tid 1) {1a7d8d1d}
,I/LibraryLoader( 6382): Expected native library version number "",actual native library version number ""
,I/chromium( 6382): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6382): Initializing chromium process, singleProcess=true
,W/art     ( 6382): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6382): ApplicationContext is null in ApplicationStatus
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
,I/NSApplication( 6382): Starting up...
,W/AudioManagerAndroid( 6382): Requires BLUETOOTH permission
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6438): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6438 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6438): v2
I/libpersona( 6438): KNOX_SDCARD checking this for 10077,
I/libpersona( 6438): KNOX_SDCARD not a persona
I/SELinux ( 6438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Killing 5642:com.android.mms/u0a41 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 5781:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #32
,I/SELinux ( 6438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6438): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6438): TimaSignature is unavailable
,D/ActivityThread( 6438): Added TimaKeyStore provider
,D/CountryDetector( 1018): No listener is left
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5781/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5642/cgroup.procs: No such file or directory
,E/SMD     (  289): DCD OFF
,D/WaitQueueForNetworkActivate( 5990): notifyNetworkActivated
,W/ContextImpl( 5990): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5990): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/InitializeManagerStateMachine( 5990): execute::IDLE:EXECUTE
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/InitializeManagerStateMachine( 5990): exit::IDLE
D/InitializeManagerStateMachine( 5990): entry::NETWORK_CHECK
,I/Hs20UtilService( 1681): Starting #10
,I/Hs20UtilService( 1681): Message received 5007
,D/InitializeManagerStateMachine( 5990): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5990): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5990): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5990): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5990): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5990): entry::SUCCESS
D/hcjo    ( 5990): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/hcjo    ( 5990): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5990): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,D/InitializeManagerStateMachine( 5990): exit::SUCCESS
D/InitializeManagerStateMachine( 5990): entry::IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 3437:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1681): Starting #11
,I/Hs20UtilService( 1681): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1681): Starting #12
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/Hs20UtilService( 1681): Message received 5007
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1681): Starting #13
I/Hs20UtilService( 1681): Message received 5007
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState,
D/SecContentProvider2( 1018): mCursor = null
D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState,
,D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5686): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5686): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5686): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5686): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6174): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6229): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6229): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5705): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5705): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5705): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5705): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_3437/cgroup.procs: No such file or directory
,I/FOTA_Client( 6257): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6257): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 02:34:46 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3694): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3694): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3694): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3694): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3694): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3694): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3694): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5705): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5705): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5705): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5705): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/art     ( 1715): Explicit concurrent mark sweep GC freed 23917(1386KB) AllocSpace objects, 8(162KB) LOS objects, 39% free, 7MB/12MB, paused 1.049ms total 55.528ms
,I/SA      ( 5761): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,D/GCM     ( 1715): Connected
I/SA      ( 5761): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5761): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5761): [OR] == isSIMCardReady false ==
,I/SA      ( 5761): [SCU] == networkStateCheck == true
I/SA      ( 5761): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5761): isChinaCountryCode : false
I/SA      ( 5761): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5761): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5705): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,D/GCM     ( 1715): Message class com.google.f.a.a.p
,I/SA      ( 5761): [OR] GetMyCountryZoneTask
,I/SA      ( 5761): [OR] onReceive END
,V/DownloadManager( 1227): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5761): [SRS] prepareGetMyCountryZone
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5705): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
D/accuweather( 1600): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/SA      ( 5761): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5761): [SSP] query invoked
I/DBG_POLICYDM( 5705): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5705): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,D/daemonapp( 1653): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,I/DBG_POLICYDM( 5705): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
D/accuweather( 1600): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1600): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1600): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1600): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,D/accuweather( 1600): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5705): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered,
,D/accuweather( 1600): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/SA      ( 5761): [TPMU] GetMccFromDB : null
I/SA      ( 5761): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5761): [TPM] isNoProxy(default) : true
,D/QuickConnect( 6299): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6299): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6299): PeriphStartReceiver.onReceive - no need to start
,I/DBG_POLICYDM( 5705): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/File    ( 5761): fail readDirectory() errno=2
I/DBG_POLICYDM( 5705): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6342): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6342): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6342): StateMachine : Current State = 1
,D/SecurityLogAgent( 6342): StateMachine : Changed Current State = 1
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2042): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2042): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6364): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6364): [SystemStateMoniter] Current Time : 163786
,E/SPPClientService( 6364): [SystemStateMoniter] No Connect : false
,I/System.out( 5089): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/hcjo    ( 5990): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5990): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5990): exit::IDLE
,D/InitializeManagerStateMachine( 5990): entry::NETWORK_CHECK
V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InitializeManagerStateMachine( 5990): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5990): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5990): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5990): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5990): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5990): entry::SUCCESS
D/hcjo    ( 5990): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5990): AutoUpdateTriggerManager:IDLE:notifyNextTime
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 5990): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5990): exit::SUCCESS
,D/InitializeManagerStateMachine( 5990): entry::IDLE
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2042): [AccountUtils] Account not ready
W/Kids    ( 2042): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2042): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2042): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2042): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2042): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2042): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2042): 	at java.lang.Thread.run(Thread.java:818)
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/SA      ( 5761): [RC New] Execute method=[GET] start
,I/SA      ( 5761): [RC New] Security=[true],
,I/System.out( 5761): Thread-975(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5761): Thread-975(ApacheHTTPLog):isSBSettingEnabled false,
I/System.out( 5761): Thread-975(ApacheHTTPLog):isShipBuild true
I/System.out( 5761): Thread-975(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5761): Thread-975(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10036
,I/jxcore-log( 6097): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 6097): 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/SA      ( 5761): [RC New] [v2liruge] api execute + 679
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
,I/SA      ( 5761): [SCU] saveMccToPreferece End
,I/SA      ( 5761): [RC New] executeRequest [v2liruge] end. 735
I/SA      ( 5761): [RC New] Execute end
,I/SA      ( 5761): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5761): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6217): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6217): wlan0: sendmsg: Cannot assign requested address
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503],
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295,
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524295
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6174): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6174): Stop autocaching.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6492): MountEmulatedStorage()
I/libpersona( 6492): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6492): v2
I/libpersona( 6492): KNOX_SDCARD not a persona
I/SELinux ( 6492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6492 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/SELinux ( 6492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6492): TimaSignature is unavailable
,D/ActivityThread( 6492): Added TimaKeyStore provider
,W/ResourcesManager( 6492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6492): VM with version 2.1.0 has multidex support
I/MultiDex( 6492): install
I/MultiDex( 6492): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/SMD     (  289): DCD OFF
,W/ActivityThread( 6492): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6492): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@25e68948: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6492): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1018): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1715): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1715): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2042): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6492): callingUid 10011, callindPid: 6492
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
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
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2042): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1811): [203] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 6174): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6174): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  258): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 166907
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3474)
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,E/Watchdog( 1018): !@Sync 5
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5686): mConnectivityHandler : connected
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/PCWCLIENTTRACE_AccountUtil( 5686): [hasSamungAccount] - No Samsung Account
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5686): [GetString-S]
,I/ReactiveServiceManager( 5686): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5686): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5686): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5686): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5686): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5686): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5686): [ensureRegistration] - No Samsung account
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 31545(1685KB) AllocSpace objects, 6(104KB) LOS objects, 33% free, 24MB/36MB, paused 2.520ms total 170.740ms
,D/Finsky  ( 5344): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5344): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5344): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  289): DCD OFF
,I/dhcpcd  ( 6217): wlan0: sending IPv6 Router Solicitation,
,I/ActivityManager( 1018): Killing 5830:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31,
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5830/cgroup.procs: No such file or directory
,V/AlarmManager( 1018): waitForAlarm result :4,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1715): Vacuum at: now=1450229694334 tag=VacuumService
,I/GoogleURLConnFactory( 1715): Using platform SSLCertificateSocketFactory
,W/Uploader( 1715): No account for auth token provided
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1715): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1715): (HTTPLog)-Static: isShipBuild true
I/System.out( 1715): (HTTPLog)-Thread-205-939466911: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1715): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,I/qtaguid ( 1715): Tagging socket 61 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,E/SMD     (  289): DCD OFF
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715):  no longer exists, so no auth token.
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/Uploader( 1715): No account for auth token provided
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
E/Uploader( 1715): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1715): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1715): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1715): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1715): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1715): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,I/System.out( 1715): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1715): Tagging socket 55 with tag 120100000000{4609,0} for uid -1, pid: 1715, getuid(): 10011
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1715): (10) POSIX Error : 11 SQLite Error : 3850
,I/dhcpcd  ( 6217): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6217): wlan0: no IPv6 Routers available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5990): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5990): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5990): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5990): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5990): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5990): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5990): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5990): entry::IDLE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5990): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5990): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5990): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5990): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5990): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5990): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5990): entry::IDLE
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{1fcf21a1 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :4
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5344): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5344): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5344): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6018): Sync error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 275592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true,
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
,I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6018): Sync error
,E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 308035, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/jxcore-log( 6097): Connected to the server!
I/jxcore-log( 6097): 
,I/chromium( 6097): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 11
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1715): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1715): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1715): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1715): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1715): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1715): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1715): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5344): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5344): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5344): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5344): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5344): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5344): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5344): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5344): Ignoring header User-Agent because its value was null.
,I/System.out( 5344): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 5344): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5344): (HTTPLog)-Static: isShipBuild true
I/System.out( 5344): (HTTPLog)-Thread-908-49468536: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5344): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 503 for uid 10026
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 5344): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 12
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 54237(3MB) AllocSpace objects, 109(1762KB) LOS objects, 33% free, 24MB/36MB, paused 2.490ms total 145.235ms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6018): Sync error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 400307, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 14
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 390s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 15
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/bootchecker(  312): bootchecker wake up!!
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 16
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 4
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 17
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 455s ago,
,I/ServiceManager(  316): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  316): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6018): Sync error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 554899, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 18
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  316): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  316): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/Atfwd_Daemon(  316): Stop the daemon....,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 19
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 20
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 21
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 600s ago
,E/Watchdog( 1018): !@Sync 22
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 23
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 24
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 680s ago
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 25
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 26
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1,
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6018): Sync error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 812594, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 27
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 765s ago
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 28,
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 29
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 30
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/PowerManagerService( 1018): [PWL] Off : 855s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 31
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 32
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 33
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 2632): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 950s ago,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 34
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/GCM     ( 1715): Message class com.google.f.a.a.i
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 35
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 36
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1050s ago,
,E/Watchdog( 1018): !@Sync 37,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 38
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 39
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 1018): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 1018): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 1018): Updating Usage Statistics in DB @ 1450230738287
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/NetworkDataUsageDb( 1018): ::getAppControlDB: DB is Created 
,I/NetworkDataUsageDb( 1018): ::isTableExists: Table exists 
,I/ApplicationUsage( 1018): Done Updating Usage Statistics in DB @ 1450230738634
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 40
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1155s ago,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 41
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 42
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 43
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6018): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6018): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6018): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6018): Soft error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6018): Sync error
E/BooksSync( 6018): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6018): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6018): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1327726, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,W/ResourcesManager( 2485): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 44
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/PowerManagerService( 1018): [PWL] Off : 1265s ago
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 45
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 46
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,E/SMD     (  289): DCD OFF
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 47
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1380s ago
,E/Watchdog( 1018): !@Sync 48
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,E/Watchdog( 1018): !@Sync 49
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 1018): !@Sync 50
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 51
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1500s ago,
,E/Watchdog( 1018): !@Sync 52
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 53
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 54
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 55
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 56
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/PowerManagerService( 1018): [PWL] Off : 1625s ago
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged,
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 57,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/Watchdog( 1018): !@Sync 58
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 59
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 60
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1755s ago
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 61
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 62
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 63
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF,
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 64
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4338, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1426): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1426): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2632): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2632): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  289): DCD OFF
,E/SMD     (  289): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  289): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ActivityManager( 1018): Killing 6319:com.android.email/u0a141 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6299:com.samsung.android.sconnect/u0a121 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 5761:com.osp.app.signin/u0a36 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 5705:com.policydm/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6282:com.sec.android.soagent/u0a31 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 6257:com.sec.android.fotaclient/u0a8 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6229:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 6202:com.sec.android.cloudagent/u0a1 (adj 15): empty for 1800s
I/ActivityManager( 1018): Killing 5686:com.sec.pcw.device/1000 (adj 15): empty for 1800s
,I/ActivityManager( 1018): Killing 5812:com.sec.android.provider.badge/u0a68 (adj 15): empty for 1801s
I/ActivityManager( 1018): Killing 5584:com.android.defcontainer/u0a3 (adj 15): empty for 1869s
I/ActivityManager( 1018): Killing 5974:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty for 1878s
,I/ActivityManager( 1018): Killing 5926:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty for 1879s
I/ActivityManager( 1018): Killing 5907:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1879s
,I/ActivityManager( 1018): Killing 5890:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1879s
I/ActivityManager( 1018): Killing 5871:com.sec.android.app.soundalive/u0a48 (adj 15): empty for 1879s
I/ActivityManager( 1018): Killing 5846:com.wsomacp/u0a23 (adj 15): empty for 1880s
I/ActivityManager( 1018): Killing 4951:com.sec.android.gallery3d/u0a39 (adj 15): empty for 1880s
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ProcessStatsService( 1018): Prepared write state in 17ms
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,I/Icing   ( 2042): Performing maintenance.
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,W/Icing   ( 2042): Received bad json for section weights override -- ignoring.
,W/Icing   ( 2042): Received bad json for corpus context scoring override -- ignoring.
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,V/NetworkStats( 1018): performPollLocked(flags=0x3)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,E/SMD     (  289): DCD OFF
,V/NetworkStats( 1018): performPollLocked() took 6ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/webhistory
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/webhistory without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2042): Aggregate from 1450229161054 (log), 1450229161054 (data)
,D/GCM     ( 1715): Message class com.google.f.a.a.i
,W/Icing   ( 2042): Failed to get auth token for account:<redacted>, error:BadAuthentication
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2: email
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2: email without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1715): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/webhistory
,I/GLSUser ( 1715): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/webhistory without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1715): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1715): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1715): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Icing   ( 2042): Failed to get auth token for account:<redacted>, error:BadAuthentication
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.googlequicksearchbox
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7300): MountEmulatedStorage()
E/Zygote  ( 7300): v2
I/libpersona( 7300): KNOX_SDCARD checking this for 10052
I/libpersona( 7300): KNOX_SDCARD not a persona
I/SELinux ( 7300): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.UdcSettingBroadcastReceiver: pid=7300 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,I/SELinux ( 7300): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 7300): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7300): TimaSignature is unavailable
,D/ActivityThread( 7300): Added TimaKeyStore provider
,I/Icing   ( 2042): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 2042): Performing maintenance usage 2094730 budget 4490054469 free 99.953% index free 99.914% purge? false target 1700816950
,I/Icing   ( 2042): Skipping storage state: opt-out
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 6342:com.samsung.android.securitylogagent/1000 (adj 15): empty for 1800s
,D/LocationManagerService( 1018): getProviders()=[passive]
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7320): MountEmulatedStorage()
E/Zygote  ( 7320): v2
,I/libpersona( 7320): KNOX_SDCARD checking this for 10014
I/libpersona( 7320): KNOX_SDCARD not a persona
,I/SELinux ( 7320): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=7320 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7320): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 6382:com.google.android.apps.magazines/u0a110 (adj 15): empty for 1800s
,E/SELinux ( 7320): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7320): TimaSignature is unavailable
,D/ActivityThread( 7320): Added TimaKeyStore provider
,I/art     (  304): Explicit concurrent mark sweep GC freed 8708(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 758us total 29.568ms
,I/ActivityManager( 1018): Killing 6438:com.android.chrome/u0a77 (adj 15): empty for 1800s
,I/ProcessStatsService( 1018): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-14-49.bin
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5686/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5812/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5846/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10001/pid_6202/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_5584/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_6257/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_5926/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6229/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10141/pid_6319/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5890/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10031/pid_6282/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5871/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5705/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5907/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_4951/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10121/pid_6299/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10052/pid_5974/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10036/pid_5761/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6342/cgroup.procs: No such file or directory
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 631us total 16.880ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.410ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_6382/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_6438/cgroup.procs: No such file or directory
,E/SQLiteLog( 1715): (10) POSIX Error : 11 SQLite Error : 3850
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  289): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 1890s ago,
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7340): 
D/AndroidRuntime( 7340): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7340): CheckJNI is OFF
D/AndroidRuntime( 7340): readGMSProperty: start
D/AndroidRuntime( 7340): readGMSProperty: already setted!!
D/AndroidRuntime( 7340): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 7340): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 7340): readGMSProperty: end
D/AndroidRuntime( 7340): addProductProperty: start
E/Watchdog( 1018): !@Sync 65
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
E/AffinityControl( 7340): AffinityControl: registerfunction enter
D/AndroidRuntime( 7340): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{766075891}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1018): !@killApplicatoin: 10338, uninstall pkg
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 6097:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
W/PackageSettings( 1018): Skipping PackageSetting{1f8ea57e com.example.hello/10346} due to missing metadata
I/WindowState( 1018): WIN DEATH: Window{1cf8d4ed u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  258): id=13 Removed NainActivit (-2/8)
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{145519d3 u0 com.test.thalitest/.MainActivity t20}
D/InputDispatcher( 1018): Focus left window: 6097
W/ActivityManager( 1018): Spurious death for ProcessRecord{e85c8b0 6097:com.test.thalitest/u0a338}, curProc for 6097: null
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
I/ActivityManager( 1018):   Force finishing activity ActivityRecord{145519d3 u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{145519d3 u0 com.test.thalitest/.MainActivity t20 f}
W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
D/InputDispatcher( 1018): Focused application released
I/art     ( 4061): Explicit concurrent mark sweep GC freed 17803(1031KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 966us total 47.839ms
E/SamsungIME( 1874): mOCRHelper is null
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1811): Ignoring removeGeofence because network location is disabled.
I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Dec 16 03:04:51 GMT+01:00 2015
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
I/KLMS-2.5.123: ( 3694): KLMSAbstractReciever(): onReceive().END.
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1018): no available spell checker services found
I/splitIntent( 1018): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1018): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1018): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onCreate()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.123: ( 3694): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
E/Zygote  ( 7353): MountEmulatedStorage()
E/Zygote  ( 7353): v2
I/libpersona( 7353): KNOX_SDCARD checking this for 10090
I/libpersona( 7353): KNOX_SDCARD not a persona
I/SELinux ( 7353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7353 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 3694): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/SELinux ( 7353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux ( 7353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): PACKAGE_REMOVED
D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
D/RegisteredServicesCache( 1463): empty dynamic service
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): listeningToPackageRemoved().START
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/TimaKeyStoreProvider( 7353): TimaSignature is unavailable
D/ActivityThread( 7353): Added TimaKeyStore provider
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
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
D/TaskPersister( 1018): removeObsoleteFile: deleting file=20_task.xml
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
D/elm:15121( 7353): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 7353): ELMEngine.ELMEngine( context ).
D/elm:15121( 7353): MDMBridge.setEnterpriseBridge()
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
D/elm:15121( 7353): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:15121( 7353): ElmAgentService : onCreate()
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): listeningToPackageRemoved().END
D/elm:15121( 7353): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 7353): MainReceiver.listeningToPackageRemoved()
I/KLMS-2.5.123: ( 3694): KLMSIntentService(): onDestroy()
D/elm:15121( 7353): MDMBridge.getInstance()
D/elm:15121( 7353): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:15121( 7353): MDMBridge.getAllLicenseInfoFromSDK()
I/art     ( 1018): Explicit concurrent mark sweep GC freed 33105(2MB) AllocSpace objects, 8(181KB) LOS objects, 33% free, 24MB/36MB, paused 3.687ms total 284.425ms
D/elm:15121( 7353): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 5948:com.google.android.apps.plus/u0a117 (adj 15): empty for 1804s
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7370): MountEmulatedStorage()
I/libpersona( 7370): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7370): v2
I/libpersona( 7370): KNOX_SDCARD not a persona
I/SELinux ( 7370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/TimaKeyStoreProvider( 7370): TimaSignature is unavailable
D/ActivityThread( 7370): Added TimaKeyStore provider
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_LOG( 7370): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 7370): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 7370): new DMDBOpenHelper instance
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PCWCLIENTTRACE_PushUtil( 7370): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7370): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7370): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7370): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 7385): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7385 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/Zygote  ( 7385): v2
I/libpersona( 7385): KNOX_SDCARD checking this for 10029
I/SELinux ( 7385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 7385): KNOX_SDCARD not a persona
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1018): Killing 5089:com.google.android.talk/u0a102 (adj 15): empty for 1805s
I/SELinux ( 7385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PackageManager( 1018): delete codoeFile: 
E/SELinux ( 7385): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AASA_removePackage( 1018): UID=10338 Target=com.test.thalitest
D/PackageManager( 1018): result of delete: 1{766075891}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
W/libprocessgroup( 1018): failed to open /acct/uid_10117/pid_5948/cgroup.procs: No such file or directory
D/AndroidRuntime( 7340): Shutting down VM
D/TimaKeyStoreProvider( 7385): TimaSignature is unavailable
D/ActivityThread( 7385): Added TimaKeyStore provider
I/FeatureConfig( 7385): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7402): MountEmulatedStorage()
E/Zygote  ( 7402): v2
I/libpersona( 7402): KNOX_SDCARD checking this for 10036
I/libpersona( 7402): KNOX_SDCARD not a persona
I/SELinux ( 7402): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.msc.sa.selfupdate.SelfUpgradeReceiver: pid=7402 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 6174:com.google.android.music:main/u0a108 (adj 15): empty for 1802s
I/SELinux ( 7402): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 7402): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 7385): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider( 7402): TimaSignature is unavailable
D/ActivityThread( 7402): Added TimaKeyStore provider
W/ResourcesManager( 7385): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SA      ( 7402): [SSP] onCreated
W/ResourcesManager( 7385): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
I/SA      ( 7402): [TPM] There is no property file
I/SA      ( 7402): [SCU] isHaveSA() - false
I/SA      ( 7402): [TPM] getModelProperty : null
I/SA      ( 7402): [TPM] getCSCProperty : null
I/SA      ( 7402): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 7402): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 7402): [DM] TFT FEATURE: false
I/SA      ( 7402): [DM] init START
W/ResourcesManager( 7385): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/SA      ( 7402): [DM] This device is not a Vodafone
W/ResourcesManager( 7385): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 7385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourceType( 7402): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/GalaxyFinderApplication( 7385): system/finder_cp/cpdata.xml file not found
W/ResourceType( 7402): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7402): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 7402): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/libprocessgroup( 1018): failed to open /acct/uid_10102/pid_5089/cgroup.procs: No such file or directory
W/ResourceType( 7402): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/libprocessgroup( 1018): failed to open /acct/uid_10108/pid_6174/cgroup.procs: No such file or directory
W/ResourceType( 7402): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 7402): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/art     ( 7340): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/SA      ( 7402): [SCU] isHaveSA() - false
I/SA      ( 7402): support phone number id : false
I/SA      ( 7402): [DM] Supports Ref Jpn : true
I/SA      ( 7402): [DM] init END
I/SA      ( 7402): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 7402): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 6492:com.google.android.gms.wearable/u0a11 (adj 15): empty for 1802s
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7421): MountEmulatedStorage()
I/libpersona( 7421): KNOX_SDCARD checking this for 10039
E/Zygote  ( 7421): v2
I/libpersona( 7421): KNOX_SDCARD not a persona
I/SELinux ( 7421): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 7421): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7421 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 7421): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7421): TimaSignature is unavailable
D/ActivityThread( 7421): Added TimaKeyStore provider
W/ResourcesManager( 7421): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 7421): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
W/libprocessgroup( 1018): failed to open /acct/uid_10011/pid_6492/cgroup.procs: No such file or directory
E/SQLiteLog( 7421): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 7421): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 7421): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7421): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7421): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7421): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7421): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 7421): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7421): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7421): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7421): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7421): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7421): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7421): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/NearbySource( 7421): Nearby Source Create!
D/NearbyContext( 7421): Nearby Context Create!
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7421): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 7421): Samsung link source created

```
