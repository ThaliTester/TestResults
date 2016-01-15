#### Test 56204092c98eeae_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
D/AndroidRuntime( 6134): 
D/AndroidRuntime( 6134): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6134): CheckJNI is OFF
D/AndroidRuntime( 6134): readGMSProperty: start
D/AndroidRuntime( 6134): readGMSProperty: already setted!!
D/AndroidRuntime( 6134): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6134): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6134): readGMSProperty: end
D/AndroidRuntime( 6134): addProductProperty: start
E/AffinityControl( 6134): AffinityControl: registerfunction enter
D/AndroidRuntime( 6134): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1017): inState():  stateMachine is null !!
I/PersonaManagerService( 1017): PersonaId don't exist
I/ActivityManager( 1017): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1017): mDVFSHelper.acquire()
D/FocusedStackFrame( 1017): Set to : 0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1017): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1017): *FMB* installDecor flags : 25362712
E/Zygote  ( 6147): MountEmulatedStorage()
E/Zygote  ( 6147): v2
I/libpersona( 6147): KNOX_SDCARD checking this for 10338
I/libpersona( 6147): KNOX_SDCARD not a persona
I/SELinux ( 6147): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6147 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1017): Focused application set to: xxxx
D/InputDispatcher( 1017): Focus left window: 1484
D/AndroidRuntime( 6134): Shutting down VM
I/SELinux ( 6147): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1017): *FMB* isFloatingMenuEnabled return false
E/SELinux ( 6147): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6147): TimaSignature is unavailable
D/ActivityThread( 6147): Added TimaKeyStore provider
V/WindowManager( 1017): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1017): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1017): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1017):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{3a39b0a2 token=android.os.BinderProxy@119d87ef {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6147): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6147): Time to load native libraries: 1 ms (timestamps 7017-7018)
I/LibraryLoader( 6147): Expected native library version number "",actual native library version number ""
W/art     ( 6134): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
V/WebViewChromiumFactoryProvider( 6147): Binding Chromium to main looper Looper (main, tid 1) {1d407d78}
I/LibraryLoader( 6147): Expected native library version number "",actual native library version number ""
I/chromium( 6147): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6147): Initializing chromium process, singleProcess=true
W/art     ( 6147): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6147): ApplicationContext is null in ApplicationStatus
W/chromium( 6147): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6147): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6147): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6147): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6147): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6147): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6147): Local Branch: 
I/Adreno-EGL( 6147): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6147): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6147):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
E/SMD     (  290): DCD OFF
W/art     ( 6147): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6147): onDetachedFromWindow called when already detached. Ignoring
D/PhoneWindow( 6147): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6147): *FMB* installDecor flags : 8456448
D/SystemWebViewEngine( 6147): CordovaWebView is running on device made by: samsung
W/art     ( 6147): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6147): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1017): Activity pause timeout for ActivityRecord{31ab4e63 u0 com.test.thalitest/.MainActivity t20}
D/OpenGLRenderer( 6147): Render dirty regions requested: true
D/ActivityManager( 1017): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1017): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1017): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1017): handleActiveUserChange for user 0
D/PersonaManagerService( 1017): getPersonasForUser(): returning null!
W/chromium( 6147): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6147): updateVisibility : ActivityRecord{71062fd token=android.os.BinderProxy@16ec2a7 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
D/PhoneWindow( 6147): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6147): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=404, NainActivit
D/InputDispatcher( 1017): Focus entered window: 6147
D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
D/SRIB_DCS( 6147): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6147): Initialized EGL, version 1.4
D/OpenGLRenderer( 6147): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6147): Enabling debug mode 0
D/InputMethodManagerService( 1017): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
I/ActivityManager( 1017): Displayed Component not be shown by security: +721ms (total +42s53ms)
W/ActivityManager( 1017): mDVFSHelper.release()
W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/Timeline( 1017): Timeline: Activity_windows_visible id: ActivityRecord{31ab4e63 u0 com.test.thalitest/.MainActivity t20} time:157601
W/IInputConnectionWrapper( 6147): showStatusIcon on inactive InputConnection
I/Timeline( 6147): Timeline: Activity_idle id: android.os.BinderProxy@16ec2a7 time:157602
I/SurfaceFlinger(  259): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  259): id=13 Removed uhalitest (-2/9)
I/SamsungIME( 1863): getCurrentCandidateView
W/BindingManager( 6147): Cannot call determinedVisibility() - never saw a connection for the pid: 6147
D/SamsungIME( 1863): Dismiss ExpandCandiate
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): getDebugLevel  : 0x4f4c
I/SamsungIME( 1863): KeybaordView init() : load resources
I/SamsungIME( 1863): getCurrentKeyboard
I/SamsungIME( 1863): getTextKeyboard
D/JsMessageQueue( 6147): Set native->JS mode to OnlineEventsBridgeMode
D/SamsungIME( 1863): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/jxcore_app_log( 6147): JniHelper::setJavaVM(0xb8cea448), pthread_self() = -1188816256
,D/JX-Cordova( 6147): jxcore cordova android initializing
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/art     ( 6147): Suspending all threads took: 11.732ms
,W/jxcore-log( 6147): Initializing JXcore engine
W/jxcore-log( 6147): JXcore engine is ready
,I/art     ( 6147): Background partial concurrent mark sweep GC freed 25681(1647KB) AllocSpace objects, 2(3MB) LOS objects, 39% free, 17MB/28MB, paused 13.918ms total 59.462ms
,W/jxcore-log( 6147): Starting JXcore engine
,E/audit   ( 1894): type=1400 msg=audit(1452883532.800:205): avc:  denied  { ioctl } for  pid=6147 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1894):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1894): type=1300 msg=audit(1452883532.800:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be957d58 items=0 ppid=316 ppcomm=main pid=6147 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1894): type=1320 msg=audit(1452883532.800:205): 
,W/jxcore-log( 6147): Platform android
W/jxcore-log( 6147): 
W/jxcore-log( 6147): Process ARCH arm
W/jxcore-log( 6147): 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,I/jxcore-log( 6147): JXcore Cordova bridge is ready!
I/jxcore-log( 6147): 
,W/jxcore-log( 6147): JXcore engine is started
I/Choreographer( 6147): Skipped 146 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6147): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/jxcore-log( 6147): Toggling radios to true,
I/jxcore-log( 6147): 
,D/BluetoothAdapter( 6147): enable(),
,D/BluetoothAdapter( 6147): enable(): BT is already enabled..!,
,D/SecContentProvider( 1017): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1017): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1017): mCursor = null
,D/WifiService( 1017): setWifiEnabled: true pid=6147, uid=10338
,W/ActivityManager( 1017): Permission Denial: getCurrentUser() from pid=6147, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1017): Failed getting userId using ActivityManagerNative
W/WifiService( 1017): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6147, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1017): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1017): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1017): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1017): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1017): name = wifi_on
,I/WifiService( 1017): disconnect: pid=6147, uid=10338
,I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6147): Radios toggled
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): Got Device Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): Perf Test app loaded loaded
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): check test folder
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): found test : ./testFindPeers.js
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): found test : ./testSendData.js
I/jxcore-log( 6147): 
,I/wpa_supplicant( 1383): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1383): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1383): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1383): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1383): Cmd 35605 not handled
E/WifiStateMachine( 1017): WifiStateMachine: Leaving Connected state
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/Tethering( 1017): InitialState.processMessage what=4
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1383): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1383): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1383): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1383): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1383): First Scan Start
I/wpa_supplicant( 1383): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1017): No numeric data
,D/Tethering( 1017): sendTetherStateChangedBroadcast 0, 0, 0
,D/Tethering( 1017): clearTetheredNotification()
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1017): interfaceStatusChanged wlan0, false
D/HotspotTile( 1177): updateTetherState():false, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,V/NetworkStats( 1017): performPollLocked() took 5ms
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1017): do suspend true,
,D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/WifiP2pService( 1017): InactiveState{ what=143375 }
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
V/NativeCrypto( 1729): Read error: ssl=0xb910ef78: I/O error during system call, Connection timed out
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
V/NativeCrypto( 1729): SSL shutdown failed: ssl=0xb910ef78: I/O error during system call, Broken pipe
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,E/WifiStateMachine( 1017): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1383): wlan0: Setting scan request: 0 sec 0 usec
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/qtaguid ( 1017): Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1017, getuid(): 1000
,E/WifiNative-wlan0( 1017): do suspend true
D/WifiP2pService( 1017): InactiveState{ what=143375 }
I/qtaguid ( 1017): Untagging socket 350
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #8
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1641): Message received 5007
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  280): Clearing all IP addresses on wlan0
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 0 for uid 1000
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
,D/ConnectivityService( 1017): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityService( 1017): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/ConnectivityService( 1017): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/CSLegacyTypeTracker( 1017): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1017): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/TelephonyNetworkFactory( 1457): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
,E/Zygote  ( 6204): MountEmulatedStorage(),
E/Zygote  ( 6204): v2
I/libpersona( 6204): KNOX_SDCARD checking this for 10102
I/libpersona( 6204): KNOX_SDCARD not a persona
,I/SELinux ( 6204): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6204 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6204): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6204): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiNetworkAgent( 1017): NetworkAgent: NetworkAgent channel lost
,I/Choreographer( 6147): Skipped 119 frames!  The application may be doing too much work on its main thread.
I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/chromium( 6147): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null,
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1017): MasterInitialState.processMessage what=3
V/NetworkStats( 1017): updateIfacesLocked()
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
,D/ConnectivityService( 1017): nai.networkMonitor.doQuit()
E/ConnectivityService( 1017): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): doQuit - quitNow()
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/EntConnectivity( 1017): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked() took 6ms
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/TimaKeyStoreProvider( 6204): TimaSignature is unavailable
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ActivityThread( 6204): Added TimaKeyStore provider
,W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
D/PhoneApp( 1457): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1457): FileWriteThread : threadType = 3
,I/Babel_SMS( 6204): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6204): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6204): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6204): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6204): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6204): MmsConfig.loadFromResources
,E/Babel_SMS( 6204): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6204): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  285): getCameraInfo: X
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/art     ( 6204): Suspending all threads took: 6.297ms
,W/Settings( 6204): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6204): startup - clean
,I/Babel   ( 6204): deleted: false for 0
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #9
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6204): Unsupported mime audio/evrc
,W/AudioCapabilities( 6204): Unsupported mime audio/qcelp
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6204): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6204): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6204): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6204): Unsupported mime audio/x-ima
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6204): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6204): Unsupported mime audio/evrc
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6204): Unsupported mime video/wvc1
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6204): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6204): Unsupported mime video/wvc1
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6204): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6204): Unsupported mime video/mp43
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/ApplicationPolicy( 1017): updateDataUsageMap
,W/VideoCapabilities( 6204): Unsupported mime video/sorenson
,W/VideoCapabilities( 6204): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6204): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6204): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1017): Killing 5619:com.sec.android.app.camera/u0a135 (adj 15): empty #31
,I/vclib   ( 6204): onServiceConnected
,W/Babel   ( 6204): Attempted to change video mute state without an active call.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/libprocessgroup( 1017): failed to open /acct/uid_10135/pid_5619/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5775): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5775): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5775): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5775): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5775): noConnectivity : true
,I/ActivityManager( 1017): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6246 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/Zygote  ( 6246): MountEmulatedStorage()
E/Zygote  ( 6246): v2
I/libpersona( 6246): KNOX_SDCARD checking this for 10108
I/libpersona( 6246): KNOX_SDCARD not a persona
,I/SELinux ( 6246): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6246): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6246): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 711us total 23.234ms
,D/TimaKeyStoreProvider( 6246): TimaSignature is unavailable
,D/ActivityThread( 6246): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 595us total 16.329ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.446ms
,I/MusicStore( 6246): Database version: 120
,I/wpa_supplicant( 1383): nl80211: Received scan results (8 BSSes),
I/wpa_supplicant( 1383): wlan0: Setting scan request: 8 sec 0 usec
D/WifiMonitor( 1017): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 1383): Trying to associate with SSID '4E47373030'
,I/wpa_supplicant( 1383): Trying to associate with  'G700'
I/wpa_supplicant( 1383): Re-associate with C0.AA.48
I/wpa_supplicant( 1383): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6246): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/wpa_supplicant( 1383): Cmd 35605 not handled
,I/wpa_supplicant( 1383): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1383): Associated with C0.AA.48
I/wpa_supplicant( 1383): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1383): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false,
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
,D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceLinkStateChanged wlan0, false
D/Tethering( 1017): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, false
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
I/wpa_supplicant( 1383): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1383): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
I/wpa_supplicant( 1383): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/SecContentProvider2( 1017): mCursor = null
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1383): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 1383): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1383): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/Nat464Xlat( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 1383): Blacklist: Clear (temp) 
I/wpa_supplicant( 1383): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering( 1017): No numeric data
D/Tethering( 1017): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1017): clearTetheredNotification()
D/Tethering( 1017): interfaceLinkStateChanged wlan0, true
D/Tethering( 1017): interfaceStatusChanged wlan0, true
D/WifiNative-wlan0( 1017): callSECApiVoid - ID [50]
,V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
,D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
E/WifiConfigStore( 1017): setLastSelectedConfiguration -1
,V/NetworkStats( 1017): performPollLocked() took 4ms
D/ConnectivityService( 1017): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1017): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1017): updateNetworkInfo()
,D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6246): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/WifiConfigStore( 1017): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine( 1017): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1017): mCursor = null
,V/JNIHelp ( 6246): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/WifiNative-wlan0( 1017): do suspend false
,D/WifiP2pService( 1017): InactiveState{ what=143375 },
D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,D/SecContentProvider2( 1017): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1017): mCursor = null
,E/SQLiteLog( 1729): (10) POSIX Error : 11 SQLite Error : 3850
,W/ActivityThread( 6246): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6246): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@267d4929: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6246): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6246): GMSCore installation verified
,I/ConfigStore( 6246): Config Database version: 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1017): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1017): getStreamVolume 3 index 70
,I/MediaRouter( 6246): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6246): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
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
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6275): MountEmulatedStorage()
I/libpersona( 6275): KNOX_SDCARD checking this for 10001
E/Zygote  ( 6275): v2
I/libpersona( 6275): KNOX_SDCARD not a persona
I/SELinux ( 6275): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6275 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6275): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6275): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 6281): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 6281): version 5.5.6 starting
,E/dhcpcd  ( 6281): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/GHttpClientFactory( 6246): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6246): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6275): TimaSignature is unavailable
,D/ActivityThread( 6275): Added TimaKeyStore provider
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6281): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6281): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6281): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6281): bssid match
,I/dhcpcd  ( 6281): wlan0: rebinding lease of 192.168.1.132
,I/ActivityManager( 1017): Killing 5651:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6301): MountEmulatedStorage()
,E/Zygote  ( 6301): v2
I/libpersona( 6301): KNOX_SDCARD checking this for 1000
I/libpersona( 6301): KNOX_SDCARD not a persona
,I/SELinux ( 6301): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6301): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6301): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6301 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5666:com.wsomacp/u0a23 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6301): TimaSignature is unavailable
,D/ActivityThread( 6301): Added TimaKeyStore provider,
,I/DIAGMON_AGENT( 6301): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 6301): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/libprocessgroup( 1017): failed to open /acct/uid_10068/pid_5651/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10023/pid_5666/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6301): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6301): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6316): MountEmulatedStorage()
,E/Zygote  ( 6316): v2
I/libpersona( 6316): KNOX_SDCARD checking this for 10008
,I/libpersona( 6316): KNOX_SDCARD not a persona
,I/SELinux ( 6316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6316 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5606:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 6316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6316): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6316): TimaSignature is unavailable
,D/ActivityThread( 6316): Added TimaKeyStore provider,
,I/ActivityManager( 1017): Killing 5268:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,D/CountryDetector( 1017): No listener is left
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:45:37 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3607): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3607): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6332): MountEmulatedStorage()
E/Zygote  ( 6332): v2
I/libpersona( 6332): KNOX_SDCARD checking this for 10031
I/libpersona( 6332): KNOX_SDCARD not a persona
,I/SELinux ( 6332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1017): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6332 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/SELinux ( 6332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3607): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3607): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6332): TimaSignature is unavailable
,D/ActivityThread( 6332): Added TimaKeyStore provider
,I/SO_AGENT( 6332): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,W/libprocessgroup( 1017): failed to open /acct/uid_10041/pid_5606/cgroup.procs: No such file or directory
W/libprocessgroup( 1017): failed to open /acct/uid_10014/pid_5268/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/SA      ( 5898): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5898): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 5898): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5898): [SLFUCHKMGR] constructor called
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5898): [OR] == isSIMCardReady false ==
,I/SA      ( 5898): [SCU] == networkStateCheck == false
,I/SA      ( 5898): [OR] onReceive END
,I/ActivityManager( 1017): Killing 5726:com.samsung.helphub/1000 (adj 15): empty #31
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1573): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1573): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1573): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1573): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6349): MountEmulatedStorage(),
I/libpersona( 6349): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD not a persona
I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6349 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
,D/ActivityThread( 6349): Added TimaKeyStore provider
,W/ResourcesManager( 6349): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6349): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6349): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6349): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6349): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6349): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6364): MountEmulatedStorage()
,E/Zygote  ( 6364): v2
I/libpersona( 6364): KNOX_SDCARD checking this for 10141
I/libpersona( 6364): KNOX_SDCARD not a persona
,I/SELinux ( 6364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6364 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1017): Killing 5734:com.sec.spp.push/u0a32 (adj 15): empty #31
,E/SELinux ( 6364): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6364): TimaSignature is unavailable
,D/ActivityThread( 6364): Added TimaKeyStore provider
,W/ResourcesManager( 6364): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6364): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5726/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5734/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6281): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/Zygote  ( 6387): MountEmulatedStorage()
E/Zygote  ( 6387): v2
I/libpersona( 6387): KNOX_SDCARD checking this for 10068
I/libpersona( 6387): KNOX_SDCARD not a persona
,I/SELinux ( 6387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6387): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1017): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6387 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/TimaKeyStoreProvider( 6387): TimaSignature is unavailable
,D/ActivityThread( 6387): Added TimaKeyStore provider
,I/dhcpcd  ( 6281): wlan0: leased 192.168.1.132 for 86400 seconds
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 6387): onCreate,
D/BadgeProvider( 6387): DatabaseHelper,
,I/ActivityManager( 1017): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6406 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 6406): MountEmulatedStorage()
I/libpersona( 6406): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6406): v2
I/libpersona( 6406): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Killing 5179:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
I/SELinux ( 6406): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Killing 5756:com.sec.android.app.myfiles/u0a42 (adj 15): empty #32
,I/SELinux ( 6406): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6406): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6406): TimaSignature is unavailable
,D/ActivityThread( 6406): Added TimaKeyStore provider,
,D/SecurityLogAgent( 6406): KnoxConfiguration : Current State = 1,
D/SecurityLogAgent( 6406): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6406): StateMachine : Current State = 1
,D/SecurityLogAgent( 6406): StateMachine : Changed Current State = 1,
,I/ActivityManager( 1017): Killing 5794:com.google.android.apps.docs/u0a87 (adj 15): empty #31,
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1017): failed to open /acct/uid_10042/pid_5756/cgroup.procs: No such file or directory
,W/libprocessgroup( 1017): failed to open /acct/uid_10032/pid_5179/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
,I/iu.Environment( 2051): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,I/iu.UploadsManager( 2051): num queued entries: 0
,I/iu.UploadsManager( 2051): num updated entries: 0
,I/iu.SyncManager( 2051): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/WifiNative-wlan0( 1017): do suspend true
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 58107(3MB) AllocSpace objects, 8(180KB) LOS objects, 33% free, 23MB/35MB, paused 3.057ms total 185.025ms
,D/ChimeraCfgMgr( 2051): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/BadgeProvider( 6387): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
D/WifiP2pService( 1017): InactiveState{ what=143375 }
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1017): P2pEnabledState{ what=143375 }
,W/libprocessgroup( 1017): failed to open /acct/uid_10087/pid_5794/cgroup.procs: No such file or directory
E/Zygote  ( 6443): MountEmulatedStorage()
E/Zygote  ( 6443): v2
I/libpersona( 6443): KNOX_SDCARD checking this for 10032
I/libpersona( 6443): KNOX_SDCARD not a persona
I/SELinux ( 6443): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1017): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6443 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6443): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SELinux ( 6443): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/WifiStateMachine( 1017): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1017): VerifyingLinkState enter
I/Babel   ( 6204): connection state changed from UNKNOWN to DISCONNECTED
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/BadgeProvider( 6387): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6387): sendNotify, [notify] : null
D/BadgeProvider( 6387): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1484): reloadBadges entered.
D/BadgeProvider( 6387): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6387): update, [UpdateCount] : 1
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1017): callSECApiInt - ID [210]
,E/ConnectivityService( 1017): updateNetworkInfo(),
D/ConnectivityService( 1017): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1017): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1017): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1017): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiStateMachine( 1017): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
D/ConnectivityService( 1017): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1017): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1017): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1017): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1017): LTETest block dns file not exists
,D/ConnectivityService( 1017): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1017): updateNetworkInfo()
,D/TimaKeyStoreProvider( 6443): TimaSignature is unavailable
,D/ActivityThread( 6443): Added TimaKeyStore provider
,E/ConnectivityService( 1017): updateNetworkInfo(),
D/ConnectivityService( 1017): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1017): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Connected
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1017): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1017):    accepting network in place of null
D/TelephonyNetworkFactory( 1457): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/WIFI_P2P( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1457): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ],
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1017): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/WIFI    ( 1017): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
E/CSLegacyTypeTracker( 1017): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1017): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1017): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1017): mBoosterFLAG : 0
I/WifiTrafficPoller( 1017): current booster mode : FullMode
,D/WifiNative-wlan0( 1017): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1017): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/Tethering( 1017): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1017): MasterInitialState.processMessage what=3
,V/NetworkStats( 1017): updateIfacesLocked()
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1017): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1017): UpdateStatsForKnox main else ---
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
V/NetworkStats( 1017): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,V/NetworkStats( 1017): performPollLocked() took 6ms
D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1017): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
,D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SPPClientService( 6443): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6443): [SystemStateMoniter] Current Time : 165233
,E/SPPClientService( 6443): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6443): [PushClientApplication] Push log off : This is Ship build version
E/SPPClientService( 6443): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6443): PushLog.txt file is not deleted.
D/SPPClientService( 6443): PushLog.txt file is not deleted.
,D/SPPClientService( 6443): ============PushLog. stop!
,E/Zygote  ( 6465): MountEmulatedStorage(),
E/Zygote  ( 6465): v2
I/libpersona( 6465): KNOX_SDCARD checking this for 10110
,I/libpersona( 6465): KNOX_SDCARD not a persona
I/SELinux ( 6465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6465 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1017): Killing 5281:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,I/SELinux ( 6465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,E/SELinux ( 6465): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/System.out( 1017): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
D/TimaKeyStoreProvider( 6465): TimaSignature is unavailable
E/SPPClientService( 6443): [[SystemStateMonitorService]] No Active Internet
,D/ActivityThread( 6465): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 15 Jan 2016 18:45:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452883538585], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452883538554]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Don't send network conditions - lacking user consent.
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1017): Validated
D/ConnectivityService( 1017): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1017): rematching NetworkAgentInfo [WIFI () - 503],
D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524290
D/ConnectivityService( 1017): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1017): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1017): failed to open /acct/uid_10029/pid_5281/cgroup.procs: No such file or directory
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6465): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6465): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6465): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6465):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6465):   adb logcat -s GAv4
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6465): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6465): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6465): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6465): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6465): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6465): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6465): Time to load native libraries: 1 ms (timestamps 5694-5695)
,I/LibraryLoader( 6465): Expected native library version number "",actual native library version number ""
,D/ConnectivityService( 1017): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/WebViewChromiumFactoryProvider( 6465): Binding Chromium to main looper Looper (main, tid 1) {112169e4}
,I/LibraryLoader( 6465): Expected native library version number "",actual native library version number ""
,I/chromium( 6465): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/GpsLocationProvider( 1017): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/BrowserStartupController( 6465): Initializing chromium process, singleProcess=true
,W/art     ( 6465): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6465): ApplicationContext is null in ApplicationStatus
,I/NetworkMonitor( 6246): type=WIFI subType= reason=null isConnected=true
,W/chromium( 6465): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6465): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6465): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6465): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6465): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6465): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6465): Local Branch: 
I/Adreno-EGL( 6465): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6465): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6465):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,W/AudioManagerAndroid( 6465): Requires BLUETOOTH permission
,I/NSApplication( 6465): Starting up...
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6521): MountEmulatedStorage(),
E/Zygote  ( 6521): v2
,I/libpersona( 6521): KNOX_SDCARD checking this for 10077,
I/libpersona( 6521): KNOX_SDCARD not a persona
,I/ActivityManager( 1017): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6521 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6521): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1017): Killing 5849:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,I/SELinux ( 6521): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6521): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/art     (  316): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 761us total 34.230ms
,D/TimaKeyStoreProvider( 6521): TimaSignature is unavailable
,D/ActivityThread( 6521): Added TimaKeyStore provider
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 20.543ms
,I/art     (  316): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 693us total 19.711ms
,W/libprocessgroup( 1017): failed to open /acct/uid_10148/pid_5849/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6036): notifyNetworkActivated
,W/ContextImpl( 6036): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1017): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/ConnectivityService( 1017): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6036): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6036): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6036): exit::IDLE
D/InitializeManagerStateMachine( 6036): entry::NETWORK_CHECK
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 6036): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6036): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6036): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6036): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6036): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6036): entry::SUCCESS
D/hcjo    ( 6036): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1641): Starting #10
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
D/hcjo    ( 6036): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6036): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6036): exit::SUCCESS
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/InitializeManagerStateMachine( 6036): entry::IDLE
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1017): Killing 5842:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #11
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #12
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1641): Starting #13
,I/Hs20UtilService( 1641): Message received 5007
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1017): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1017): mCursor = null
,D/SecContentProvider2( 1017): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1017): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5775): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5775): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5775): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5775): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1017): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
,I/splitIntent( 1017): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1017): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
,I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6246): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  259): id=15 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6301): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6301): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/PowerManagerService( 1017): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,D/SRIB_DCS( 1177): log_dcs ThreadedRenderer::initialize entered! 
,W/libprocessgroup( 1017): failed to open /acct/uid_10048/pid_5842/cgroup.procs: No such file or directory
,D/SSRM:n  ( 1017): SIOP:: AP = 300
,I/DBG_POLICYDM( 5826): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5826): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5826): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5826): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6316): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6316): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:45:39 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive().END.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3607): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3607): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3607): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3607): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3607): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3607): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3607): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5826): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SA      ( 5898): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
I/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
I/SA      ( 5898): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5898): [OR] == ACTION_CONNECTIVITY_CHANGE ==
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,E/DBG_POLICYDM( 5826): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5898): [OR] == isSIMCardReady false ==
,I/SA      ( 5898): [SCU] == networkStateCheck == true,
I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,I/SA      ( 5898): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5898): isChinaCountryCode : false
I/SA      ( 5898): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5898): [OR] == networkStateCheck true ==
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/SA      ( 5898): [OR] GetMyCountryZoneTask
,I/SA      ( 5898): [OR] onReceive END
,I/DBG_POLICYDM( 5826): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5898): [SRS] prepareGetMyCountryZone
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,I/SA      ( 5898): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5898): [SSP] query invoked
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/SA      ( 5898): [TPMU] GetMccFromDB : null
I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
I/SA      ( 5898): [TPM] isNoProxy(default) : true
,D/accuweather( 1573): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/SecContentProvider2( 1017): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1017): mCursor = null
,E/File    ( 5898): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,D/daemonapp( 1625): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/accuweather( 1573): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1573): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
D/accuweather( 1573): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1573): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5826): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1573): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1573): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6349): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
E/DBG_POLICYDM( 5826): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,I/QuickConnect( 6349): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6349): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
I/DBG_POLICYDM( 5826): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5826): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/RCPManagerService( 1017): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6406): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6406): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6406): StateMachine : Current State = 1
,D/SecurityLogAgent( 6406): StateMachine : Changed Current State = 1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 2051): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2051): num queued entries: 0
,I/iu.UploadsManager( 2051): num updated entries: 0
,I/iu.SyncManager( 2051): NEXT; no task
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2051): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2051): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6443): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6443): [SystemStateMoniter] Current Time : 166739
,E/SPPClientService( 6443): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 6204): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6204): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6204): (HTTPLog)-Static: isShipBuild true
I/System.out( 6204): (HTTPLog)-Thread-1057-395230755: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6204): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6036): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6036): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6036): exit::IDLE
D/InitializeManagerStateMachine( 6036): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6036): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6036): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6036): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6036): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6036): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6036): entry::SUCCESS
D/hcjo    ( 6036): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6036): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6036): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6036): exit::SUCCESS
D/InitializeManagerStateMachine( 6036): entry::IDLE
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 6204): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/Kids    ( 2051): [AccountUtils] Account not ready
W/Kids    ( 2051): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2051): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2051): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2051): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2051): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2051): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2051): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2051): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2051): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2051): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2051): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2051): 	at java.lang.Thread.run(Thread.java:818)
,I/Babel   ( 6204): connection state changed from DISCONNECTED to CONNECTED
,V/AlarmManager( 1017): waitForAlarm result :4,
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1729): Connected
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1729): Message class com.google.f.a.a.p
,I/SA      ( 5898): [RC New] Execute method=[GET] start
,I/SA      ( 5898): [RC New] Security=[true]
,I/System.out( 5898): Thread-1005(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5898): Thread-1005(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5898): Thread-1005(ApacheHTTPLog):isShipBuild true
I/System.out( 5898): Thread-1005(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5898): Thread-1005(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5351): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5351): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5351): [1] 5.onFinished: Scheduling replication attempt 5.
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6147): BLE supported!!
I/jxcore-log( 6147): 
,E/Watchdog( 1017): !@Sync 5
,I/SA      ( 5898): [RC New] [v2liruge] api execute + 655,
I/SA      ( 5898): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5898): AsyncTask #1 calls detatch()
I/SA      ( 5898): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5898): [OCP] update openData : PL,
,I/SA      ( 5898): [TPMU] getNetworkMcc : 
,I/SA      ( 5898): [SCU] saveMccToPreferece Start
,I/SA      ( 5898): [SCU] RegionMCC : 260
,I/SA      ( 5898): [SSP] query invoked
,I/SA      ( 5898): [TPMU] GetMccFromDB : null
,I/SA      ( 5898): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5898): [SCU] saveMccToPreferece End
,I/SA      ( 5898): [RC New] executeRequest [v2liruge] end. 711,
I/SA      ( 5898): [RC New] Execute end
I/SA      ( 5898): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5898): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6281): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
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
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6246): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6246): Stop autocaching.
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WearableService( 3493): callingUid 10011, callindPid: 3493
,E/GmsUtils( 6246): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6246): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/SMD     (  290): DCD OFF
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  259): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1017): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 169869
,D/PowerManagerService( 1017): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
,D/PowerManagerService( 1017): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10049}) (elapsedTime=3490)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5775): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5775): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5775): [GetString-S]
,I/ReactiveServiceManager( 5775): Supported : 1
,D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1017): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1017): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1017): handleString: Failed to handle string(-4)
E/terrier ( 1017): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5775): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5775): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5775): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5775): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5775): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 5775): [ensureRegistration] - No Samsung account
,I/PowerManagerService( 1017): [PWL] Off : 75s ago
,V/AlarmManager( 1017): waitForAlarm result :4
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 37744(2MB) AllocSpace objects, 6(100KB) LOS objects, 33% free, 23MB/35MB, paused 2.527ms total 152.639ms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1729): Vacuum at: now=1452883545262 tag=VacuumService
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
,W/Uploader( 1729): No account for auth token provided
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1729): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1729): (HTTPLog)-Static: isShipBuild true
I/System.out( 1729): (HTTPLog)-Thread-206-59255925: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1729): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,I/qtaguid ( 1729): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,I/dhcpcd  ( 6281): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  290): DCD OFF
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729):  no longer exists, so no auth token.
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/Uploader( 1729): No account for auth token provided
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,E/Uploader( 1729): Failed to get auth token: User intervention required. Notification has been pushed.
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
,I/System.out( 1729): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1729): Tagging socket 56 with tag 120100000000{4609,0} for uid -1, pid: 1729, getuid(): 10011
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SQLiteLog( 1729): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/dhcpcd  ( 6281): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6281): wlan0: no IPv6 Routers available
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6036): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6036): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6036): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6036): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6036): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6036): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6036): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6036): entry::IDLE
,D/SSRM:n  ( 1017): SIOP:: AP = 290
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6036): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6036): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6036): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6036): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6036): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6036): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6036): entry::IDLE
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,V/AlarmManager( 1017): waitForAlarm result :4
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,V/AlarmManager( 1017): waitForAlarm result :8
,V/AlarmManager( 1017): waitForAlarm result :4
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,E/SMD     (  290): DCD OFF,
D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5351): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5351): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5351): [1] 5.onFinished: Giving up after 6 failures.
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 6
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 105s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/Watchdog( 1017): !@Sync 7
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1017): [PWL] Off : 140s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,V/AlarmManager( 1017): waitForAlarm result :8
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 8
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 1017): [PWL] Off : 180s ago
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
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
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6061): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6061): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6061): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksSync( 6061): Soft error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6061): Sync error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6061): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 282576, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1017): !@Sync 9
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
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
,E/SMD     (  290): DCD OFF
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 1017): initializing...,
I/TLC_TIMA_PKM_initialize( 1017): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1017): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1017): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1017): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1017): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1017): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1017): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1017): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1017): Trustlet response is completed
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/Watchdog( 1017): !@Sync 10
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 225s ago
,E/SMD     (  290): DCD OFF
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 6147): Connected to the server!
I/jxcore-log( 6147): 
,I/chromium( 6147): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1017): stay LED for fully charged
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :4
,I/BooksSync( 6061): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6061): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice,
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/BooksAccountManager( 6061): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6061): Soft error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6061): Sync error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6061): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 314199, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 11
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1177): Icon Only,
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/GLSActivity( 1729): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1729): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1729): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1729): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1729): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1729): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1729): 	at android.os.Binder.execTransact(Binder.java:461)
,E/PlayEventLogger( 5351): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5351): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5351): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5351): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5351): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5351): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5351): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5351): Ignoring header User-Agent because its value was null.
,I/System.out( 5351): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5351): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 5351): (HTTPLog)-Static: isShipBuild true
I/System.out( 5351): (HTTPLog)-Thread-903-495555723: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 5351): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10026
,I/System.out( 5351): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,V/AlarmManager( 1017): waitForAlarm result :8,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 275s ago
,V/AlarmManager( 1017): waitForAlarm result :4
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
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 12
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :4
,I/BooksSync( 6061): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6061): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1177): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1177): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1177): Icon Only
,I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
,D/PanelView( 1177): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6061): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6061): Soft error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6061): Sync error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6061): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 405579, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 48503(3MB) AllocSpace objects, 102(1654KB) LOS objects, 33% free, 23MB/35MB, paused 2.445ms total 167.414ms
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 13
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 330s ago,
,V/AlarmManager( 1017): waitForAlarm result :8,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 14
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 6147): --- start :testFindPeers.js---
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): testFindPeers created [object Object]
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): serverPort is 8876
I/jxcore-log( 6147): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2033
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6147): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6147): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6147): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
,D/BluetoothSocket( 6147): bindListen(), new LocalSocket 
D/BluetoothSocket( 6147): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6147): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3894089
,D/BluetoothSocket( 6147): channel: 6
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): start: OK
,I/io.jxcore.node.ConnectionHelper( 6147): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2033
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6147): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6147): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6147): start: OK
,I/jxcore-log( 6147): StartBroadcasting started ok
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): P2pEnabledState add service
I/chromium( 6147): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6147): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onWifiStateChanged: State changed to 2
,I/io.jxcore.node.ConnectionHelper( 6147): onDiscoveryManagerStateChanged: RUNNING
,D/WifiP2pService( 1017): add a new client
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): Local service added successfully
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 1 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: , device address: 7e:f9:0e:51:18:23
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] is available
I/jxcore-log( 6147): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"samsung-SM-A500FU_PT4798","peerAvailable":true}]
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): weAreDoneNow,
I/jxcore-log( 6147): 
I/jxcore-log( 6147): done, now sending data to server
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: , device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] is available
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 4 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 4 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 5 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 6 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78,
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] is available
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] is available
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 8 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 1017): stay LED for fully charged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13],
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully,
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered,
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] is available
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"90:E7:C4:F6:69:77","pn":"HTC-HTC One M8s_PT6746","ra":"90:E7:C4:F6:69:77"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746], Bluetooth address: 90:E7:C4:F6:69:77, device name: Android_608e, device address: 92:e7:c4:e6:4c:f8
,D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746] is available
,E/SMD     (  290): DCD OFF,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"44:80:EB:7B:5A:05","pn":"motorola-XT1072_PT858","ra":"44:80:EB:7B:5A:05"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], Bluetooth address: 44:80:EB:7B:5A:05, device name: XT1072_23d5, device address: 44:80:eb:7b:5a:07
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT6746]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [44:80:EB:7B:5A:05 motorola-XT1072_PT858], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [44:80:EB:7B:5A:05 motorola-XT1072_PT858],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 15
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b,
,I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 ,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: , device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] is available
,E/SMD     (  290): DCD OFF,
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714],
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714],
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: , device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] is available
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered,
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddre,ss: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager,( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=139301 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/bootchecker(  324): bootchecker wake up!!
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiDisplayController( 1017): Received list of peers.
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
,I/PowerManagerService( 1017): [PWL] Off : 390s ago,
,V/AlarmManager( 1017): waitForAlarm result :8,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 3
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,E/Watchdog( 1017): !@Sync 16
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1017): Plugged
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,V/AlarmManager( 1017): waitForAlarm result :4
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
,E/SMD     (  290): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=139307 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF,
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 17
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2,
,I/ServiceManager(  327): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,I/ServiceManager(  327): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  327): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): checkListForExpiredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] expired
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: false
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Removed [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerLost: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] removed
,D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] not available
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1017): waitForAlarm result :8
,E/SMD     (  290): DCD OFF,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,V/AlarmManager( 1017): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1177): handleTimeUpdate
,D/SecKeyguardClockView( 1177): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1177): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1177): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1177): *** don't update sliding image ***
,I/BooksSync( 6061): Starting books sync for 61035162, extras: ade
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6061): GmsCore Version = 7.8.99 (2134222-434)
D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/SViewCoverWidget( 1177): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecKeyguardStatusUtils( 1177): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1017): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1017): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
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
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1729): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1729): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1729): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1729): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6061): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6061): Soft error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6061): Sync error
E/BooksSync( 6061): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6061): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6061): Finished books sync
,D/SyncManager( 1017): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 531053, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1177): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1017): mCursor = null
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1017): [PWL] Off : 455s ago,
,E/SMD     (  290): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 18
,I/Atfwd_Sendcmd(  327): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  327): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): InactiveState{ what=139301 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF,
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 },
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213],
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 6147): teardown,
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): testFindPeers stopped
I/jxcore-log( 6147): 
,I/io.jxcore.node.ConnectionHelper( 6147): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): shutdown
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@abc5c45, channel: 6, state: LISTENING
D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@abc5c45, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3894089, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@18ae7f9amSocket: android.net.LocalSocket@384970cb impl:android.net.LocalSocketImpl@1fa510a8 fd:FileDescriptor[109]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@384970cb impl:android.net.LocalSocketImpl@1fa510a8 fd:FileDescriptor[109]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): stop: Stopping services
,D/WifiP2pService( 1017): InactiveState{ what=139298 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6147): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onServerStopped
D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setState: NOT_STARTED
,I/jxcore-log( 6147): StopBroadcasting went ok
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): remove channel information from framework
,I/jxcore-log( 6147): --- start :testSendData.js---
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,I/jxcore-log( 6147): testSendData created {"name":"testSendData.js","serverTimeout":120000,"timeout":100000,"rounds":1,"dataTimeout":20000,"dataAmount":100000,"conReTryTimeout":5000,"conReTryCount":5,"peerCount":15}bt-address length : 0
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6147): daya100000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): check server
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): serverPort is 54017
I/jxcore-log( 6147): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2033
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6147): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6147): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6147): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
,D/BluetoothSocket( 6147): bindListen(), new LocalSocket 
D/BluetoothSocket( 6147): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6147): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34e4fb66
D/BluetoothSocket( 6147): channel: 6
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): start: OK
I/io.jxcore.node.ConnectionHelper( 6147): start: Using peer discovery mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): start: Peer ID: 08:EC:A9:50:75:41, peer name: samsung-SM-A300FU_PT2033
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6147): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6147): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): start: {"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"samsung-SM-A300FU_PT2033","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1017): InactiveState{ what=139292 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139292 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6147): start: OK
,I/jxcore-log( 6147): StartBroadcasting started ok
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): P2pEnabledState add service
I/jxcore-log( 6147): null
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): add a new client
,I/jxcore-log( 6147): 2016-01-15T18:52:18.110Z SendDataTCPServer.js: TCP/IP server is bound to port: 54017
I/jxcore-log( 6147): 
I/chromium( 6147): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6147): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 6147): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service requests cleared successfully
I/chromium( 6147): [INFO:CONSOLE(63)] "logCallback --- start :testSendData.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6147): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onWifiStateChanged: State changed to 2
,I/io.jxcore.node.ConnectionHelper( 6147): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): Local service added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery stopped successfully
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully,
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10,
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Start timer timeout, starting now...,
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiP2pService( 1017): InactiveState{ what=139265 }
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
D/WifiP2pService( 1017): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devc,apab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"34:FC:EF:11:AE:67","pn":"LGE-Nexus 5_PT4558","ra":"34:FC:EF:11:AE:67"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], Bluetooth address: 34:FC:EF:11:AE:67, device name: Android_8ae2, device address: 52:55:27:f0:fd:0b
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] is available
I/jxcore-log( 6147): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"LGE-Nexus 5_PT4558","peerAvailable":true}]
I/jxcore-log( 6147): 
I/jxcore-log( 6147): Found peer : LGE-Nexus 5_PT4558, Available: true
I/jxcore-log( 6147): 
I/jxcore-log( 6147): startWithNextDevice
I/jxcore-log( 6147): 
I/jxcore-log( 6147): device[1]: 34:FC:EF:11:AE:67
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:32.041Z SendDataConnector.js: Start called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:32.042Z SendDataConnector.js: doConnect called with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:32.042Z SendDataConnector.js: do connect now
I/jxcore-log( 6147): 
I/io.jxcore.node.ConnectionHelper( 6147): connect: Trying to connect to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): connect: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Trying to start connecting to null in address 34:FC:EF:11:AE:67
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnecting: null 34:FC:EF:11:AE:67
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Started connecting to null in address 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 6147): connect: Connection process successfully started (peer ID: 34:FC:EF:11:AE:67)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Trying to connect to peer with address 34:FC:EF:11:AE:67 (thread ID: 1065)
,D/BluetoothUtils( 6147): isSocketAllowedBySecurityPolicy start : device null,
W/BluetoothAdapter( 6147): getBluetoothService() called with no BluetoothManagerCallback
D/BTIF_SOCK( 2630): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/BluetoothSocket( 6147): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value 1
D/IOP_DB_BT( 2630): db_query_execute: result 1
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"samsung-SM-G900F_PT3213","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213] already in the list, will not add again
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 2630): db_query_execute: result 1
,W/bt-btif ( 2630): info:x10
,D/        ( 2630): remote version info [34:fc:ef:11:ae:67]: 7, f, 6109
,E/BluetoothRemoteDevices( 2630): aclStateChangeCallback: Device is NULL
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"samsung-SM-G900F_PT919","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919] already in the list, will not add again
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2630): process_service_search_attr_rsp
,V/AlarmManager( 1017): waitForAlarm result :4
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,E/bt-btif ( 2630): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2630): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 2630): isSecureModeOn:false
I/BluetoothBondStateMachine( 2630): Entering PendingCommandState State
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5954): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098
,D/GMFPReceiver( 5954): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,W/BackupManagerService( 1017): dataChanged but no participant pkg='com.android.providers.settings' uid=10098,
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/GMFPReceiver( 5954): ::::::::Wearable0002::false
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
D/GMFPReceiver( 5954): onServiceConnected() : 1
D/GMFPReceiver( 5954): mBluetoothHeadset = true
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/SMD     (  290): DCD OFF
,D/btif_config_util( 2630): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: 34:FC:EF:11:AE:67 newState: 0
,D/BluetoothAdapterProperties( 2630): Failed to remove device: 34:FC:EF:11:AE:67
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2630): Bond State Change Intent:34:FC:EF:11:AE:67 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5954): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/HidService( 2630): getHidService(): returning com.android.bluetooth.hid.HidService@39ec6238
D/SettingsProvider( 1017): name = Wearable0001
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5954): ::::::::Wearable0001::false
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_34:FC:EF:11:AE:67
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2630): Saved priority 34:FC:EF:11:AE:67 = -1
D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5954): ::::::::Wearable0002::false
,D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_34:FC:EF:11:AE:67
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/GMFPReceiver( 5954): onServiceConnected() : 1
D/GMFPReceiver( 5954): mBluetoothHeadset = true
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_34:FC:EF:11:AE:67
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2630): StableState(): Entering Off State
,W/bt-btif ( 2630): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2630): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2630): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2630): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onSocketConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1065)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesWritten: 83 bytes successfully written (thread ID: 1066),
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Outgoing connection initialized (*handshake* thread ID: 1066)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Exiting thread (thread ID: 1065)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Entering thread (ID: 1066)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesRead: Read 77 bytes successfully (thread ID: 1066)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Handshake succeeded with [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onHandshakeSucceeded: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Exiting thread (ID: 1066),
I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID 34:FC:EF:11:AE:67
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
D/io.jxcore.node.ConnectionHelper( 6147): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6147): Entering thread (ID: 1067)
,D/io.jxcore.node.OutgoingSocketThread( 6147): Server socket local port: 38476
,I/io.jxcore.node.OutgoingSocketThread( 6147): Now accepting connections...
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,W/bt-btif ( 2630): new conn_srvc id:26, app_id:255
,W/bt-btif ( 2630): bta_dm_pm_ssr conn_srvc id:26, app_id:1
W/bt-btif ( 2630): bta_dm_pm_ssr conn_srvc id:26, app_id:255
D/BluetoothSocket( 6147): socket fd passed by stack  fds: [Ljava.io.FileDescriptor;@3656cefd
W/bt-btif ( 2630): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2630): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Incoming connection initialized (thread ID: 1068)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Entering thread (ID: 1068)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): onBytesRead: Read 77 bytes successfully (thread ID: 1068)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Got valid identity from [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): onBytesWritten: 83 bytes successfully written (thread ID: 1068)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): removeThreadFromList: Removing thread with ID 1068
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Handshake thread disposed (thread ID: 1068)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onIncomingConnectionConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Exiting thread (ID: 1068)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnected: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Incoming connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: We have an outgoing connection with peer with ID 34:FC:EF:11:AE:67
,W/io.jxcore.node.ConnectionHelper( 6147): onConnected: Already connected with peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], continuing anyway...
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Incoming socket thread, for peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], created successfully
,D/io.jxcore.node.ConnectionHelper( 6147): onConnected: The total number of connections is now 2
D/io.jxcore.node.IncomingSocketThread( 6147): Entering thread (ID: 1069)
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10338
,I/io.jxcore.node.IncomingSocketThread( 6147): Local host address: localhost/127.0.0.1, port: 54017
,D/io.jxcore.node.IncomingSocketThread( 6147): Setting local streams and starting stream copying threads...
,I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.IncomingSocketThread( 6147): startStreamCopyingThreads: OK
D/io.jxcore.node.IncomingSocketThread( 6147): Exiting thread (ID: 1069)
,I/jxcore-log( 6147): 2016-01-15T18:52:33.921Z SendDataTCPServer.js: TCP/IP server connected
I/jxcore-log( 6147): 
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1071, name: Receiver)
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1070, name: Sender)
,I/io.jxcore.node.ConnectionHelper( 6147): onListeningForIncomingConnections: Outgoing connection is using port 38476 (peer ID: 34:FC:EF:11:AE:67)
,I/jxcore-log( 6147): 2016-01-15T18:52:34.138Z SendDataConnector.js: CLIENT connected to 38476, error: null
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.139Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6147): 
,I/io.jxcore.node.IncomingSocketThread( 6147): Incoming data from address: /127.0.0.1, port: 38476
,D/io.jxcore.node.IncomingSocketThread( 6147): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.IncomingSocketThread( 6147): startStreamCopyingThreads: OK
D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1072, name: Sender)
D/io.jxcore.node.IncomingSocketThread( 6147): Exiting thread (ID: 1067)
,I/jxcore-log( 6147): 2016-01-15T18:52:34.149Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6147): 
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1073, name: Receiver)
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:3786
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:17330
,I/jxcore-log( 6147): 2016-01-15T18:52:34.803Z SendDataTCPServer.js: TCP/IP server has received 1980 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.809Z SendDataTCPServer.js: TCP/IP server has received 3960 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.873Z SendDataTCPServer.js: TCP/IP server has received 5940 bytes of data
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] is available
,I/jxcore-log( 6147): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"LGE-LG-D722_PT3965","peerAvailable":true}]
I/jxcore-log( 6147): 
I/jxcore-log( 6147): Found peer : LGE-LG-D722_PT3965, Available: true
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.892Z SendDataTCPServer.js: TCP/IP server has received 7920 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.898Z SendDataTCPServer.js: TCP/IP server has received 9900 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.904Z SendDataTCPServer.js: TCP/IP server has received 11880 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.915Z SendDataTCPServer.js: TCP/IP server has received 13860 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.936Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6147): 
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:10890,tx.queue.count:11,available:8420
,I/jxcore-log( 6147): 2016-01-15T18:52:34.941Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:34.954Z SendDataTCPServer.js: TCP/IP server has received 23760 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.024Z SendDataTCPServer.js: TCP/IP server has received 25740 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.076Z SendDataTCPServer.js: TCP/IP server has received 27720 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.105Z SendDataTCPServer.js: TCP/IP server has received 29700 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.134Z SendDataTCPServer.js: TCP/IP server has received 31680 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.143Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.339Z SendDataTCPServer.js: TCP/IP server has received 32768 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.374Z SendDataTCPServer.js: TCP/IP server has received 40688 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.379Z SendDataTCPServer.js: TCP/IP server has received 42668 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.415Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.476Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.504Z SendDataTCPServer.js: TCP/IP server has received 44648 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.527Z SendDataTCPServer.js: TCP/IP server has received 46628 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.569Z SendDataTCPServer.js: TCP/IP server has received 48608 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.574Z SendDataTCPServer.js: TCP/IP server has received 50588 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.584Z SendDataTCPServer.js: TCP/IP server has received 52568 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.647Z SendDataTCPServer.js: TCP/IP server has received 54548 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.675Z SendDataTCPServer.js: TCP/IP server has received 56528 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.719Z SendDataTCPServer.js: TCP/IP server has received 58508 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.790Z SendDataTCPServer.js: TCP/IP server has received 60488 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:35.820Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6147): 
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT919]
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965],
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT3213]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/jxcore-log( 6147): 2016-01-15T18:52:35.982Z SendDataConnector.js: CLIENT is data received : 90000,
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.020Z SendDataTCPServer.js: TCP/IP server has received 62468 bytes of data,
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.054Z SendDataTCPServer.js: TCP/IP server has received 68408 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.057Z SendDataTCPServer.js: TCP/IP server has received 70388 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.063Z SendDataTCPServer.js: TCP/IP server has received 72368 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.094Z SendDataTCPServer.js: TCP/IP server has received 84248 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.102Z SendDataTCPServer.js: TCP/IP server has received 86228 bytes of data
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.111Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.112Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): oneRoundDownNow
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.115Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.116Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6147): 
,D/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Trying to close connection to peer with ID 34:FC:EF:11:AE:67
,I/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 34:FC:EF:11:AE:67
I/io.jxcore.node.IncomingSocketThread( 6147): close
D/io.jxcore.node.IncomingSocketThread( 6147): close: Stopping receiving thread...
,I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1073
,D/io.jxcore.node.IncomingSocketThread( 6147): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1072
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local input stream...
,D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.IncomingSocketThread( 6147): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2ab567f2, channel: 5, state: CONNECTED
D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@2ab567f2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c152e43, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23ef4cc0mSocket: android.net.LocalSocket@12c65df9 impl:android.net.LocalSocketImpl@16ae113e fd:FileDescriptor[111]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@12c65df9 impl:android.net.LocalSocketImpl@16ae113e fd:FileDescriptor[111]
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2ab567f2, channel: 5, state: CLOSED
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2ab567f2, channel: 5, state: CLOSED
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Successfully disconnected (peer ID: 34:FC:EF:11:AE:67
,W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1073, thread name: Receiver): bt socket closed, read return: -1
,I/jxcore-log( 6147): 2016-01-15T18:52:36.125Z SendDataConnector.js: Mobile.Disconnect() callback with peer 34:FC:EF:11:AE:67
I/jxcore-log( 6147): 
,E/io.jxcore.node.IncomingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
I/jxcore-log( 6147): ---- round done--------
I/jxcore-log( 6147): 
W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1072, thread name: Sender): Socket closed
I/jxcore-log( 6147): startWithNextDevice
I/jxcore-log( 6147): 
I/jxcore-log( 6147): device[2]: F8:95:C7:87:85:54
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:36.128Z SendDataConnector.js: Start called with peer F8:95:C7:87:85:54
I/jxcore-log( 6147): 
E/io.jxcore.node.IncomingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
I/jxcore-log( 6147): 2016-01-15T18:52:36.128Z SendDataConnector.js: doConnect called with peer F8:95:C7:87:85:54
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:36.128Z SendDataConnector.js: do connect now
I/jxcore-log( 6147): 
W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1072, name: Sender)
I/io.jxcore.node.ConnectionHelper( 6147): connect: Trying to connect to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): connect: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Trying to start connecting to null in address F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setMaxNumberOfRetries: 0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnecting: null F8:95:C7:87:85:54
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Started connecting to null in address F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6147): connect: Connection process successfully started (peer ID: F8:95:C7:87:85:54)
,E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 34:FC:EF:11:AE:67
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1073, name: Receiver)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Trying to connect to peer with address F8:95:C7:87:85:54 (thread ID: 1074)
,I/jxcore-log( 6147): 2016-01-15T18:52:36.141Z SendDataTCPServer.js: TCP/IP server has received 98108 bytes of data
I/jxcore-log( 6147): 
,D/BluetoothUtils( 6147): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6147): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2630): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
,D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2630): db_query_execute: result 1
D/BluetoothSocket( 6147): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,I/jxcore-log( 6147): 2016-01-15T18:52:36.303Z SendDataTCPServer.js: TCP/IP server has received 100000 bytes of data
I/jxcore-log( 6147): 
,I/Atfwd_Daemon(  327): Stop the daemon....
,W/bt-btif ( 2630): bta_jv_rfc_port_to_cb(port_handle:0xc):jv handle:0x0 not FOUND
,D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:85:54
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 6:16653
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2630): db_query_execute: result 1
W/bt-btif ( 2630): info:x10
D/        ( 2630): remote version info [f8:95:c7:87:85:54]: 6, f, 410d
,E/BluetoothRemoteDevices( 2630): aclStateChangeCallback: Device is NULL
,E/SMD     (  290): DCD OFF
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-btif ( 2630): invalid rfc slot id: 5
,W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1071, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.IncomingSocketThread( 6147): The receiving thread failed with error "Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1", this is likely due to peer having disconnected
W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
,I/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1069
D/io.jxcore.node.IncomingSocketThread( 6147): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1071
D/io.jxcore.node.IncomingSocketThread( 6147): close: Stopping sending thread...
,I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1070
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local output stream...
,W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1070, thread name: Sender): Socket closed
E/io.jxcore.node.IncomingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Incoming connection, peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.IncomingSocketThread( 6147): closeLocalSocketAndStreams: Closing the localhost socket...
,I/io.jxcore.node.IncomingSocketThread( 6147): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@5526b9f, channel: 6, state: CONNECTED
,D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@5526b9f, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3cdc74ec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3005e0b5mSocket: android.net.LocalSocket@3df6034a impl:android.net.LocalSocketImpl@2bfc22bb fd:FileDescriptor[113]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@3df6034a impl:android.net.LocalSocketImpl@2bfc22bb fd:FileDescriptor[113]
,D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@5526b9f, channel: 6, state: CLOSED
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@5526b9f, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1071, name: Receiver)
,D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1070, name: Sender)
,I/jxcore-log( 6147): 2016-01-15T18:52:36.905Z SendDataTCPServer.js: TCP/IP server is ended
I/jxcore-log( 6147): 
,W/bt-sdp  ( 2630): process_service_search_attr_rsp,
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 1
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2630): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 10 NewState: 11
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,I/BluetoothBondStateMachine( 2630): Entering PendingCommandState State
E/bt-btif ( 2630): check_cod: remote_cod = 0x5a020c
V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5954): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5954): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5954): ::::::::Wearable0002::false
,D/GMFPReceiver( 5954): onServiceConnected() : 1
D/GMFPReceiver( 5954): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2630): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new,
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: F8:95:C7:87:85:54 newState: 0
,D/BluetoothAdapterProperties( 2630): Failed to remove device: F8:95:C7:87:85:54
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote,
I/BluetoothBondStateMachine( 2630): Bond State Change Intent:F8:95:C7:87:85:54 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10,
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
D/BluetoothTile( 1177):  handleUpdatestate:false name:null
D/HidService( 2630): getHidService(): returning com.android.bluetooth.hid.HidService@39ec6238
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings,
V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
D/SettingsProvider( 1017): name = bluetooth_input_device_priority_F8:95:C7:87:85:54
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/HidService( 2630): Saved priority F8:95:C7:87:85:54 = -1
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_F8:95:C7:87:85:54
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
I/BluetoothBondStateMachine( 2630): StableState(): Entering Off State
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5954): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
,D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5954): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 10098
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
D/GMFPReceiver( 5954): ::::::::Wearable0002::false
D/GMFPReceiver( 5954): onServiceConnected() : 1
,D/GMFPReceiver( 5954): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,W/bt-btif ( 2630): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2630): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2630): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2630): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onSocketConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1074)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesWritten: 83 bytes successfully written (thread ID: 1075)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Outgoing connection initialized (*handshake* thread ID: 1075)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Exiting thread (thread ID: 1074)
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Entering thread (ID: 1075)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesRead: Read 77 bytes successfully (thread ID: 1075)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Handshake succeeded with [F8:95:C7:87:85:54 LGE-LG-D722_PT3965],
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onHandshakeSucceeded: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Exiting thread (ID: 1075)
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnected: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID F8:95:C7:87:85:54
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing socket thread, for peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6147): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6147): Entering thread (ID: 1076)
D/io.jxcore.node.OutgoingSocketThread( 6147): Server socket local port: 50356
I/io.jxcore.node.OutgoingSocketThread( 6147): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6147): onListeningForIncomingConnections: Outgoing connection is using port 50356 (peer ID: F8:95:C7:87:85:54)
,I/jxcore-log( 6147): 2016-01-15T18:52:38.750Z SendDataConnector.js: CLIENT connected to 50356, error: null
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:38.751Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:38.755Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6147): 
,I/io.jxcore.node.OutgoingSocketThread( 6147): Incoming data from address: /127.0.0.1, port: 50356
,D/io.jxcore.node.OutgoingSocketThread( 6147): Setting local streams and starting stream copying threads...,
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.OutgoingSocketThread( 6147): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6147): Exiting thread (ID: 1076)
D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1077, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1078, name: Receiver)
,I/jxcore-log( 6147): 2016-01-15T18:52:39.271Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.360Z SendDataConnector.js: CLIENT is data received : 20000,
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.436Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.471Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.513Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.586Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.591Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.610Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.647Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.650Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.651Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6147): 
I/jxcore-log( 6147): oneRoundDownNow
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:39.652Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:39.652Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6147): 
,D/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Trying to close connection to peer with ID F8:95:C7:87:85:54
I/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: F8:95:C7:87:85:54
I/io.jxcore.node.OutgoingSocketThread( 6147): close
D/io.jxcore.node.OutgoingSocketThread( 6147): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1078
D/io.jxcore.node.OutgoingSocketThread( 6147): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1077
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6147): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2491f3d8, channel: 8, state: CONNECTED
D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@2491f3d8, channel: 8, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b80d331, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f190a16mSocket: android.net.LocalSocket@1c02f97 impl:android.net.LocalSocketImpl@331e7584 fd:FileDescriptor[111]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@1c02f97 impl:android.net.LocalSocketImpl@331e7584 fd:FileDescriptor[111]
W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1078, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2491f3d8, channel: 8, state: CLOSED
,D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@2491f3d8, channel: 8, state: CLOSED
W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1077, thread name: Sender): Socket closed
E/io.jxcore.node.OutgoingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Successfully disconnected (peer ID: F8:95:C7:87:85:54
,E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
I/jxcore-log( 6147): 2016-01-15T18:52:39.657Z SendDataConnector.js: Mobile.Disconnect() callback with peer F8:95:C7:87:85:54
I/jxcore-log( 6147): 
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
I/jxcore-log( 6147): ---- round done--------
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): startWithNextDevice
I/jxcore-log( 6147): 
,E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID F8:95:C7:87:85:54
D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1077, name: Sender),
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1078, name: Receiver)
,E/SMD     (  290): DCD OFF
,W/bt-btif ( 2630): bta_jv_rfc_port_to_cb(port_handle:0xe):jv handle:0x0 not FOUND
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 19
,E/bt-btm  ( 2630): Reset sec_bd_name and name flag. (BR/EDR link)
,E/bt-btm  ( 2630): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1316): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2630): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34b9bcb6
,D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2630): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=34:FC:EF:11:AE:67, alias=null, name=Nexus 5, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6020): Bluetooth Device Name: Nexus 5
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/WifiP2pManager( 6147): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/WifiP2pService( 1017): InactiveState{ what=139301 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/bt-btm  ( 2630): Reset sec_bd_name and name flag. (BR/EDR link)
E/bt-btm  ( 2630): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 1316): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,D/BluetoothAdapterService( 2630): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34b9bcb6
,D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2630): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:85:54, alias=null, name=G3s-1, majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6020): Bluetooth Device Name: G3s-1
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254],
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6147): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] is available
,I/jxcore-log( 6147): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"samsung-SM-A300FU_PT7121","peerAvailable":true}]
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): Found peer : samsung-SM-A300FU_PT7121, Available: true
I/jxcore-log( 6147): 
I/jxcore-log( 6147): startWithNextDevice
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): device[3]: 08:EC:A9:50:76:27
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:44.157Z SendDataConnector.js: Start called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:44.157Z SendDataConnector.js: doConnect called with peer 08:EC:A9:50:76:27
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:44.158Z SendDataConnector.js: do connect now
I/jxcore-log( 6147): 
,I/io.jxcore.node.ConnectionHelper( 6147): connect: Trying to connect to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): connect: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Trying to start connecting to null in address 08:EC:A9:50:76:27
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setInsecureRfcommSocketPort: Using port -1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): setMaxNumberOfRetries: 0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnecting: null 08:EC:A9:50:76:27
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): connect: Started connecting to null in address 08:EC:A9:50:76:27
I/io.jxcore.node.ConnectionHelper( 6147): connect: Connection process successfully started (peer ID: 08:EC:A9:50:76:27)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Trying to connect to peer with address 08:EC:A9:50:76:27 (thread ID: 1079)
,D/BluetoothUtils( 6147): isSocketAllowedBySecurityPolicy start : device null
,W/BluetoothAdapter( 6147): getBluetoothService() called with no BluetoothManagerCallback
,D/BTIF_SOCK( 2630): service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value 1
,D/IOP_DB_BT( 2630): db_query_execute: result 1
,D/BluetoothSocket( 6147): connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 2630): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 2630): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 2630): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 2630): db_query_execute: result 1
W/bt-btif ( 2630): info:x10
,D/        ( 2630): remote version info [08:ec:a9:50:76:27]: 7, f, 6109
,E/BluetoothRemoteDevices( 2630): aclStateChangeCallback: Device is NULL
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED
,W/bt-sdp  ( 2630): process_service_search_attr_rsp
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 1
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.NAME_CHANGED,
V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.CLASS_CHANGED
E/bt-btif ( 2630): check_cod: remote_cod = 0x5a020c
,I/BluetoothBondStateMachine( 2630): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 2630): isSecureModeOn:false
I/BluetoothBondStateMachine( 2630): Entering PendingCommandState State
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 11,
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothNotiBroadcastReceiver( 1316): onReceive
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
,E/BluetoothHeadset( 5954): BTStateChangeCB is registed
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
,D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001,
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5954): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5954): ::::::::Wearable0002::false,
,D/GMFPReceiver( 5954): onServiceConnected() : 1
D/GMFPReceiver( 5954): mBluetoothHeadset = true
W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,D/btif_config_util( 2630): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,I/BluetoothBondStateMachine( 2630): bondStateChangeCallback: Status: 0 Address: 08:EC:A9:50:76:27 newState: 0
,D/BluetoothAdapterProperties( 2630): Failed to remove device: 08:EC:A9:50:76:27
,D/SecContentProvider( 1017): uri = 4 selection = bluetoothLogForRemote
,I/BluetoothBondStateMachine( 2630): Bond State Change Intent:08:EC:A9:50:76:27 OldState: 11 NewState: 10
D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED prevBondState: 11
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED bondState: 10
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_BOND_STATE_CHANGED it is NOT bonded. quit
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.settings
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/HidService( 2630): getHidService(): returning com.android.bluetooth.hid.HidService@39ec6238
,D/SettingsProvider( 1017): name = bluetooth_input_device_priority_08:EC:A9:50:76:27
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/BluetoothNotiBroadcastReceiver( 1316): onReceive
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/HidService( 2630): Saved priority 08:EC:A9:50:76:27 = -1
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.samsung.android.app.watchmanagerstub
D/SettingsProvider( 1017): name = bluetooth_a2dp_sink_priority_08:EC:A9:50:76:27
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/SettingsProvider( 1017): name = bluetooth_headset_priority_08:EC:A9:50:76:27
D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1017): selectionArgs: false
,D/SettingsProvider( 1017): selectionArgs: 1002
D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
E/BluetoothHeadset( 5954): BTStateChangeCB is registed
I/BluetoothBondStateMachine( 2630): StableState(): Entering Off State
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.watchmanagerstub, destAppInfo.processName = com.android.bluetooth
,E/BluetoothHeadset( 5954): BluetoothHeadset service is binded
,D/GMFPReceiver( 5954): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 5954): jangil::setProperties()
,D/GMFPReceiver( 5954): jangil::printBTStatus()
,D/SettingsProvider( 1017): name = Wearable0001
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5954): ::::::::Wearable0001::false
,D/SettingsProvider( 1017): name = Wearable0002
,D/SettingsProvider( 1017): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1017): projectionArgs: isSettingsChangesAllowed
,D/SettingsProvider( 1017): selectionArgs: false
D/SettingsProvider( 1017): selectionArgs: 10098
,D/SecContentProvider( 1017): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1017): ret = -1
,D/GMFPReceiver( 5954): ::::::::Wearable0002::false
,D/GMFPReceiver( 5954): onServiceConnected() : 1
D/GMFPReceiver( 5954): mBluetoothHeadset = true
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.gms
,E/SMD     (  290): DCD OFF
,W/bt-btif ( 2630): new conn_srvc id:26, app_id:1
,W/bt-btif ( 2630): bta_dm_pm_ssr conn_srvc id:26, app_id:1
,W/bt-btif ( 2630): bta_dm_pm_ssr:2, lat:1200
,E/BluetoothRemoteDevices( 2630): setRfcommConnected true
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onSocketConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Socket connection succeeded (using system decided port), total number of attempts: 1 (thread ID: 1079)
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesWritten: 83 bytes successfully written (thread ID: 1080)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Outgoing connection initialized (*handshake* thread ID: 1080)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Exiting thread (thread ID: 1079)
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Entering thread (ID: 1080)
,D/WifiP2pService( 1017): InactiveState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): onBytesRead: Read 83 bytes successfully (thread ID: 1080)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread( 6147): Handshake succeeded with [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onHandshakeSucceeded: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 6147): Exiting thread (ID: 1080)
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): onConnected: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/io.jxcore.node.ConnectionHelper( 6147): hasConnection: No connection with peer with ID 08:EC:A9:50:76:27
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,I/io.jxcore.node.ConnectionHelper( 6147): onConnected: Outgoing socket thread, for peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], created successfully
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setInsecureRfcommSocketPort: Will use port -1 when trying to connect
,D/io.jxcore.node.ConnectionHelper( 6147): onConnected: The total number of connections is now 1
,D/io.jxcore.node.OutgoingSocketThread( 6147): Entering thread (ID: 1081)
,D/io.jxcore.node.OutgoingSocketThread( 6147): Server socket local port: 47684
I/io.jxcore.node.OutgoingSocketThread( 6147): Now accepting connections...
,I/io.jxcore.node.ConnectionHelper( 6147): onListeningForIncomingConnections: Outgoing connection is using port 47684 (peer ID: 08:EC:A9:50:76:27)
,I/jxcore-log( 6147): 2016-01-15T18:52:52.545Z SendDataConnector.js: CLIENT connected to 47684, error: null
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:52.546Z SendDataConnector.js: CLIENT starting client 
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:52.550Z SendDataConnector.js: CLIENT now sending 100000 bytes of data
I/jxcore-log( 6147): 
,I/io.jxcore.node.OutgoingSocketThread( 6147): Incoming data from address: /127.0.0.1, port: 47684
D/io.jxcore.node.OutgoingSocketThread( 6147): Setting local streams and starting stream copying threads...
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
I/io.jxcore.node.StreamCopyingThread( 6147): setBufferSize: Setting buffer size to 8192 bytes
,I/io.jxcore.node.OutgoingSocketThread( 6147): startStreamCopyingThreads: OK
D/io.jxcore.node.OutgoingSocketThread( 6147): Exiting thread (ID: 1081)
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1082, name: Sender)
,D/io.jxcore.node.StreamCopyingThread( 6147): Entering thread (ID: 1083, name: Receiver)
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:3324,
D/WifiP2pService( 1017): InactiveState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/jxcore-log( 6147): 2016-01-15T18:52:53.023Z SendDataConnector.js: CLIENT is data received : 10000
I/jxcore-log( 6147): 
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:18628
,I/jxcore-log( 6147): 2016-01-15T18:52:53.073Z SendDataConnector.js: CLIENT is data received : 20000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.135Z SendDataConnector.js: CLIENT is data received : 30000
I/jxcore-log( 6147): 
,D/        ( 2630): PORT_WriteDataCO: tx queue is full,tx.queue_size:11132,tx.queue.count:11,available:7496
,I/jxcore-log( 6147): 2016-01-15T18:52:53.184Z SendDataConnector.js: CLIENT is data received : 40000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.188Z SendDataConnector.js: CLIENT is data received : 50000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.233Z SendDataConnector.js: CLIENT is data received : 60000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.320Z SendDataConnector.js: CLIENT is data received : 70000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.422Z SendDataConnector.js: CLIENT is data received : 80000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.426Z SendDataConnector.js: CLIENT is data received : 90000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.468Z SendDataConnector.js: CLIENT is data received : 100000
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:52:53.469Z SendDataConnector.js: got all data for this round
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): oneRoundDownNow
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:53.470Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6147): 
I/jxcore-log( 6147): 2016-01-15T18:52:53.470Z SendDataConnector.js: CLIENT closeClientSocket
I/jxcore-log( 6147): 
,D/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Trying to close connection to peer with ID 08:EC:A9:50:76:27
,I/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 08:EC:A9:50:76:27
I/io.jxcore.node.OutgoingSocketThread( 6147): close
D/io.jxcore.node.OutgoingSocketThread( 6147): close: Stopping receiving thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1083
D/io.jxcore.node.OutgoingSocketThread( 6147): close: Stopping sending thread...
I/io.jxcore.node.StreamCopyingThread( 6147): doStop: Thread ID: 1082
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local input stream...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the local output stream...
D/io.jxcore.node.OutgoingSocketThread( 6147): closeLocalSocketAndStreams: Closing the localhost socket...
I/io.jxcore.node.OutgoingSocketThread( 6147): closeBluetoothSocketAndStreams
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@33de716d, channel: 6, state: CONNECTED
D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@33de716d, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@393b1a2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b4e2e33mSocket: android.net.LocalSocket@10cf65f0 impl:android.net.LocalSocketImpl@20fdb769 fd:FileDescriptor[111]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@10cf65f0 impl:android.net.LocalSocketImpl@20fdb769 fd:FileDescriptor[111]
W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1083, thread name: Receiver): bt socket closed, read return: -1
E/io.jxcore.node.OutgoingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] disconnected: Either failed to read from the output stream or write to the input stream: bt socket closed, read return: -1
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@33de716d, channel: 6, state: CLOSED
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@33de716d, channel: 6, state: CLOSED
,D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
W/io.jxcore.node.StreamCopyingThread( 6147): Either failed to read from the output stream or write to the input stream (thread ID: 1082, thread name: Sender): Socket closed
I/io.jxcore.node.ConnectionHelper( 6147): disconnectOutgoingConnection: Successfully disconnected (peer ID: 08:EC:A9:50:76:27
E/io.jxcore.node.OutgoingSocketThread( 6147): Unidentified stream copying thread failed with error: Either failed to read from the output stream or write to the input stream: Socket closed
,W/io.jxcore.node.ConnectionHelper( 6147): onDisconnected: Outgoing connection, peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] disconnected: Either failed to read from the output stream or write to the input stream: Socket closed
E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27,
,D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1082, name: Sender)
,I/jxcore-log( 6147): 2016-01-15T18:52:53.474Z SendDataConnector.js: Mobile.Disconnect() callback with peer 08:EC:A9:50:76:27
I/jxcore-log( 6147): 
E/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 08:EC:A9:50:76:27
,D/io.jxcore.node.ConnectionHelper( 6147): closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
D/io.jxcore.node.StreamCopyingThread( 6147): Exiting thread (ID: 1083, name: Receiver)
I/jxcore-log( 6147): ---- round done--------
I/jxcore-log( 6147): ,
I/jxcore-log( 6147): startWithNextDevice
I/jxcore-log( 6147): 
,W/bt-btif ( 2630): bta_jv_rfc_port_to_cb(port_handle:0xf):jv handle:0x0 not FOUND,
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/WifiP2pService( 1017): P2pEnabledState receive service response,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,E/bt-btm  ( 2630): Reset sec_bd_name and name flag. (BR/EDR link),
E/bt-btm  ( 2630): btm_sec_disconnected - Clearing Pending flag
,D/KeyguardViewMediator( 1177): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver onReceive
,D/KnoxKeyguardUpdateMonitor( 1017): BroadcastReceiver ACTION_ACL_DISCONNECTED
,V/BluetoothEventManager( 1316): Received android.bluetooth.device.action.ACL_DISCONNECTED
E/BluetoothEventManager( 1316): ACTION_ACL_DISCONNECTED
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterService( 2630): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@34b9bcb6
,D/BtConfig.SecureMode( 2630): isSecureModeOn:false
,D/SecContentProvider( 1017): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2630): action: android.bluetooth.device.action.ACL_DISCONNECTED, state: -2147483648
,D/KeyguardViewMediator( 1177): isGear1: device is not B1!
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
,W/ActivityManager( 1017): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.google.android.googlequicksearchbox
,I/BTConnectionReceiver( 6020): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=512, deviceClass=524]
,I/BluetoothClassifier( 6020): Bluetooth Device Name: Thali Test (Galaxy A3)
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,V/AlarmManager( 1017): waitForAlarm result :8
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac,
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState clear service request,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): InactiveState{ what=139301 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler },
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services,
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/wpa_supplicant( 1383): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 1383): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"LGE-LG-D722_PT3965","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965] already in the list, will not add again
,D/TimaService( 1017): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1017): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1017): TimaServiceHandler.handleMessage what =1
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 LGE-LG-D722_PT3965], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 LGE-LG-D722_PT3965]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1017): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1017): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/Watchdog( 1017): !@Sync 20,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1017): Plugged,
D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,I/PowerManagerService( 1017): [PWL] Off : 525s ago
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,W/ContextImpl( 1017): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
,D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
,I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 21
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: RESTARTING
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
,D/WifiP2pService( 1017): InactiveState{ what=147493 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1017): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1177): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): Start timer timeout, starting now...
,D/WifiP2pService( 1017): InactiveState{ what=139265 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139265 }
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1017): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1017): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
D/WifiP2pService( 1017): P2pEnabledState add service request,
D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017): Received list of peers.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): InactiveState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1017): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1017): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1017): stay LED for fully charged
D/BatteryService( 1017): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1017): Plugged,
I/MotionRecognitionService( 1017): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2630): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2630): Disconnected process message: 10
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1017): InactiveState{ what=139283 },
D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,E/SMD     (  290): DCD OFF
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1017): P2pEnabledState add service request
,D/WifiP2pManager( 6147): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 6147): timeout now
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): weAreDoneNow, resultArray.length: 3
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): sendReportNow
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): done, now sending data to server
I/jxcore-log( 6147): 
,I/jxcore-log( 6147): 2016-01-15T18:53:58.139Z SendDataConnector.js: CLIENT Stop now
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c,
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"samsung-SM-A500FU_PT3714","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
,W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147477 },
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiDisplayController( 1017): Received list of peers.,
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
,D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true,
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT3714]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/SSRM:n  ( 1017): SIOP:: AP = 260,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:F,C:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1017): Do not check CP during LCD off.,
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,E/SMD     (  290): DCD OFF
,E/Watchdog( 1017): !@Sync 22
,D/SSRM:n  ( 1017): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1017): !@BatteryListener : batteryPropertiesChanged!
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1017): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): restart: Restarting...
,D/WifiP2pService( 1017): InactiveState{ what=139301 },
D/WifiP2pService( 1017): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1017): P2pEnabledState add service request
D/WifiP2pManager( 6147): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service request added successfully
,D/WifiP2pService( 1017): InactiveState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1017): P2pEnabledState discover services
,D/WifiService( 1017): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1017): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1017): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1017): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1383): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service discovery started successfully,
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 },
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac,
D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/WifiDisplayController( 1017): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onP2pDeviceListChanged: 13 device(s) discovered
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 3: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 4: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A5) 7e:f9:0e:51:18:23
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 7: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 8: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 9: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 10: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 11: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 12: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onP2pDeviceListChanged: Peer 13: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1017): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Updating the timestamp of peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT4558]
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
,D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"samsung-SM-N910C_PT8999","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT8999] already in the list, will not add again
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"LGE-LG-D855_PT8254","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
D/WifiP2pService( 1017): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254]
,I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [58:3F:54:73:64:C0 LGE-LG-D855_PT8254], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8254] already in the list, will not add again
,E/SMD     (  290): DCD OFF
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"samsung-SM-A300FU_PT7121","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT7121] already in the list, will not add again
,D/WifiP2pService( 1017): InactiveState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1017): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:51:18:22","pn":"samsung-SM-A500FU_PT4798","ra":"7C:F9:0E:51:18:22"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): onServiceDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798]
I/io.jxcore.node.ConnectionHelper( 6147): onPeerDiscovered: [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798], Bluetooth address: 7C:F9:0E:51:18:22, device name: Thali Test (Galaxy A5), device address: 7e:f9:0e:51:18:23
W/io.jxcore.node.ConnectionHelper( 6147): modifyListOfDiscoveredPeers: Peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT4798] already in the list, will not add again
,I/jxcore-log( 6147): teardown,
I/jxcore-log( 6147): 
I/jxcore-log( 6147): testSendData stopped
I/jxcore-log( 6147): 
I/io.jxcore.node.ConnectionHelper( 6147): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): shutdown
D/BluetoothSocket( 6147): close() in, this: android.bluetooth.BluetoothSocket@1e1f45ee, channel: 6, state: LISTENING,
D/BluetoothSocket( 6147): close() this: android.bluetooth.BluetoothSocket@1e1f45ee, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@34e4fb66, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1eb37a8fmSocket: android.net.LocalSocket@1b5cf11c impl:android.net.LocalSocketImpl@fb16125 fd:FileDescriptor[110]
D/BluetoothSocket( 6147): Closing mSocket: android.net.LocalSocket@1b5cf11c impl:android.net.LocalSocketImpl@fb16125 fd:FileDescriptor[110]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6147): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6147): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: No more listeners, de-initializing...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6147): setState: NOT_STARTED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): stop: Stopping peer discovery...
D/WifiP2pService( 1017): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6147): stop: Stopping services
D/WifiP2pService( 1017): P2pEnabledState{ what=139298 }
D/WifiP2pService( 1017): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): onIsWifiPeerDiscoveryStartedChanged: false,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6147): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6147): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6147): setState: NOT_STARTED
,I/jxcore-log( 6147): StopBroadcasting went ok
I/jxcore-log( 6147): 
,D/WifiP2pService( 1017): InactiveState{ what=139268 }
,I/wpa_supplicant( 1383): P2P-FIND-STOPPED 
,I/jxcore-log( 6147): ****TEST TOOK:  ms ****
I/jxcore-log( 6147): 
D/WifiP2pService( 1017): InactiveState{ what=139307 }
I/jxcore-log( 6147): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6147): 
D/WifiP2pService( 1017): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1017): P2pEnabledState clear service request
D/WifiP2pService( 1017): remove channel information from framework
D/WifiP2pService( 1017): InactiveState{ what=147493 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1017): discovery change broadcast false
,I/jxcore-log( 6147): 2016-01-15T18:54:17.999Z SendDataTCPServer.js: TCP/IP server  socket is disconnected
I/jxcore-log( 6147): 
I/chromium( 6147): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6147): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6147): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6147): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6147): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6147): Service requests cleared successfully
,I/wpa_supplicant( 1383): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1383): P2P-DEVICE-FOUND 7E.18.23 p2p_dev_addr=7E.18.23 pri_dev_type=10-0050F204-5  ' A5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1017): InactiveState{ what=147477 }
D/WifiP2pService( 1017): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1017): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1017): DefaultState{ what=139283 }
,D/WifiDisplayController( 1017): Received list of peers.
,D/WifiP2pService( 1017): InactiveState{ what=139283 }
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1017): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1017): DefaultState{ what=139283 }
D/WifiDisplayController( 1017): Received list of peers.
D/WifiDisplayController( 1017):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A5), deviceAddress: 7e:f9:0e:51:18:23, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1017):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1017):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/AndroidRuntime( 6844): ,
D/AndroidRuntime( 6844): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6844): CheckJNI is OFF,
D/AndroidRuntime( 6844): readGMSProperty: start
,D/AndroidRuntime( 6844): readGMSProperty: already setted!!
D/AndroidRuntime( 6844): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6844): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6844): readGMSProperty: end
D/AndroidRuntime( 6844): addProductProperty: start
,E/AffinityControl( 6844): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6844): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1017): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1017): START PACKAGE DELETE: observer{580341279}
D/PackageManager( 1017): pkg{<packageName>}
D/PackageManager( 1017): user{0}
D/PackageManager( 1017): caller{2000}
D/PackageManager( 1017): flags{3}
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1017): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1017): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1017): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1017): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1017): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1017): Killing 6147:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/InputDispatcher( 1017): channel ~ Consumer closed input channel or an error occurred.  events=0x9
W/PackageSettings( 1017): Skipping PackageSetting{360ed769 com.example.hello/10346} due to missing metadata
E/InputDispatcher( 1017): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 1017): Attempted to unregister already unregistered input channel
I/WindowState( 1017): WIN DEATH: Window{2fcb7afd u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  259): id=14 Removed NainActivit (6/8)
,I/SurfaceFlinger(  259): id=14 Removed NainActivit (-2/8),
,D/InputDispatcher( 1017): Focus left window: 6147
,D/PointerIcon( 1017): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1017): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1017):   Force finishing activity ActivityRecord{31ab4e63 u0 com.test.thalitest/.MainActivity t20},
,W/ActivityManager( 1017): Spurious death for ProcessRecord{1f33e56c 6147:com.test.thalitest/u0a338}, curProc for 6147: null
D/InputDispatcher( 1017): Focused application released
,I/ActivityManager( 1017): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1017): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 6020): Explicit concurrent mark sweep GC freed 14833(851KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 6MB/8MB, paused 817us total 38.130ms
,I/art     ( 3851): Explicit concurrent mark sweep GC freed 3152(189KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 760us total 29.158ms
,E/SamsungIME( 1863): mOCRHelper is null
,W/GeofencerStateMachine( 1831): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1017): Reconfiguring input devices.  changes=0x00000010
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 15 19:54:18 GMT+01:00 2016
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3607): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1017): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
I/splitIntent( 1017): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1017): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1017): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/SMD     (  290): DCD OFF
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1017): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1017): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1017): no available spell checker services found
,E/Zygote  ( 6857): MountEmulatedStorage()
E/Zygote  ( 6857): v2
I/libpersona( 6857): KNOX_SDCARD checking this for 10090
I/libpersona( 6857): KNOX_SDCARD not a persona
,I/SELinux ( 6857): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1017): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6857 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6857): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6857): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onCreate()
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6857): TimaSignature is unavailable
,D/ActivityThread( 6857): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3607): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3607): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1444): empty dynamic service
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1017): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1017): mCursor = null
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6857): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6857): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6857): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 46974(7MB) AllocSpace objects, 37(596KB) LOS objects, 33% free, 24MB/37MB, paused 3.132ms total 217.255ms
,I/art     ( 1017): WaitForGcToComplete blocked for 203.200ms for cause Explicit
,D/elm:15121( 6857): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6857): ElmAgentService : onCreate()
,D/elm:15121( 6857): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 6857): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6857): MDMBridge.getInstance()
D/elm:15121( 6857): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6857): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15121( 6857): ElmAgentService : onDestroy().
,I/ActivityManager( 1017): Killing 5908:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 3607): KLMSIntentService(): onDestroy()
,W/ResourceType( 1017): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1017): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1017): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1017): Explicit concurrent mark sweep GC freed 10103(496KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.015ms total 155.101ms
,D/RCPManagerService( 1017): PackageReceiver onReceive()
,I/HarmonyEASService( 1017): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1017): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1017): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1017): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1017): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1017): failed to open /acct/uid_10152/pid_5908/cgroup.procs: No such file or directory
,D/PackageManager( 1017): delete codoeFile: 
,D/AASAuninstall( 1017): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
I/AASA_removePackage( 1017): UID=10338 Target=com.test.thalitest
,D/PackageManager( 1017): result of delete: 1{580341279}
,D/AndroidRuntime( 6844): Shutting down VM
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
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1017): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED,
V/EnterpriseBillingPolicy( 1017): uID is 10338
V/EnterpriseBillingPolicy( 1017): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1017): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1017): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1017): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1017): MSG_TYPE_APP_REMOVED::
D/TaskPersister( 1017): removeObsoleteFile: deleting file=20_task.xml
,I/PCWCLIENTTRACE_PushUtil( 5775): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5775): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5775): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5775): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1017): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6874 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/Zygote  ( 6874): MountEmulatedStorage()
E/Zygote  ( 6874): v2
I/libpersona( 6874): KNOX_SDCARD checking this for 10029
I/libpersona( 6874): KNOX_SDCARD not a persona
,I/SELinux ( 6874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6874): TimaSignature is unavailable
D/ActivityThread( 6874): Added TimaKeyStore provider
,I/SA      ( 5898): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5898): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/FeatureConfig( 6874): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 1017): Killing 5881:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,W/ActivityManager( 1017): userId = 0, bbcId = -10000
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6874): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/PackagesMonitor( 4958): PackagesMonitor onReceive :com.test.thalitest
,W/ResourcesManager( 6874): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1017): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6874): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 6893): MountEmulatedStorage(),
I/libpersona( 6893): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6893): v2
I/libpersona( 6893): KNOX_SDCARD not a persona
I/SELinux ( 6893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1017): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6893 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 6893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6893): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/art     ( 6844): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,W/ResourcesManager( 6874): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6893): TimaSignature is unavailable
,D/ActivityThread( 6893): Added TimaKeyStore provider
,W/ResourcesManager( 6874): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6874): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6893): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6893): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6893): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6893): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6893): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6874): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6874): system/finder_cp/cpdata.xml file not found
,D/Mms/MmsApp( 6893): [start]    onCreate() consume time = 0.0
,W/libprocessgroup( 1017): failed to open /acct/uid_1000/pid_5881/cgroup.procs: No such file or directory
,W/ActivityManager( 1017): userId = 0, bbcId = -10000,
W/ActivityManager( 1017): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1017): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
