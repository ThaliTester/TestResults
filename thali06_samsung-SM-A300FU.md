#### Test 55431344e5dd625_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main
E/SMD     (  294): DCD OFF
,D/AndroidRuntime( 6381): 
D/AndroidRuntime( 6381): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6381): CheckJNI is OFF
D/AndroidRuntime( 6381): readGMSProperty: start
D/AndroidRuntime( 6381): readGMSProperty: already setted!!
D/AndroidRuntime( 6381): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6381): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6381): readGMSProperty: end
D/AndroidRuntime( 6381): addProductProperty: start
E/AffinityControl( 6381): AffinityControl: registerfunction enter
D/AndroidRuntime( 6381): Calling main entry com.android.commands.am.Am
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
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6393 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1476
E/Zygote  ( 6393): MountEmulatedStorage()
E/Zygote  ( 6393): v2
I/libpersona( 6393): KNOX_SDCARD checking this for 10338
I/libpersona( 6393): KNOX_SDCARD not a persona
D/AndroidRuntime( 6381): Shutting down VM
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SELinux ( 6393): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SurfaceFlinger(  257): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6393): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6393): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 6393): TimaSignature is unavailable
D/ActivityThread( 6393): Added TimaKeyStore provider
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/9)
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
V/ActivityThread( 1476): updateVisibility : ActivityRecord{13008924 token=android.os.BinderProxy@619a070 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1476): onTrimMemory. Level: 20
I/WebViewFactory( 6393): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6393): Time to load native libraries: 1 ms (timestamps 5338-5339)
I/LibraryLoader( 6393): Expected native library version number "",actual native library version number ""
W/art     ( 6381): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,V/WebViewChromiumFactoryProvider( 6393): Binding Chromium to main looper Looper (main, tid 1) {11fbb58a}
,I/LibraryLoader( 6393): Expected native library version number "",actual native library version number ""
,I/chromium( 6393): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6393): Initializing chromium process, singleProcess=true
,W/art     ( 6393): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6393): ApplicationContext is null in ApplicationStatus
,W/chromium( 6393): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6393): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6393): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6393): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6393): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6393): Local Branch: 
I/Adreno-EGL( 6393): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6393): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6393):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6393): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6393): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6393): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6393): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6393): CordovaWebView is running on device made by: samsung
,W/art     ( 6393): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6393): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{eb3c4dd u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6393): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false,
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false,
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
W/chromium( 6393): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
V/ActivityThread( 6393): updateVisibility : ActivityRecord{1a2475c7 token=android.os.BinderProxy@219a41e1 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6393): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6393): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6393
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6393): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6393): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6393): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 6393): Enabling debug mode 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager( 1018): Displayed Component not be shown by security: +665ms (total +38s270ms)
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{eb3c4dd u0 com.test.thalitest/.MainActivity t20} time:155866
W/ActivityManager( 1018): mDVFSHelper.release()
I/SurfaceFlinger(  257): id=13 Removed uhalitest (7/9)
I/SurfaceFlinger(  257): id=13 Removed uhalitest (-2/9)
W/IInputConnectionWrapper( 6393): showStatusIcon on inactive InputConnection
I/SamsungIME( 1785): getCurrentCandidateView
I/Timeline( 6393): Timeline: Activity_idle id: android.os.BinderProxy@219a41e1 time:155883
D/SamsungIME( 1785): Dismiss ExpandCandiate
I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
I/SamsungIME( 1785): getDebugLevel  : 0x4f4c
I/SamsungIME( 1785): KeybaordView init() : load resources
I/SamsungIME( 1785): getCurrentKeyboard
I/SamsungIME( 1785): getTextKeyboard
W/BindingManager( 6393): Cannot call determinedVisibility() - never saw a connection for the pid: 6393
D/SamsungIME( 1785): [SwiftkeyWrapper] currentLangauge : 1701729619
D/JsMessageQueue( 6393): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6393): JniHelper::setJavaVM(0xb77f9448), pthread_self() = -1210797616
D/JX-Cordova( 6393): jxcore cordova android initializing
D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2662): Disconnected process message: 10
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,W/jxcore-log( 6393): Initializing JXcore engine
W/jxcore-log( 6393): JXcore engine is ready
,W/jxcore-log( 6393): Starting JXcore engine
,E/audit   ( 1881): type=1400 msg=audit(1452238037.697:205): avc:  denied  { ioctl } for  pid=6393 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1881):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1881): type=1300 msg=audit(1452238037.697:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=bebdfd58 items=0 ppid=315 ppcomm=main pid=6393 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1881): type=1320 msg=audit(1452238037.697:205): 
,W/jxcore-log( 6393): Platform android
W/jxcore-log( 6393): 
W/jxcore-log( 6393): Process ARCH arm
W/jxcore-log( 6393): 
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/jxcore-log( 6393): JXcore Cordova bridge is ready!
I/jxcore-log( 6393): 
,W/jxcore-log( 6393): JXcore engine is started
,I/Choreographer( 6393): Skipped 131 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6393): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF,
,I/jxcore-log( 6393): Toggling radios to true,
I/jxcore-log( 6393): 
,D/BluetoothAdapter( 6393): enable(),
,D/BluetoothAdapter( 6393): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6393, uid=10338
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6393, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6393, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6393, uid=10338
,I/wpa_supplicant( 1394): [wpa_supplicant_ctrl_iface_process] : DISCONNECT,
,I/jxcore-log( 6393): Radios toggled
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): Received device characteristics:
I/jxcore-log( 6393): Bluetooth address: 08:EC:A9:50:75:41
I/jxcore-log( 6393): Bluetooth name: A3-1
I/jxcore-log( 6393): Device name: samsung-SM-A300FU
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): Perf Test app loaded loaded
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): check test folder
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): found test : ./testFindPeers.js
I/jxcore-log( 6393): 
,I/wpa_supplicant( 1394): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1394): wlan0: State: COMPLETED -> DISCONNECTED
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1394): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> DISCONNECTED
E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1394): reset timer : RESET_TIMER 0,
,I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec
E/wpa_supplicant( 1394): Cmd 35605 not handled
I/wpa_supplicant( 1394): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1394): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1394): First Scan Start
I/wpa_supplicant( 1394): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1018): InitialState.processMessage what=4
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/Tethering( 1018): No numeric data
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
I/jxcore-log( 6393): found test : ./testSendData.js
I/jxcore-log( 6393): 
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,V/NetworkStats( 1018): performPollLocked() took 9ms
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1018): do suspend true,
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1667): Read error: ssl=0xb7d889c8: I/O error during system call, Connection timed out
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700",
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
I/wpa_supplicant( 1394): wlan0: Setting scan request: 0 sec 0 usec,
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,V/NativeCrypto( 1667): SSL shutdown failed: ssl=0xb7d889c8: I/O error during system call, Broken pipe
,E/WifiNative-wlan0( 1018): do suspend true
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/qtaguid ( 1018): Tagging socket 337 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2105): Starting #8
,I/Hs20UtilService( 2105): Message received 5007
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NearbySettings( 1346): DMSUtil.isNetworkConnected - flag-null, state-null
,I/qtaguid ( 1018): Untagging socket 337
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1346): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1346): MountReceiver.mPrefHandler - 7002
,D/CommandListener(  278): Clearing all IP addresses on wlan0,
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 0 for uid 1000
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524292
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1452): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/TelephonyNetworkFactory( 1452): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-4ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,E/Zygote  ( 6450): MountEmulatedStorage()
,E/Zygote  ( 6450): v2
I/libpersona( 6450): KNOX_SDCARD checking this for 10102
I/libpersona( 6450): KNOX_SDCARD not a persona
,I/SELinux ( 6450): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6450 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
I/SELinux ( 6450): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6450): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false,
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 3ms
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6450): TimaSignature is unavailable
D/ActivityThread( 6450): Added TimaKeyStore provider
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
W/ResourcesManager( 6450): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Choreographer( 6393): Skipped 120 frames!  The application may be doing too much work on its main thread.
I/chromium( 6393): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
D/PhoneApp( 1452): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1452): FileWriteThread : threadType = 3
,I/Babel_SMS( 6450): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6450): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6450): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,I/Babel_SMS( 6450): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6450): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 6450): MmsConfig.loadFromResources
E/Babel_SMS( 6450): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6450): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml,
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  286): getCameraInfo: X
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  286): getCameraInfo: X
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/Settings( 6450): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6450): startup - clean
,I/Babel   ( 6450): deleted: false for 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2105): Starting #9
D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1346): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 2105): Message received 5007
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1346): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1346): MountReceiver.mPrefHandler - 7002
,W/VideoCapabilities( 6450): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6450): Unsupported mime audio/evrc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/AudioCapabilities( 6450): Unsupported mime audio/qcelp
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6450): Unsupported mime audio/mpeg-L1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/AudioCapabilities( 6450): Unsupported mime audio/mpeg-L2
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6450): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6450): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6450): Unsupported mime audio/qcelp
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/AudioCapabilities( 6450): Unsupported mime audio/evrc
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
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6450): Unsupported mime video/wvc1
,W/VideoCapabilities( 6450): Unsupported mime video/x-ms-wmv
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,W/VideoCapabilities( 6450): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6450): Unsupported mime video/wvc1
,W/VideoCapabilities( 6450): Unsupported mime video/x-ms-wmv
,I/PCWCLIENTTRACE_PushUtil( 5914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5914): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5914): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6450): Unsupported mime video/x-ms-wmv7
I/PCWCLIENTTRACE_SYSTEMReceiver( 5914): noConnectivity : true
,W/VideoCapabilities( 6450): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 6450): Unsupported mime video/mp43
,E/Zygote  ( 6492): MountEmulatedStorage()
E/Zygote  ( 6492): v2,
I/libpersona( 6492): KNOX_SDCARD checking this for 10108
I/libpersona( 6492): KNOX_SDCARD not a persona
,I/SELinux ( 6492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6492 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 6450): Unsupported mime video/sorenson
,D/TimaKeyStoreProvider( 6492): TimaSignature is unavailable
,D/ActivityThread( 6492): Added TimaKeyStore provider
,W/VideoCapabilities( 6450): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6450): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6450): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6450): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6450): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6450): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager( 1018): Killing 5787:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/vclib   ( 6450): onServiceConnected
,W/Babel   ( 6450): Attempted to change video mute state without an active call.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/MusicStore( 6492): Database version: 120
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/wpa_supplicant( 1394): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 1394): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1394): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1394): Trying to associate with  'G700'
I/wpa_supplicant( 1394): Re-associate with C0.AA.48
I/wpa_supplicant( 1394): wlan0: State: SCANNING -> ASSOCIATING
D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_5787/cgroup.procs: No such file or directory
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6492): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6492): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6492): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/wpa_supplicant( 1394): Cmd 35605 not handled
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1394): wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1394): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1394): Associated with C0.AA.48
I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1394): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 1394): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 1394): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
E/Tethering( 1018): No numeric data
I/wpa_supplicant( 1394): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1394): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,I/wpa_supplicant( 1394): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1018): clearTetheredNotification()
I/wpa_supplicant( 1394): Blacklist: Clear (temp) 
I/wpa_supplicant( 1394): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true,
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/HotspotTile( 1174): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1174): updateTetherState():false, false
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NetworkStats( 1018): performPollLocked() took 4ms
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit,
E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
W/ResourcesManager( 6492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,V/JNIHelp ( 6492): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,D/CommandListener(  278): Setting iface cfg,
E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,E/WifiNative-wlan0( 1018): do suspend false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,W/ActivityThread( 6492): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6492): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8a0e713: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6492): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6492): GMSCore installation verified
,I/ConfigStore( 6492): Config Database version: 1,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,I/MediaRouter( 6492): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6492): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/SQLiteLog( 1667): (10) POSIX Error : 11 SQLite Error : 3850
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
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6523): MountEmulatedStorage(),
E/Zygote  ( 6523): v2
I/libpersona( 6523): KNOX_SDCARD checking this for 10001
I/libpersona( 6523): KNOX_SDCARD not a persona
,I/SELinux ( 6523): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6523 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6523): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/dhcpcd  ( 6522): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
E/SELinux ( 6523): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/dhcpcd  ( 6522): version 5.5.6 starting
,E/dhcpcd  ( 6522): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/GHttpClientFactory( 6492): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,I/GoogleURLConnFactory( 6492): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6523): TimaSignature is unavailable
,D/ActivityThread( 6523): Added TimaKeyStore provider
,I/dhcpcd  ( 6522): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6522): wlan0: sendmsg: Cannot assign requested address
,I/dhcpcd  ( 6522): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6522): bssid match
,I/dhcpcd  ( 6522): wlan0: rebinding lease of 192.168.1.132
,I/ActivityManager( 1018): Killing 5802:com.wsomacp/u0a23 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6548): MountEmulatedStorage()
E/Zygote  ( 6548): v2
,I/libpersona( 6548): KNOX_SDCARD checking this for 1000
I/libpersona( 6548): KNOX_SDCARD not a persona
,I/SELinux ( 6548): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6548 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 5865:com.samsung.helphub/1000 (adj 15): empty #31
,I/SELinux ( 6548): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6548): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6548): TimaSignature is unavailable
,D/ActivityThread( 6548): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 6548): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_5802/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5865/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6548): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6548): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,I/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6548): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6563): MountEmulatedStorage()
E/Zygote  ( 6563): v2
I/libpersona( 6563): KNOX_SDCARD checking this for 10008
I/libpersona( 6563): KNOX_SDCARD not a persona
,I/SELinux ( 6563): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6563 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5743:com.android.mms/u0a41 (adj 15): empty #31
,I/SELinux ( 6563): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6563): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6563): TimaSignature is unavailable
,D/ActivityThread( 6563): Added TimaKeyStore provider
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/CountryDetector( 1018): No listener is left
,I/ActivityManager( 1018): Killing 5880:com.sec.spp.push/u0a32 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_5743/cgroup.procs: No such file or directory
,I/KLMS-2.5.123: ( 3618): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 08:27:22 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3618): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 3618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3618): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3618): StateImplV2(): networkChangeListener().END
,E/Zygote  ( 6579): MountEmulatedStorage(),
I/libpersona( 6579): KNOX_SDCARD checking this for 10031
E/Zygote  ( 6579): v2
I/libpersona( 6579): KNOX_SDCARD not a persona
I/SELinux ( 6579): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6579 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6579): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6579): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6579): TimaSignature is unavailable
,D/ActivityThread( 6579): Added TimaKeyStore provider
,I/SO_AGENT( 6579): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5946): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5880/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5946): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/SA      ( 6096): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 6096): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6096): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5946): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,I/SA      ( 6096): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 5946): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5946): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 6096): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6096): [OR] == isSIMCardReady false ==
,I/SA      ( 6096): [SCU] == networkStateCheck == false
,I/SA      ( 6096): [OR] onReceive END
,I/ActivityManager( 1018): Killing 5897:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/accuweather( 1599): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1647): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1599): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1599): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1599): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1599): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1599): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1599): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6596): MountEmulatedStorage(),
E/Zygote  ( 6596): v2
I/libpersona( 6596): KNOX_SDCARD checking this for 10121
I/libpersona( 6596): KNOX_SDCARD not a persona
,I/SELinux ( 6596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6596): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6596 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6596): TimaSignature is unavailable
,D/ActivityThread( 6596): Added TimaKeyStore provider
,W/ResourcesManager( 6596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6596): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.,
W/ResourcesManager( 6596): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6596): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6596): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6596): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6612): MountEmulatedStorage(),
E/Zygote  ( 6612): v2
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6612 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/libpersona( 6612): KNOX_SDCARD checking this for 10141
I/libpersona( 6612): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Killing 5418:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SELinux ( 6612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5897/cgroup.procs: No such file or directory
,I/SELinux ( 6612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6612): TimaSignature is unavailable
D/ActivityThread( 6612): Added TimaKeyStore provider
,W/ResourcesManager( 6612): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6612): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6612): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6612): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_5418/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6522): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/Zygote  ( 6635): MountEmulatedStorage()
E/Zygote  ( 6635): v2
I/libpersona( 6635): KNOX_SDCARD checking this for 10068
I/libpersona( 6635): KNOX_SDCARD not a persona
,I/SELinux ( 6635): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6635 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
,I/SELinux ( 6635): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6635): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6635): TimaSignature is unavailable
,D/ActivityThread( 6635): Added TimaKeyStore provider
,I/art     (  315): Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 21.758ms
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.936ms,
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 6635): onCreate
,D/BadgeProvider( 6635): DatabaseHelper
,I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.581ms
,I/dhcpcd  ( 6522): wlan0: leased 192.168.1.132 for 86400 seconds
,E/Zygote  ( 6652): MountEmulatedStorage(),
E/Zygote  ( 6652): v2
I/libpersona( 6652): KNOX_SDCARD checking this for 1000
I/libpersona( 6652): KNOX_SDCARD not a persona
,I/SELinux ( 6652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6652 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 5434:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
E/SELinux ( 6652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5319:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #32
,D/TimaKeyStoreProvider( 6652): TimaSignature is unavailable
,D/ActivityThread( 6652): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5319/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10029/pid_5434/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/SecurityLogAgent( 6652): KnoxConfiguration : Current State = 1,
D/SecurityLogAgent( 6652): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6652): StateMachine : Current State = 1
,D/SecurityLogAgent( 6652): StateMachine : Changed Current State = 1,
,I/ActivityManager( 1018): Killing 5962:com.google.android.apps.docs/u0a87 (adj 15): empty #31,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/iu.Environment( 1960): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 1960): num queued entries: 0
,I/iu.UploadsManager( 1960): num updated entries: 0
,I/iu.SyncManager( 1960): NEXT; no task
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.kids from APK com.google.android.gms
,E/WifiNative-wlan0( 1018): do suspend true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 66906(3MB) AllocSpace objects, 19(369KB) LOS objects, 33% free, 23MB/35MB, paused 4.635ms total 196.208ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/BadgeProvider( 6635): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/Zygote  ( 6691): MountEmulatedStorage()
,E/Zygote  ( 6691): v2
I/libpersona( 6691): KNOX_SDCARD checking this for 10032
I/libpersona( 6691): KNOX_SDCARD not a persona
I/SELinux ( 6691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6691 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,E/SELinux ( 6691): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
,E/ConnectivityService( 1018): updateNetworkInfo()
I/Babel   ( 6450): connection state changed from UNKNOWN to DISCONNECTED
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_5962/cgroup.procs: No such file or directory
D/BadgeProvider( 6635): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6635): sendNotify, [notify] : null
D/BadgeProvider( 6635): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6635): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6635): update, [UpdateCount] : 1
D/Launcher.Model( 1476): reloadBadges entered.
D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1018): LTETest block dns file not exists
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/TimaKeyStoreProvider( 6691): TimaSignature is unavailable
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
D/ActivityThread( 6691): Added TimaKeyStore provider
D/StatusBar.NetworkController( 1174): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1018): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
D/ConnectivityService( 1018):    accepting network in place of null
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1452): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1452): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
V/NetworkStats( 1018): updateIfacesLocked()
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/Tethering( 1018): MasterInitialState.processMessage what=3
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 3ms
D/StatusBar.NetworkController( 1174): EthernetConnected: false
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,E/SPPClientService( 6691): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 6691): [SystemStateMoniter] Current Time : 163211
,E/SPPClientService( 6691): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6691): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 6691): [SystemStateMoniter] No Connect : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6691): PushLog.txt file is not deleted.
,D/SPPClientService( 6691): PushLog.txt file is not deleted.
D/SPPClientService( 6691): ============PushLog. stop!
,E/Zygote  ( 6713): MountEmulatedStorage(),
E/Zygote  ( 6713): v2
I/libpersona( 6713): KNOX_SDCARD checking this for 10110
I/libpersona( 6713): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6713 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6713): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Killing 5978:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SELinux ( 6713): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
E/SELinux ( 6713): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SPPClientService( 6691): [[SystemStateMonitorService]] No Active Internet
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TimaKeyStoreProvider( 6713): TimaSignature is unavailable
,D/ActivityThread( 6713): Added TimaKeyStore provider
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 07:27:23 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452238043250], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452238043233]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,E/SMD     (  294): DCD OFF
D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524290
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION,
,D/StatusBar.NetworkController( 1174): EthernetConnected: false
,D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1174): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1174): updateDataNetType()
D/StatusBar.NetworkController( 1174): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1174): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1174): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1174): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1174): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1174): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1174): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_5978/cgroup.procs: No such file or directory,
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,I/GAv4    ( 6713): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6713):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6713):   adb logcat -s GAv4
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 6713): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6713): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6713): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6492): type=WIFI subType= reason=null isConnected=true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin,
D/SecContentProvider2( 1018): mCursor = null
,I/WebViewFactory( 6713): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6713): Time to load native libraries: 1 ms (timestamps 3774-3775)
I/LibraryLoader( 6713): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6713): Binding Chromium to main looper Looper (main, tid 1) {32609316}
,I/LibraryLoader( 6713): Expected native library version number "",actual native library version number "",
I/chromium( 6713): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6713): Initializing chromium process, singleProcess=true
,W/art     ( 6713): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6713): ApplicationContext is null in ApplicationStatus
,W/chromium( 6713): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6713): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6713): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6713): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6713): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6713): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6713): Local Branch: 
I/Adreno-EGL( 6713): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6713): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6713):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6713): Requires BLUETOOTH permission
,I/NSApplication( 6713): Starting up...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6769): MountEmulatedStorage()
,E/Zygote  ( 6769): v2
I/libpersona( 6769): KNOX_SDCARD checking this for 10077
I/libpersona( 6769): KNOX_SDCARD not a persona
,I/SELinux ( 6769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6769 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6769): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Killing 6017:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6769): TimaSignature is unavailable
,D/ActivityThread( 6769): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_6017/cgroup.procs: No such file or directory
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,D/WaitQueueForNetworkActivate( 6178): notifyNetworkActivated
,W/ContextImpl( 6178): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6178): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2105): Starting #10
,I/Hs20UtilService( 2105): Message received 5007
,D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1346): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1346): MountReceiver.onReceive - Keep current state
,D/InitializeManagerStateMachine( 6178): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6178): exit::IDLE
D/InitializeManagerStateMachine( 6178): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6178): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6178): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6178): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6178): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6178): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6178): entry::SUCCESS
D/hcjo    ( 6178): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6178): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6178): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
D/InitializeManagerStateMachine( 6178): exit::SUCCESS
D/InitializeManagerStateMachine( 6178): entry::IDLE
,I/Hs20UtilService( 2105): Starting #11
,I/Hs20UtilService( 2105): Message received 5007
,D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1346): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Killing 5998:com.sec.android.app.soundalive/u0a48 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2105): Starting #12
,D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1346): DMSUtil.isNetworkConnected - flag-null, state-null
I/Hs20UtilService( 2105): Message received 5007
I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1346): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1346): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2105): Starting #13
,I/Hs20UtilService( 2105): Message received 5007
,D/NearbySettings( 1346): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1346): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1018): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5914): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5914): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5914): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5914): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1018): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1018): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,V/MusicLeanback( 6492): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=4, Uoast,
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018,
,D/SRIB_DCS( 1174): log_dcs ThreadedRenderer::initialize entered! 
,I/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6548): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6548): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1018): failed to open /acct/uid_10048/pid_5998/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 5946): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5946): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/DBG_POLICYDM( 5946): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5946): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6563): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6563): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 3618): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Jan 08 08:27:24 GMT+01:00 2016
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3618): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onCreate()
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 3618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 3618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 3618): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 3618): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 3618): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 3618): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.123: ( 3618): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 3618): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5946): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5946): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5946): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5946): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 6096): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 6096): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6096): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6096): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6096): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 5946): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 6096): [SCU] == networkStateCheck == true
,I/SA      ( 6096): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6096): isChinaCountryCode : false
I/SA      ( 6096): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6096): [OR] == networkStateCheck true ==
,I/SA      ( 6096): [OR] GetMyCountryZoneTask
,I/SA      ( 6096): [OR] onReceive END
,I/DBG_POLICYDM( 5946): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts,
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/SA      ( 6096): [SRS] prepareGetMyCountryZone
I/DBG_POLICYDM( 5946): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
I/DBG_POLICYDM( 5946): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/accuweather( 1599): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/daemonapp( 1647): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,E/DBG_POLICYDM( 5946): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,D/accuweather( 1599): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1599): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1599): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1599): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,I/SA      ( 6096): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,D/accuweather( 1599): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 6096): [SSP] query invoked
,D/accuweather( 1599): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DBG_POLICYDM( 5946): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5946): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,D/QuickConnect( 6596): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6596): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/SA      ( 6096): [TPMU] GetMccFromDB : null
I/QuickConnect( 6596): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 6096): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6096): [TPM] isNoProxy(default) : true
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/File    ( 6096): fail readDirectory() errno=2
,D/SecurityLogAgent( 6652): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6652): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6652): StateMachine : Current State = 1
D/SecurityLogAgent( 6652): StateMachine : Changed Current State = 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10011
,I/iu.Environment( 1960): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.UploadsManager( 1960): num queued entries: 0
I/iu.UploadsManager( 1960): num updated entries: 0
,I/iu.SyncManager( 1960): NEXT; no task
,D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 1960): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6691): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6691): [SystemStateMoniter] Current Time : 164885
,E/SPPClientService( 6691): [SystemStateMoniter] No Connect : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,I/System.out( 6450): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 6450): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6450): (HTTPLog)-Static: isShipBuild true
I/System.out( 6450): (HTTPLog)-Thread-1077-36006909: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6450): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10102
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6178): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6178): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6178): exit::IDLE
D/InitializeManagerStateMachine( 6178): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6178): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6178): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6178): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6178): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6178): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6178): entry::SUCCESS
D/hcjo    ( 6178): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6178): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6178): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6178): exit::SUCCESS
D/InitializeManagerStateMachine( 6178): entry::IDLE
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 6450): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Kids    ( 1960): [AccountUtils] Account not ready
W/Kids    ( 1960): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 1960): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 1960): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 1960): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 1960): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 1960): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 1960): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 1960): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 1960): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 1960): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 1960): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 1960): 	at java.lang.Thread.run(Thread.java:818)
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice,
I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,I/Babel   ( 6450): connection state changed from DISCONNECTED to CONNECTED
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/GCM     ( 1667): Connected
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1667): Message class com.google.f.a.a.p
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GCM     ( 1960): Message from null null
E/GCM     ( 1960): Dropping message from null
,I/SA      ( 6096): [RC New] Execute method=[GET] start
,I/SA      ( 6096): [RC New] Security=[true]
,I/System.out( 6096): Thread-1030(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6096): Thread-1030(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6096): Thread-1030(ApacheHTTPLog):isShipBuild true
I/System.out( 6096): Thread-1030(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6096): Thread-1030(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10036
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6393): BLE is supported
I/jxcore-log( 6393): 
,I/SA      ( 6096): [RC New] [v2liruge] api execute + 664
,I/SA      ( 6096): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6096): AsyncTask #1 calls detatch()
,I/SA      ( 6096): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6096): [OCP] update openData : PL
,I/SA      ( 6096): [TPMU] getNetworkMcc : 
,I/SA      ( 6096): [SCU] saveMccToPreferece Start
,I/SA      ( 6096): [SCU] RegionMCC : 260
,I/SA      ( 6096): [SSP] query invoked
,I/SA      ( 6096): [TPMU] GetMccFromDB : null
,I/SA      ( 6096): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6096): [SCU] saveMccToPreferece End
,I/SA      ( 6096): [RC New] executeRequest [v2liruge] end. 725
I/SA      ( 6096): [RC New] Execute end
,I/SA      ( 6096): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6096): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6522): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6522): wlan0: sendmsg: Cannot assign requested address
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 290,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
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
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 4896): callingUid 10011, callindPid: 4896
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6492): Conditions not met for autocaching. okToAttempt=false
,I/MusicLeanback( 6492): Stop autocaching.
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1174): CM callback handler got msg 524295
,E/GmsUtils( 6492): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6492): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5500): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5500): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5500): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  257): id=15 Removed Uoast (8/9),
I/SurfaceFlinger(  257): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 167972
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10049}) (elapsedTime=3495)
,E/Watchdog( 1018): !@Sync 5
,E/SMD     (  294): DCD OFF,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5914): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5914): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5914): [GetString-S]
,I/ReactiveServiceManager( 5914): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1018): handleString: Failed to handle string(-4)
,E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5914): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5914): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5914): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5914): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5914): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5914): [ensureRegistration] - No Samsung account
,I/dhcpcd  ( 6522): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService( 1018): [PWL] Off : 75s ago,
,E/SMD     (  294): DCD OFF
,I/dhcpcd  ( 6522): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6522): wlan0: no IPv6 Routers available
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6178): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6178): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6178): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6178): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 6178): RestApi Request Add : 2307
,E/File    ( 6178): fail readDirectory() errno=2
,I/System.out( 6178): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6178): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6178): (HTTPLog)-Static: isShipBuild true
I/System.out( 6178): (HTTPLog)-Thread-1046-399840559: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6178): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10009
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6178): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/System.out( 6178): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
I/qtaguid ( 6178): Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6178, getuid(): 10009
,I/qtaguid ( 6178): Untagging socket 26
,D/hcjo    ( 6178): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6178): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6178): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6178): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6178): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6178): RestApi Request Add : 2315
,I/System.out( 6178): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 6178): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 6178): Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 6178, getuid(): 10009
,E/SMD     (  294): DCD OFF
,I/qtaguid ( 6178): Untagging socket -1,
I/qtaguid ( 6178): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6178): Untagging socket -1 failed errno=-9
W/NetworkManagementSocketTagger( 6178): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6178): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 6178): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6178): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6178): exit::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6178): entry::FINISH
,D/PreloadUpdateManagerStateMachine( 6178): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 6178): entry::IDLE
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 41645(2MB) AllocSpace objects, 15(244KB) LOS objects, 33% free, 23MB/35MB, paused 2.470ms total 152.776ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5500): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5500): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5500): [1] 5.onFinished: Giving up after 6 failures.
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1018): [PWL] Off : 140s ago,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
,D/SecKeyguardClockView( 1174): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false,
D/SecKeyguardClockView( 1174): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1174): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1174): *** don't update sliding image ***
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/BooksSync( 6287): Starting books sync for 61035162, extras: ade
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksConfig( 6287): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
,D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6287): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6287): Soft error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6287): Sync error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6287): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 275029, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
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
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/PowerManagerService( 1018): [PWL] Off : 225s ago
,E/SMD     (  294): DCD OFF
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
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
,D/SViewCoverWidget( 1174): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167],
,D/SecKeyguardStatusUtils( 1174): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/BooksSync( 6287): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6287): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6287): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6287): Soft error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6287): Sync error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6287): Finished books sync
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307666, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/jxcore-log( 6393): Connected to the server!
I/jxcore-log( 6393): 
,I/chromium( 6393): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 11,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  294): DCD OFF
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 32029(1849KB) AllocSpace objects, 20(755KB) LOS objects, 39% free, 7MB/12MB, paused 1.486ms total 62.906ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
W/GLSActivity( 1667): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1667): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1667): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1667): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1667): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1667): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1667): 	at android.os.Binder.execTransact(Binder.java:461)
,I/PhoneStatusBar( 1174): Icon Only
I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,E/PlayEventLogger( 5500): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5500): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5500): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 5500): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5500): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 5500): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5500): 	at android.os.Binder.execTransact(Binder.java:461)
,W/System  ( 5500): Ignoring header User-Agent because its value was null.
,I/System.out( 5500): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5500): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5500): (HTTPLog)-Static: isShipBuild true
I/System.out( 5500): (HTTPLog)-Thread-913-1063247397: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5500): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10026
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/System.out( 5500): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  294): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 275s ago
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/Watchdog( 1018): !@Sync 12
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :4,
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
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
,I/BooksSync( 6287): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6287): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/SMD     (  294): DCD OFF
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6287): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6287): Soft error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6287): Sync error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6287): Finished books sync
D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 400204, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 13
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5,
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 330s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :4
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 14
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,E/SMD     (  294): DCD OFF
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6393): --- start :testFindPeers.js---
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): testFindPeers created [object Object]
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): serverPort is 8876
I/jxcore-log( 6393): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): setDiscoveryMode: Mode set to WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6393): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6393): initialize: My bluetooth address is 08:EC:A9:50:75:41
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6393): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6393): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6393): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 6393): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothSocket( 6393): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
,D/BluetoothSocket( 6393): bindListen(), new LocalSocket 
D/BluetoothSocket( 6393): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 6393): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37866864
D/BluetoothSocket( 6393): channel: 6,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): start: OK
I/io.jxcore.node.ConnectionHelper( 6393): start: Using peer discovery mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): start: Peer ID: 08:EC:A9:50:75:41, peer name: A3-1
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 6393): verifyIdentityString: Identity string created: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6393): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6393): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): start: {"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6393): start: Identity string: "{"pi":"08:EC:A9:50:75:41","pn":"A3-1","ra":"08:EC:A9:50:75:41"}", service type: "Cordovap2p._tcp"
,D/WifiP2pService( 1018): InactiveState{ what=139292 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139292 }
,D/WifiP2pService( 1018): P2pEnabledState add service
,D/WifiP2pService( 1018): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): start: Starting P2P device discovery...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 6393): start: OK
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/jxcore-log( 6393): StartBroadcasting started ok
I/jxcore-log( 6393): 
D/WifiP2pService( 1018): discovery change broadcast true
I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
I/chromium( 6393): [INFO:CONSOLE(63)] "logCallback --- start :testFindPeers.js---", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6393): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6393): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 6393): onDiscoveryManagerStateChanged: RUNNING
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 44.5A.07 p2p_dev_addr=44.5A.07 pri_dev_type=10-0050F204-5  '23d5' config_methods=0x188 dev_capab=0x21 group_capab=0x0 vendor_elems=1 freq=2437
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 3 device(s) discovered,
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 3 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 3 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState add service request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pManager( 6393): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service request added successfully
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 },
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 7 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 7 device(s) discovered,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 7 device(s) discovered
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 7 device(s) discovered
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true,
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service discovery started successfully
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 7E.96.AC p2p_dev_addr=7E.96.AC pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 7 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 1,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 15
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 2,
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/bootchecker(  324): bootchecker wake up!!
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/PowerManagerService( 1018): [PWL] Off : 390s ago
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 3
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService( 1018): Plugged
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: RESTARTING
,D/WifiP2pService( 1018): InactiveState{ what=139268 },
,I/wpa_supplicant( 1394): P2P-FIND-STOPPED 
D/WifiP2pService( 1018): InactiveState{ what=147493 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
,D/WifiP2pService( 1018): discovery change broadcast true
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: STARTED
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started,
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
D/WifiP2pService( 1018): InactiveState{ what=147477 }
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 8 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 8 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState add service request
,D/WifiP2pManager( 6393): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service request added successfully
,E/SMD     (  294): DCD OFF,
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad,
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=139310 },
D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service discovery started successfully,
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 16
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiP2pService( 1018): InactiveState{ what=139283 },
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:37:96:AB","pn":"A5-1","ra":"7C:F9:0E:37:96:AB"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [7C:F9:0E:37:96:AB A5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:37:96:AB A5-1]
,I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [7C:F9:0E:37:96:AB A5-1], Bluetooth address: 7C:F9:0E:37:96:AB, device name: A5-1, device address: 7e:f9:0e:37:96:ac
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [7C:F9:0E:37:96:AB A5-1] is available
,I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"A5-1","peerAvailable":true}]
I/jxcore-log( 6393): 
I/jxcore-log( 6393): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6393): 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF,
,I/ServiceManager(  329): Waiting for service AtCmdFwd...,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF,
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 17
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): Got discovery timeout, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: RESTARTING
,D/WifiP2pService( 1018): InactiveState{ what=139268 }
,I/wpa_supplicant( 1394): P2P-FIND-STOPPED 
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
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
,I/BooksSync( 6287): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6287): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1174): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
D/PersonaManager( 1174): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1174): Icon Only
,I/StatusBar( 1174): Icon Only
D/PanelView( 1174): There is/are notification(s) 
D/PanelView( 1174): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1174): isKioskContainerExistOnDevice
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
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/GLSUser ( 1667): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1667): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1667): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1667): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1667): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1174): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 62918(5MB) AllocSpace objects, 145(2MB) LOS objects, 33% free, 24MB/36MB, paused 2.464ms total 165.177ms
,E/BooksAccountManager( 6287): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6287): Soft error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6287): Sync error
E/BooksSync( 6287): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6287): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6287): Finished books sync
,D/SyncManager( 1018): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 530038, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,I/ServiceManager(  329): Waiting for service AtCmdFwd...
,E/SMD     (  294): DCD OFF
,W/Atfwd_Sendcmd(  329): AtCmdFwd service not published, waiting... retryCnt : 5
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): Start timer timeout, starting now...
,D/WifiP2pService( 1018): InactiveState{ what=139265 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139265 }
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): P2P device discovery started successfully,
D/WifiP2pService( 1018): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): restart: Restarting...
,D/WifiP2pService( 1018): InactiveState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/WifiP2pService( 1018): InactiveState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState add service request
,D/WifiP2pManager( 6393): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service request added successfully
,E/SMD     (  294): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
,D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
I/wpa_supplicant( 1394): p2p0: P2P: Reject scan trigger since one is already pending
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service discovery started successfully
,I/wpa_supplicant( 1394): p2p0: P2P: Reject scan trigger since one is already pending,
I/wpa_supplicant( 1394): [wpa_supplicant_ctrl_retry_p2p_find]: p2p_find ret=0 timeout=0 
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 9 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: A5-1 7e:f9:0e:37:96:ac
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_8ae2 52:55:27:f0:fd:0b
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 10 device(s) discovered,
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c,
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 10 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): DefaultState{ what=139283 }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"7C:F9:0E:34:8A:A0","pn":"S5-1","ra":"7C:F9:0E:34:8A:A0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [7C:F9:0E:34:8A:A0 S5-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [7C:F9:0E:34:8A:A0 S5-1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: S5-1, device address: ee:1f:72:63:11:86
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [7C:F9:0E:34:8A:A0 S5-1] is available
,I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"S5-1","peerAvailable":true}]
I/jxcore-log( 6393): 
I/jxcore-log( 6393): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6393): 
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
,D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [F8:95:C7:87:85:54 G3s-1] is available
I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"G3s-1","peerAvailable":true}]
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 6393): 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 92.4C.F8 p2p_dev_addr=92.4C.F8 pri_dev_type=10-0050F204-5  '608e' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462,
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 10 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_8ae2 52:55:27:f0:fd:0b
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10,
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 52.FD.0B p2p_dev_addr=52.FD.0B pri_dev_type=10-0050F204-5  '8ae2' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 11 device(s) discovered
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:34:8A:A0 S5-1], add/update: true
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:34:8A:A0 S5-1]
,D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [7C:F9:0E:37:96:AB A5-1], add/update: true
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [7C:F9:0E:37:96:AB A5-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 11 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:3C:51 G4-1]
,I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [F8:95:C7:87:3C:51 G4-1] is available
,I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"G4-1","peerAvailable":true}]
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 6393): 
,E/SMD     (  294): DCD OFF
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 },
,D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 11 device(s) discovered
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:85:54 G3s-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.,
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.,
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 11 device(s) discovered
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  294): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.,
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND EE.8B.78 p2p_dev_addr=EE.8B.78 pri_dev_type=10-0050F204-5  ' S5)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
,D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): restart: Restarting...
,D/WifiP2pService( 1018): InactiveState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/WifiP2pService( 1018): InactiveState{ what=139301 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
D/WifiP2pService( 1018): P2pEnabledState add service request
,D/WifiP2pManager( 6393): Ignored { when=-1ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service request added successfully
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service discovery started successfully
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-1  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437,
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.C9.5D p2p_dev_addr=A2.C9.5D pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2437
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJ,et 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"E0:DB:10:14:E2:C0","pn":"Note4-1","ra":"E0:DB:10:14:E2:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [E0:DB:10:14:E2:C0 Note4-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [E0:DB:10:14:E2:C0 Note4-1], Bluetooth address: E0:DB:10:14:E2:C0, device name: Note4-1, device address: 92:b6:86:43:73:1c
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [E0:DB:10:14:E2:C0 Note4-1] is available
I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"Note4-1","peerAvailable":true}]
I/jxcore-log( 6393): 
I/jxcore-log( 6393): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 6393): 
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local.",
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] is available
I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"Thali Test (Galaxy A3)","peerAvailable":true}]
I/jxcore-log( 6393): 
I/jxcore-log( 6393): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6393): 
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:3C:51","pn":"G4-1","ra":"F8:95:C7:87:3C:51"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:3C:51 G4-1]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [F8:95:C7:87:3C:51 G4-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [F8:95:C7:87:3C:51 G4-1], Bluetooth address: F8:95:C7:87:3C:51, device name: G4-1, device address: a2:39:f7:6f:c9:5d
W/io.jxcore.node.ConnectionHelper( 6393): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:3C:51 G4-1] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
,I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [58:3F:54:73:64:C0 G3-1] is available
,I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"G3-1","peerAvailable":true}]
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6393): 
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"B0:C5:59:3F:75:69","pn":"Thali Test (Galaxy S5)","ra":"B0:C5:59:3F:75:69"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], Bluetooth address: B0:C5:59:3F:75:69, device name: Thali Test (Galaxy S5), device address: ee:1f:72:18:8b:78
D/io.jxcore.node.ConnectionHelper( 6393): notifyPeerAvailability: Peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)] is available
,I/jxcore-log( 6393): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"Thali Test (Galaxy S5)","peerAvailable":true}]
I/jxcore-log( 6393): 
I/jxcore-log( 6393): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 6393): 
,E/SMD     (  294): DCD OFF
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07,
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [E0:DB:10:14:E2:C0 Note4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [E0:DB:10:14:E2:C0 Note4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80,
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:3C:51 G4-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [F8:95:C7:87:3C:51 G4-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/PowerManagerService( 1018): [PWL] Off : 455s ago
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 02.60.AC p2p_dev_addr=02.60.AC pri_dev_type=10-0050F204-5  '' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 },
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.,
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null,
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  294): DCD OFF
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND EE.11.86 p2p_dev_addr=EE.11.86 pri_dev_type=10-0050F204-5  '' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412,
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 },
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=139283 },
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.,
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6393): timeout now
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): weAreDoneNow
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): done, now sending data to server
I/jxcore-log( 6393): 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 18,
,I/Atfwd_Sendcmd(  329): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  329): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged,
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8,
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1174): handleTimeUpdate
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
,E/SMD     (  294): DCD OFF,
,D/WifiP2pService( 1018): InactiveState{ what=147477 },
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 92.73.1C p2p_dev_addr=92.73.1C pri_dev_type=10-0050F204-5  'e4-1' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-1, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
,D/WifiP2pService( 1018): DefaultState{ what=139283 },
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiP2pService( 1018): InactiveState{ what=139307 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): P2pEnabledState{ what=139307 },
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): InactiveState{ what=139301 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiP2pService( 1018): P2pEnabledState{ what=139301 }
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiP2pService( 1018): P2pEnabledState add service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): restart: Restarting...
D/WifiP2pManager( 6393): Ignored { when=0 what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service request added successfully
,D/WifiP2pService( 1018): InactiveState{ what=139310 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139310 }
D/WifiP2pService( 1018): P2pEnabledState discover services
,D/WifiStateMachine( 1018): WifiManager.SEC_COMMAND_ID_SET_WIFI_ENABLED_WITH_P2P mSkipScanAssoc : true
D/WifiService( 1018): SEC_COMMAND_ID_SET_WIFI_SCAN_WITH_P2P : WiFi scan with p2p -> Stop Scan, Stop Assoc
D/WifiStateMachine( 1018): WifiNative.WIFI_NATIVE_CMD_SET_ESTABLISH_SUP_CONNECTION mSkipScanAssoc : true
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [13]
I/wpa_supplicant( 1394): USE_NETWORK : USE_NETWORK OFF
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service discovery started successfully
,I/wpa_supplicant( 1394): P2P-DEVICE-FOUND DC.C2.F1 p2p_dev_addr=DE.89.AD pri_dev_type=3-0050F204-5  'ries' config_methods=0x5a88 dev_capab=0x4 group_capab=0x1 vendor_elems=1 freq=2437
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND 0A.76.28 p2p_dev_addr=0A.76.28 pri_dev_type=10-0050F204-5  ' A3)' config_methods=0x188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2412
I/wpa_supplicant( 1394): P2P-DEVICE-FOUND A2.12.80 p2p_dev_addr=A2.12.80 pri_dev_type=10-0050F204-5  '3s-1' config_methods=0x1188 dev_capab=0x25 group_capab=0x0 vendor_elems=1 freq=2462
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
,D/WifiP2pService( 1018): InactiveState{ what=147477 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147477 }
,D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received list of peers.
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiDisplayController( 1018): Received WIFI_P2P_PEERS_CHANGED_ACTION.
D/WifiP2pService( 1018): InactiveState{ what=139283 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/WifiP2pService( 1018): DefaultState{ what=139283 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018): Received list of peers.
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab:, 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiP2pService( 1018): InactiveState{ what=139283 }
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/WifiDisplayController( 1018): Received list of peers.
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/WifiP2pService( 1018): P2pEnabledState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/WifiDisplayController( 1018):   Device: DIRECT-AD-HP DeskJet 3630 series, deviceAddress: de:4a:3e:0f:89:ad, primary type: 3-0050F204-5, secondary type: null, wps: 23176, grpcapab: 1, devcapab: 4, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
D/WifiDisplayController( 1018):   Device: XT1072_23d5, deviceAddress: 44:80:eb:7b:5a:07, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 33, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/WifiDisplayController( 1018):   Device: S5-1, deviceAddress: ee:1f:72:63:11:86, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
,D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy A3), deviceAddress: 0a:ec:a9:50:76:28, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/WifiP2pService( 1018): DefaultState{ what=139283 }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/WifiDisplayController( 1018):   Device: Note4-1, deviceAddress: 92:b6:86:43:73:1c, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/WifiDisplayController( 1018):   Device: A5-1, deviceAddress: 7e:f9:0e:37:96:ac, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/WifiDisplayController( 1018):   Device: G3s-1, deviceAddress: a2:39:f7:70:12:80, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
D/WifiDisplayController( 1018):   Device: G4-1, deviceAddress: a2:39:f7:6f:c9:5d, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
,D/WifiDisplayController( 1018):   Device: Android_608e, deviceAddress: 92:e7:c4:e6:4c:f8, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/WifiDisplayController( 1018):   Device: G3-1, deviceAddress: 02:9a:02:7b:60:ac, primary type: 10-0050F204-5, secondary type: null, wps: 4488, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
D/WifiDisplayController( 1018):   Device: Thali Test (Galaxy S5), deviceAddress: ee:1f:72:18:8b:78, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onP2pDeviceListChanged: 12 device(s) discovered
D/WifiDisplayController( 1018):   Device: Android_8ae2, deviceAddress: 52:55:27:f0:fd:0b, primary type: 10-0050F204-5, secondary type: null, wps: 392, grpcapab: 0, devcapab: 37, status: 3, wfdInfo: null, groupownerAddress: null, GOdeviceName: null, interfaceAddress: , SConnectInfo : null
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 1: S5-1 ee:1f:72:63:11:86
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 2: XT1072_23d5 44:80:eb:7b:5a:07
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 3: DIRECT-AD-HP DeskJet 3630 series de:4a:3e:0f:89:ad
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 4: A5-1 7e:f9:0e:37:96:ac
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 5: Note4-1 92:b6:86:43:73:1c
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 6: Thali Test (Galaxy A3) 0a:ec:a9:50:76:28
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 7: G3s-1 a2:39:f7:70:12:80
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 8: G4-1 a2:39:f7:6f:c9:5d
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 9: G3-1 02:9a:02:7b:60:ac
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 10: Android_608e 92:e7:c4:e6:4c:f8
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 11: Thali Test (Galaxy S5) ee:1f:72:18:8b:78
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Updating the timestamp of peer [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onP2pDeviceListChanged: Peer 12: Android_8ae2 52:55:27:f0:fd:0b
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"F8:95:C7:87:85:54","pn":"G3s-1","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp.local.",
D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [F8:95:C7:87:85:54 G3s-1]
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [F8:95:C7:87:85:54 G3s-1]
,D/WifiP2pService( 1018): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [F8:95:C7:87:85:54 G3s-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [F8:95:C7:87:85:54 G3s-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [F8:95:C7:87:85:54 G3s-1], Bluetooth address: F8:95:C7:87:85:54, device name: G3s-1, device address: a2:39:f7:70:12:80
W/io.jxcore.node.ConnectionHelper( 6393): modifyListOfDiscoveredPeers: Peer [F8:95:C7:87:85:54 G3s-1] already in the list, will not add again
,E/SMD     (  294): DCD OFF
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"08:EC:A9:50:76:27","pn":"Thali Test (Galaxy A3)","ra":"08:EC:A9:50:76:27"}", service type: "Cordovap2p._tcp.local."
D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
D/WifiP2pService( 1018): P2pEnabledState receive service response
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [08:EC:A9:50:76:27 Thali Test (Galaxy A3)], Bluetooth address: 08:EC:A9:50:76:27, device name: Thali Test (Galaxy A3), device address: 0a:ec:a9:50:76:28
W/io.jxcore.node.ConnectionHelper( 6393): modifyListOfDiscoveredPeers: Peer [08:EC:A9:50:76:27 Thali Test (Galaxy A3)] already in the list, will not add again
,D/WifiP2pService( 1018): InactiveState{ what=147494 }
D/WifiP2pService( 1018): P2pEnabledState{ what=147494 }
,D/WifiP2pService( 1018): P2pEnabledState receive service response
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Identity: "{"pi":"58:3F:54:73:64:C0","pn":"G3-1","ra":"58:3F:54:73:64:C0"}", service type: "Cordovap2p._tcp.local."
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): onDnsSdServiceAvailable: Resolved peer properties: [58:3F:54:73:64:C0 G3-1]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): onServiceDiscovered: [58:3F:54:73:64:C0 G3-1]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1]
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: [58:3F:54:73:64:C0 G3-1], add/update: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): modifyListOfDiscoveredPeers: Adding new peer: [58:3F:54:73:64:C0 G3-1]
I/io.jxcore.node.ConnectionHelper( 6393): onPeerDiscovered: [58:3F:54:73:64:C0 G3-1], Bluetooth address: 58:3F:54:73:64:C0, device name: G3-1, device address: 02:9a:02:7b:60:ac
W/io.jxcore.node.ConnectionHelper( 6393): modifyListOfDiscoveredPeers: Peer [58:3F:54:73:64:C0 G3-1] already in the list, will not add again
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 6393): teardown
I/jxcore-log( 6393): 
,I/jxcore-log( 6393): testFindPeers stopped
I/jxcore-log( 6393): 
,I/io.jxcore.node.ConnectionHelper( 6393): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6393): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6393): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6393): shutdown
,D/BluetoothSocket( 6393): close() in, this: android.bluetooth.BluetoothSocket@1e73a6d0, channel: 6, state: LISTENING
D/BluetoothSocket( 6393): close() this: android.bluetooth.BluetoothSocket@1e73a6d0, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37866864, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@8f196c9mSocket: android.net.LocalSocket@1344a1ce impl:android.net.LocalSocketImpl@10d9d8ef fd:FileDescriptor[109]
,D/BluetoothSocket( 6393): Closing mSocket: android.net.LocalSocket@1344a1ce impl:android.net.LocalSocketImpl@10d9d8ef fd:FileDescriptor[109]
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6393): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 6393): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): stop: Stopping peer discovery...
D/WifiP2pService( 1018): InactiveState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 6393): stop: Stopping services
D/WifiP2pService( 1018): P2pEnabledState{ what=139298 }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): stop: Stopping P2P device discovery...
D/WifiP2pService( 1018): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): setState: NOT_INITIALIZED,
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 6393): release: No more listeners, de-initializing...
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6393): release: The given listener does not exist in the list
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6393): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6393): setState: NOT_STARTED
I/jxcore-log( 6393): StopBroadcasting went ok,
I/jxcore-log( 6393): 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 6393): Exiting thread
D/WifiP2pService( 1018): InactiveState{ what=139268 }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 6393): onServerStopped
I/chromium( 6393): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
I/io.jxcore.node.ConnectionHelper( 6393): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 6393): onDiscoveryManagerStateChanged: NOT_STARTED
I/wpa_supplicant( 1394): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 6393): Local services cleared successfully
,D/WifiP2pService( 1018): InactiveState{ what=139307 }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 6393): P2P device discovery stopped successfully
,D/WifiP2pService( 1018): P2pEnabledState{ what=139307 }
,D/WifiP2pService( 1018): P2pEnabledState clear service request
,D/WifiP2pService( 1018): remove channel information from framework
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 6393): Service requests cleared successfully
,D/WifiP2pService( 1018): InactiveState{ what=147493 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147493 }
,D/WifiP2pService( 1018): discovery change broadcast false
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,I/jxcore-log( 6393): teardown
I/jxcore-log( 6393): 
,E/jxcore  ( 6393): Error!: self.currentTest is null,
E/jxcore  ( 6393): Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js","_functionName":"TestFrameworkClient/<","_lineNumber":"169","_columnNumber":"5","_msg":"    at TestFrameworkClient/<@/data/data/com.test.thalitest/files/www/jxcore/perf_tests/PerfTestFrameworkClient.js:169:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onevent","_lineNumber":"263","_columnNumber":"5","_msg":"    at Socket.prototype.onevent@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.onpacket","_lineNumber":"221","_columnNumber":"7","_msg":"    at Socket.prototype.onpacket@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.ondecoded","_lineNumber":"333","_columnNumber":"3","_msg":"    at Manager.prototype.ondecoded@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:333:3"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js","_functionName":"module.exports/<","_lineNumber":"21","_columnNumber":"12","_msg":"    at module.exports/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/component-bind/index.js:21:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/node_modules/socket.io-parser/node_modules/component-emitter/index.js:134:7"}]
,I/chromium( 6393): [INFO:CONSOLE(63)] "logCallback teardown", source: file:///android_asset/www/js/thali_main.js (63)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,I/Atfwd_Daemon(  329): Stop the daemon....
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 19
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 20
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,E/SMD     (  294): DCD OFF
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1174): level :100 plugged : 2
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/PowerManagerService( 1018): [PWL] Off : 525s ago,
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1174): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1174): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2662): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2662): Disconnected process message: 10
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1174): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1174): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,D/SViewCoverView( 1174): level :100 plugged : 2
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/Watchdog( 1018): !@Sync 21
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  294): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF
,E/SMD     (  294): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,E/SMD     (  294): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  294): DCD OFF

```
