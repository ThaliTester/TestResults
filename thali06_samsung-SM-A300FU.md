#### Test 549702610b97681_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
D/SSRM:n  ( 1022): SIOP:: AP = 260
,--------- beginning of main
D/AndroidRuntime( 6173): 
D/AndroidRuntime( 6173): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6173): CheckJNI is OFF
D/AndroidRuntime( 6173): readGMSProperty: start
D/AndroidRuntime( 6173): readGMSProperty: already setted!!
D/AndroidRuntime( 6173): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6173): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6173): readGMSProperty: end
D/AndroidRuntime( 6173): addProductProperty: start
E/AffinityControl( 6173): AffinityControl: registerfunction enter
D/AndroidRuntime( 6173): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1022): inState():  stateMachine is null !!
I/PersonaManagerService( 1022): PersonaId don't exist
I/ActivityManager( 1022): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/ActivityManager( 1022): mDVFSHelper.acquire()
D/FocusedStackFrame( 1022): Set to : 0
D/PhoneWindow( 1022): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1022): *FMB* installDecor flags : 25362712
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6185): MountEmulatedStorage()
E/Zygote  ( 6185): v2
I/libpersona( 6185): KNOX_SDCARD checking this for 10338
I/libpersona( 6185): KNOX_SDCARD not a persona
I/SELinux ( 6185): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1022): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1022): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6185 uid=10338 gids={50338, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 6185): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6185): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1022): Focused application set to: xxxx
D/InputDispatcher( 1022): Focus left window: 1484
D/AndroidRuntime( 6173): Shutting down VM
D/TimaKeyStoreProvider( 6185): TimaSignature is unavailable
D/ActivityThread( 6185): Added TimaKeyStore provider
V/WindowManager( 1022): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
D/StatusBarManagerService( 1022): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1022): isKioskContainerExistOnDevice
D/WindowOrientationListener( 1022):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
I/SurfaceFlinger(  259): id=9 Removed Mauncher (5/9)
I/SurfaceFlinger(  259): id=9 Removed Mauncher (-2/9)
V/ActivityThread( 1484): updateVisibility : ActivityRecord{3a5119f0 token=android.os.BinderProxy@3f0e11ce {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1484): onTrimMemory. Level: 20
I/WebViewFactory( 6185): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
I/LibraryLoader( 6185): Time to load native libraries: 1 ms (timestamps 3645-3646)
I/LibraryLoader( 6185): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6185): Binding Chromium to main looper Looper (main, tid 1) {3a0f81b6}
I/LibraryLoader( 6185): Expected native library version number "",actual native library version number ""
I/chromium( 6185): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/art     ( 6173): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/BrowserStartupController( 6185): Initializing chromium process, singleProcess=true
,W/art     ( 6185): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6185): ApplicationContext is null in ApplicationStatus
,W/chromium( 6185): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6185): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6185): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6185): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6185): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6185): Local Branch: 
I/Adreno-EGL( 6185): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6185): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6185):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/art     ( 6185): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6185): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6185): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6185): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6185): CordovaWebView is running on device made by: samsung
,W/art     ( 6185): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6185): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1022): Activity pause timeout for ActivityRecord{f22ca32 u0 com.test.thalitest/.MainActivity t20}
,D/OpenGLRenderer( 6185): Render dirty regions requested: true
,D/ActivityManager( 1022): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/PersonaManagerService( 1022): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1022): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1022): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1022): handleActiveUserChange for user 0
,W/chromium( 6185): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/ActivityThread( 6185): updateVisibility : ActivityRecord{f711343 token=android.os.BinderProxy@2784ebfd {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6185): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 6185): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  259): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1022): Focus entered window: 6185
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6185): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6185): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6185): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6185): Enabling debug mode 0
,D/InputMethodManagerService( 1022): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
,I/ActivityManager( 1022): Displayed Component not be shown by security: +748ms (total +38s659ms)
,W/ActivityManager( 1022): mDVFSHelper.release()
,I/Timeline( 1022): Timeline: Activity_windows_visible id: ActivityRecord{f22ca32 u0 com.test.thalitest/.MainActivity t20} time:154243
,I/SurfaceFlinger(  259): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  259): id=12 Removed uhalitest (-2/9)
,I/SamsungIME( 1869): getCurrentCandidateView
,W/IInputConnectionWrapper( 6185): showStatusIcon on inactive InputConnection
,I/Timeline( 6185): Timeline: Activity_idle id: android.os.BinderProxy@2784ebfd time:154256
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SamsungIME( 1869): Dismiss ExpandCandiate
,E/SMD     (  290): DCD OFF,
,W/BindingManager( 6185): Cannot call determinedVisibility() - never saw a connection for the pid: 6185
,I/SamsungIME( 1869): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1869): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1869): KeybaordView init() : load resources
,I/SamsungIME( 1869): getCurrentKeyboard
,I/SamsungIME( 1869): getTextKeyboard
,D/SamsungIME( 1869): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/JsMessageQueue( 6185): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6185): JniHelper::setJavaVM(0xb7863448), pthread_self() = -1210352816
,D/JX-Cordova( 6185): jxcore cordova android initializing
,W/jxcore-log( 6185): Initializing JXcore engine
W/jxcore-log( 6185): JXcore engine is ready
,W/jxcore-log( 6185): Starting JXcore engine
,E/audit   ( 1921): type=1400 msg=audit(1452294351.721:205): avc:  denied  { ioctl } for  pid=6185 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1921):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1921): type=1300 msg=audit(1452294351.721:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=be8d8d58 items=0 ppid=313 ppcomm=main pid=6185 auid=4294967295 uid=10338 gid=10338 euid=10338 suid=10338 fsuid=10338 egid=10338 sgid=10338 fsgid=10338 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1921): type=1320 msg=audit(1452294351.721:205): 
,W/jxcore-log( 6185): Platform android
W/jxcore-log( 6185): 
W/jxcore-log( 6185): Process ARCH arm
W/jxcore-log( 6185): 
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/jxcore-log( 6185): JXcore Cordova bridge is ready!
I/jxcore-log( 6185): 
,W/jxcore-log( 6185): JXcore engine is started
,I/Choreographer( 6185): Skipped 128 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6185): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6185): Toggling radios to true
I/jxcore-log( 6185): 
,D/BluetoothAdapter( 6185): enable()
,D/BluetoothAdapter( 6185): enable(): BT is already enabled..!
,D/SecContentProvider( 1022): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1022): uri = 20 selection = isWifiStateChangeAllowed
,D/SecContentProvider2( 1022): mCursor = null
,D/WifiService( 1022): setWifiEnabled: true pid=6185, uid=10338
,W/ActivityManager( 1022): Permission Denial: getCurrentUser() from pid=6185, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1022): Failed getting userId using ActivityManagerNative
W/WifiService( 1022): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6185, uid=10338 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1022): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24603)
W/WifiService( 1022): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1022): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1022): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1022): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1022): name = wifi_on
I/WifiService( 1022): disconnect: pid=6185, uid=10338
,I/wpa_supplicant( 1384): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6185): Radios toggled
I/jxcore-log( 6185): 
,I/jxcore-log( 6185): My device name is: samsung-SM-A300FU
I/jxcore-log( 6185): 
,I/wpa_supplicant( 1384): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 1384): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1384): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1384): Cmd 35605 not handled
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
E/WifiStateMachine( 1022): WifiStateMachine: Leaving Connected state
D/Tethering( 1022): InitialState.processMessage what=4
I/wpa_supplicant( 1384): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1384): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1384): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1384): First Scan Start
I/wpa_supplicant( 1384): Scan requested (ret=0) - scan timeout 30 seconds
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/Tethering( 1022): No numeric data
,D/Tethering( 1022): sendTetherStateChangedBroadcast 0, 0, 0,
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): clearTetheredNotification()
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
D/HotspotTile( 1178): updateTetherState():false, false
,V/NetworkStats( 1022): performPollLocked() took 4ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit,
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1022): do suspend true
,D/WifiP2pService( 1022): InactiveState{ what=143375 }
,D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
V/NativeCrypto( 1704): Read error: ssl=0xb7df6fe8: I/O error during system call, Connection timed out
E/ConnectivityService( 1022): updateNetworkInfo()
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1022): updateNetworkInfo()
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
,E/WifiStateMachine( 1022): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/wpa_supplicant( 1384): wlan0: Setting scan request: 0 sec 0 usec
,E/WifiNative-wlan0( 1022): do suspend true
,D/WifiP2pService( 1022): InactiveState{ what=143375 },
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7fab7c8
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1208306376)
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1208306376) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7fab7c8
,D/CommandListener(  280): Clearing all IP addresses on wlan0,
D/ConnectivityService( 1022): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1022): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/WIFI_P2P( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
D/ConnectivityService( 1022): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1022): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory( 1453): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1022): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/TelephonyNetworkFactory( 1453): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler },
D/Tethering( 1022): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1022): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit,
V/NetworkStats( 1022): updateIfacesLocked()
D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
D/WifiNetworkAgent( 1022): NetworkAgent: NetworkAgent channel lost
D/WIFI    ( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1022): mCursor = null
,V/NetworkStats( 1022): performPollLocked() took 22ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 50262(2MB) AllocSpace objects, 32(516KB) LOS objects, 33% free, 24MB/36MB, paused 3.460ms total 210.628ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,V/NativeCrypto( 1704): SSL shutdown failed: ssl=0xb7df6fe8: I/O error during system call, Broken pipe
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #8
,I/Hs20UtilService( 1664): Message received 5007
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1022): nai.networkMonitor.doQuit()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): doQuit - quitNow()
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #9
,I/Hs20UtilService( 1664): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1304): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1022): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6242 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/Zygote  ( 6242): MountEmulatedStorage()
I/libpersona( 6242): KNOX_SDCARD checking this for 10102
E/Zygote  ( 6242): v2
I/libpersona( 6242): KNOX_SDCARD not a persona
I/SELinux ( 6242): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6242): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6242): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/TimaKeyStoreProvider( 6242): TimaSignature is unavailable
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/ActivityThread( 6242): Added TimaKeyStore provider
D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,E/SMD     (  290): DCD OFF
D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ResourcesManager( 6242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,D/PhoneApp( 1453): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1453): FileWriteThread : threadType = 3
,I/Babel_SMS( 6242): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 6242): MmsConfig.loadMmsSettings
I/Babel_SMS( 6242): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel_SMS( 6242): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6242): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6242): MmsConfig.loadFromResources
,E/Babel_SMS( 6242): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6242): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  285): getCameraInfo: X
,W/QCamera2Factory(  285): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  285): getCameraInfo: X
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/art     ( 6242): Suspending all threads took: 5.095ms
,I/ApplicationPolicy( 1022): updateDataUsageMap
,D/GpsLocationProvider( 1022): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/Settings( 6242): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6242): startup - clean
,I/Babel   ( 6242): deleted: false for 0
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6242): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6242): Unsupported mime audio/evrc
,W/AudioCapabilities( 6242): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6242): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6242): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6242): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6242): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6242): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6242): Unsupported mime audio/evrc
,W/VideoCapabilities( 6242): Unsupported mime video/wvc1
,W/VideoCapabilities( 6242): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6242): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6242): Unsupported mime video/wvc1
,W/VideoCapabilities( 6242): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6242): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6242): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6242): Unsupported mime video/mp43,
,W/VideoCapabilities( 6242): Unsupported mime video/sorenson
,W/VideoCapabilities( 6242): Unsupported mime video/mp4v-esdp
,I/wpa_supplicant( 1384): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 1384): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1384): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1384): Trying to associate with  'G700'
I/wpa_supplicant( 1384): Re-associate with C0.AA.48
I/wpa_supplicant( 1384): wlan0: State: SCANNING -> ASSOCIATING,
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
D/WifiMonitor( 1022): didn't find BSSID Trying to associate with SSID 'NG700'
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1022): mCursor = null
,I/VideoCapabilities( 6242): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6242): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6242): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6242): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/wpa_supplicant( 1384): Cmd 35605 not handled
I/wpa_supplicant( 1384): wlan0: State: ASSOCIATING -> ASSOCIATED
W/VideoCapabilities( 6242): Unrecognized profile 2130706433 for video/avc
,I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1384): Associated with C0.AA.48
I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1384): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, false
D/Tethering( 1022): interfaceStatusChanged wlan0, false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/wpa_supplicant( 1384): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/vclib   ( 6242): onServiceConnected
,W/Babel   ( 6242): Attempted to change video mute state without an active call.
I/wpa_supplicant( 1384): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1384): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1384): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1384): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/ActivityManager( 1022): Killing 5620:com.wssyncmldm/1000 (adj 15): empty #31
I/wpa_supplicant( 1384): Blacklist: Clear (temp) 
I/wpa_supplicant( 1384): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, true
D/Tethering( 1022): interfaceStatusChanged wlan0, true
D/SecContentProvider2( 1022): mCursor = null
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/Tethering( 1022): interfaceLinkStateChanged wlan0, true
I/Nat464Xlat( 1022): interfaceLinkStateChanged wlan0, true
D/Tethering( 1022): interfaceStatusChanged wlan0, true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/Tethering( 1022): No numeric data
,D/Tethering( 1022): sendTetherStateChangedBroadcast 1, 0, 0
,D/Tethering( 1022): clearTetheredNotification()
,V/NetworkStats( 1022): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,D/HotspotTile( 1178): updateTetherState():false, false
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,V/NetworkStats( 1022): performPollLocked() took 7ms
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/WifiNative-wlan0( 1022): callSECApiVoid - ID [50]
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/PCWCLIENTTRACE_PushUtil( 5778): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5778): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5778): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5778): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/WifiConfigStore( 1022): setLastSelectedConfiguration -1
,D/ConnectivityService( 1022): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService( 1022): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1022): updateNetworkInfo()
D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5778): noConnectivity : true
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/splitIntent( 1022): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1022): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1022): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6286): MountEmulatedStorage()
I/ActivityManager( 1022): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6286 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/Zygote  ( 6286): v2
I/libpersona( 6286): KNOX_SDCARD checking this for 10108
I/libpersona( 6286): KNOX_SDCARD not a persona
,E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/SELinux ( 6286): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6286): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6286): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_5620/cgroup.procs: No such file or directory
,E/WifiConfigStore( 1022): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 6286): TimaSignature is unavailable
,D/ActivityThread( 6286): Added TimaKeyStore provider
,D/CommandListener(  280): Setting iface cfg
,E/WifiStateMachine( 1022): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1022): mCursor = null
,E/WifiNative-wlan0( 1022): do suspend false
,D/SecContentProvider2( 1022): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1022): mCursor = null
,D/WifiP2pService( 1022): InactiveState{ what=143375 }
,D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
,I/MusicStore( 6286): Database version: 120
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/ResourcesManager( 6286): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6286): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6286): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...,
,E/dhcpcd  ( 6308): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6308): version 5.5.6 starting,
,E/dhcpcd  ( 6308): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6308): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6308): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6308): bssid match,
W/ActivityThread( 6286): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6286): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f17434f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6286): Installed default security provider GmsCore_OpenSSL,
D/AndroidMusic( 6286): GMSCore installation verified
I/dhcpcd  ( 6308): wlan0: rebinding lease of 192.168.1.132
,I/ConfigStore( 6286): Config Database version: 1
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1022): getStreamVolume 3 index 70
,I/MediaRouter( 6286): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6286): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1022): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6319): MountEmulatedStorage(),
E/Zygote  ( 6319): v2
I/libpersona( 6319): KNOX_SDCARD checking this for 10001
I/libpersona( 6319): KNOX_SDCARD not a persona
,I/SELinux ( 6319): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6319): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1022): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6319 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,E/SELinux ( 6319): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,I/GHttpClientFactory( 6286): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,D/TimaKeyStoreProvider( 6319): TimaSignature is unavailable
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityThread( 6319): Added TimaKeyStore provider
,I/GoogleURLConnFactory( 6286): Using platform SSLCertificateSocketFactory
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,V/AlarmManager( 1022): waitForAlarm result :4
,I/ActivityManager( 1022): Killing 5643:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,I/dhcpcd  ( 6308): wlan0: acknowledged 192.168.1.132 from 192.168.1.1
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6338): MountEmulatedStorage(),
I/libpersona( 6338): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD not a persona
I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1022): Killing 4594:com.sec.spp.push/u0a32 (adj 15): empty #31
E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/dhcpcd  ( 6308): wlan0: leased 192.168.1.132 for 86400 seconds
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable,
D/ActivityThread( 6338): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_10139/pid_5643/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_4594/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 6338): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] ,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/WifiNative-wlan0( 1022): do suspend true
,I/DIAGMON_AGENT( 6338): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,D/WifiP2pService( 1022): InactiveState{ what=143375 },
D/WifiP2pService( 1022): P2pEnabledState{ what=143375 }
,I/DIAGMON_AGENT( 6338): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
E/WifiStateMachine( 1022): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1022): VerifyingLinkState enter
,I/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6338): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,D/WifiNative-wlan0( 1022): callSECApiInt - ID [210]
,E/ConnectivityService( 1022): updateNetworkInfo()
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1022): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1022): Adding iface wlan0 to network 503
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6375): MountEmulatedStorage()
,E/Zygote  ( 6375): v2
I/libpersona( 6375): KNOX_SDCARD checking this for 10008
I/libpersona( 6375): KNOX_SDCARD not a persona
,I/SELinux ( 6375): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6375): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6375): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1022): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6375 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1022): Killing 5287:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,D/WifiWatchdogStateMachine( 1022): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1022): Adding Route [fe80::/64 -> :: wlan0] to network 503
D/WifiWatchdogStateMachine.DnsResolver( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1022): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1022): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1022): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/ConnectivityService( 1022): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1022): Setting Dns servers for network 503 to [/192.168.1.1]
D/ConnectivityService( 1022): LTETest block dns file not exists
,D/ConnectivityService( 1022): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1022): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/TimaKeyStoreProvider( 6375): TimaSignature is unavailable
E/ConnectivityService( 1022): updateNetworkInfo()
,D/ActivityThread( 6375): Added TimaKeyStore provider
,E/ConnectivityService( 1022): updateNetworkInfo()
,D/ConnectivityService( 1022): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1022): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Connected
D/ConnectivityService( 1022): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
D/ConnectivityService( 1022):    accepting network in place of null
D/WIFI_P2P( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1453): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,I/System.out( 1022): (HTTPLog)-Static: isSBSettingEnabled false,
,D/CSLegacyTypeTracker( 1022): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
E/CSLegacyTypeTracker( 1022): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 1000
,D/TelephonyNetworkFactory( 1453): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1022): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1022): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/ConnectivityService( 1022): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,I/WifiTrafficPoller( 1022): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1022): mBoosterFLAG : 0
I/WifiTrafficPoller( 1022): current booster mode : FullMode
D/WifiNative-wlan0( 1022): callSECApiVoid - ID [212]
,D/EntConnectivity( 1022): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1022): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1022): MasterInitialState.processMessage what=3
,V/NetworkStats( 1022): updateIfacesLocked()
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
V/NetworkStats( 1022): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1022): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1022): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,V/NetworkStats( 1022): performPollLocked() took 8ms
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,V/NetworkStats( 1022): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
D/NtpTrustedTime( 1022): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
,D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/System.out( 1022): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/ActivityManager( 1022): Killing 5744:com.samsung.helphub/1000 (adj 15): empty #31
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:05:54 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ConnectivityService( 1022): Validated NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 08 Jan 2016 23:05:54 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452294354902], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452294354882]}
D/ConnectivityService( 1022): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Don't send network conditions - lacking user consent.
D/ConnectivityService( 1022): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1022): Validated
D/ConnectivityService( 1022): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,E/Zygote  ( 6395): MountEmulatedStorage(),
I/KLMS-2.5.123: ( 2756): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
E/Zygote  ( 6395): v2,
I/libpersona( 6395): KNOX_SDCARD checking this for 10031
I/libpersona( 6395): KNOX_SDCARD not a persona
,I/ActivityManager( 1022): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6395 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 6395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
I/KLMS-2.5.123: ( 2756): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().START
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().START 
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/TimaKeyStoreProvider( 6395): TimaSignature is unavailable
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().END 
D/ActivityThread( 6395): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
,I/SO_AGENT( 6395): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,W/libprocessgroup( 1022): failed to open /acct/uid_10032/pid_5287/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_1000/pid_5744/cgroup.procs: No such file or directory
E/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,I/SA      ( 5850): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5850): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/SA      ( 5850): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5850): [SLFUCHKMGR] constructor called
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5850): [OR] == isSIMCardReady false ==
,I/SA      ( 5850): [SCU] == networkStateCheck == true
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/SA      ( 5850): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5850): isChinaCountryCode : false
,I/SA      ( 5850): [SCU] is ChinestModel Data Restricted   : false
I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
I/SA      ( 5850): [OR] == networkStateCheck true ==
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 5850): [OR] GetMyCountryZoneTask
,I/SA      ( 5850): [OR] onReceive END
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,I/ActivityManager( 1022): Killing 5715:com.google.android.partnersetup/u0a14 (adj 15): empty #31
,I/SA      ( 5850): [SRS] prepareGetMyCountryZone
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5850): [SSP] query invoked
,I/SA      ( 5850): [TPMU] GetMccFromDB : null
,I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [TPM] isNoProxy(default) : true
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/DBG_POLICYDM( 5802): [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/accuweather( 1580): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,E/File    ( 5850): fail readDirectory() errno=2
,D/SecContentProvider2( 1022): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1022): mCursor = null
,D/daemonapp( 1623): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,D/accuweather( 1580): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1580): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1,
W/libprocessgroup( 1022): failed to open /acct/uid_10014/pid_5715/cgroup.procs: No such file or directory
D/accuweather( 1580): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1580): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1580): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1580): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!,
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6415): MountEmulatedStorage(),
I/libpersona( 6415): KNOX_SDCARD checking this for 10121
E/Zygote  ( 6415): v2
I/libpersona( 6415): KNOX_SDCARD not a persona
,I/SELinux ( 6415): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6415): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 6415): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6415 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,D/TimaKeyStoreProvider( 6415): TimaSignature is unavailable
,D/ActivityThread( 6415): Added TimaKeyStore provider
,W/ResourcesManager( 6415): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6415): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6415): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6415): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6415): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6415): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6430): MountEmulatedStorage()
I/libpersona( 6430): KNOX_SDCARD checking this for 10141
E/Zygote  ( 6430): v2
I/libpersona( 6430): KNOX_SDCARD not a persona
I/SELinux ( 6430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1022): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6430 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Killing 5760:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,E/SELinux ( 6430): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6430): TimaSignature is unavailable
,D/ActivityThread( 6430): Added TimaKeyStore provider
,W/ResourcesManager( 6430): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService( 1022): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/BroadcastQueue( 1022): Failure sending broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
W/BroadcastQueue( 1022): android.os.DeadObjectException
W/BroadcastQueue( 1022): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1022): 	at android.os.BinderProxy.transact(Binder.java:511)
W/BroadcastQueue( 1022): 	at android.app.ApplicationThreadProxy.scheduleRegisteredReceiver(ApplicationThreadNative.java:1220)
W/BroadcastQueue( 1022): 	at com.android.server.am.BroadcastQueue.performReceiveLocked(BroadcastQueue.java:529)
W/BroadcastQueue( 1022): 	at com.android.server.am.BroadcastQueue.deliverToRegisteredReceiverLocked(BroadcastQueue.java:665)
W/BroadcastQueue( 1022): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:717)
W/BroadcastQueue( 1022): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
W/BroadcastQueue( 1022): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 1022): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 1022): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 1022): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,I/NetworkMonitor( 6286): type=WIFI subType= reason=null isConnected=true
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/GpsLocationProvider( 1022): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup( 1022): failed to open /acct/uid_10087/pid_5760/cgroup.procs: No such file or directory
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,I/BooksSync( 6112): Starting books sync for 61035162, extras: ade
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,I/BooksConfig( 6112): GmsCore Version = 7.8.99 (2134222-434)
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6455): MountEmulatedStorage(),
E/Zygote  ( 6455): v2
,I/libpersona( 6455): KNOX_SDCARD checking this for 1000
I/libpersona( 6455): KNOX_SDCARD not a persona
,I/SELinux ( 6455): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6455): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 6455): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6455): TimaSignature is unavailable
,D/ActivityThread( 6455): Added TimaKeyStore provider
,D/BadgeProvider( 5920): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,I/art     (  313): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 41.170ms,
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 17.948ms,
D/BadgeProvider( 5920): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5920): sendNotify, [notify] : null,
D/BadgeProvider( 5920): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5920): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5920): update, [UpdateCount] : 1
D/Launcher.Model( 1484): reloadBadges entered.
,I/art     (  313): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 604us total 17.716ms
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SecurityLogAgent( 6455): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6455): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6455): StateMachine : Current State = 1
I/art     ( 1704): Explicit concurrent mark sweep GC freed 17824(1026KB) AllocSpace objects, 3(60KB) LOS objects, 39% free, 7MB/12MB, paused 1.132ms total 44.147ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecurityLogAgent( 6455): StateMachine : Changed Current State = 1
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5850): [RC New] Execute method=[GET] start
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/SA      ( 5850): [RC New] Security=[true]
,I/System.out( 5850): Thread-1000(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
I/System.out( 5850): Thread-1000(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5850): Thread-1000(ApacheHTTPLog):isShipBuild true
I/System.out( 5850): Thread-1000(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5850): Thread-1000(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/ChimeraCfgMgr( 2072): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ChimeraCfgMgr( 2072): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService( 1022): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network,
,I/ActivityManager( 1022): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6477 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 6477): MountEmulatedStorage()
I/libpersona( 6477): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6477): v2
I/libpersona( 6477): KNOX_SDCARD not a persona
,I/SELinux ( 6477): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6477): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6477): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/System.out( 6242): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6242): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 6242): (HTTPLog)-Static: isShipBuild true
I/System.out( 6242): (HTTPLog)-Thread-1076-414281507: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 6242): (HTTPLog)-Static: isSBSettingEnabled false
,D/TimaKeyStoreProvider( 6477): TimaSignature is unavailable
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10102
D/ActivityThread( 6477): Added TimaKeyStore provider
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/System.out( 6242): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/Babel   ( 6242): connection state changed from UNKNOWN to CONNECTED
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 53849(2MB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 23MB/35MB, paused 2.533ms total 156.303ms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/BooksAccountManager( 6112): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6112): Soft error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6112): Sync error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6112): Finished books sync
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158591, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1022): Killing 5392:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #31
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,W/Kids    ( 2072): [AccountUtils] Account not ready
W/Kids    ( 2072): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2072): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2072): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2072): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2072): 	at java.lang.Thread.run(Thread.java:818)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/SPPClientService( 6477): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6477): [PushClientApplication] Push log off : This is Ship build version
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
E/SPPClientService( 6477): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
E/SPPClientService( 6477): [SystemStateMoniter] Current Time : 160298
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,E/SPPClientService( 6477): [SystemStateMoniter] No Connect : true
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,D/SPPClientService( 6477): PushLog.txt file is not deleted.
D/SPPClientService( 6477): PushLog.txt file is not deleted.
D/SPPClientService( 6477): ============PushLog. stop!
,E/SMD     (  290): DCD OFF
,E/Zygote  ( 6497): MountEmulatedStorage()
E/Zygote  ( 6497): v2
I/libpersona( 6497): KNOX_SDCARD checking this for 10110
I/libpersona( 6497): KNOX_SDCARD not a persona
,I/SELinux ( 6497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6497 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/SELinux ( 6497): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1022): Killing 5834:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/TimaKeyStoreProvider( 6497): TimaSignature is unavailable
,E/SPPClientService( 6477): [[SystemStateMonitorService]] No Active Internet
D/ActivityThread( 6497): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_10029/pid_5392/cgroup.procs: No such file or directory
,W/libprocessgroup( 1022): failed to open /acct/uid_10148/pid_5834/cgroup.procs: No such file or directory
,I/SA      ( 5850): [RC New] [v2liruge] api execute + 678
,I/SA      ( 5850): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5850): AsyncTask #1 calls detatch()
,I/SA      ( 5850): [ODM] saveOpenData( GEO_IP, PL )
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/SA      ( 5850): [OCP] update openData : PL
,I/SA      ( 5850): [TPMU] getNetworkMcc : 
,I/SA      ( 5850): [SCU] saveMccToPreferece Start
I/SA      ( 5850): [SCU] RegionMCC : 260
I/SA      ( 5850): [SSP] query invoked
,I/SA      ( 5850): [TPMU] GetMccFromDB : null
I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [SCU] saveMccToPreferece End
,I/SA      ( 5850): [RC New] executeRequest [v2liruge] end. 795
I/SA      ( 5850): [RC New] Execute end
I/SA      ( 5850): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5850): [OR] GetMyCountryZoneTask Success
,I/GAv4    ( 6497): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6497):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6497):   adb logcat -s GAv4
,W/GAv4    ( 6497): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6497): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6497): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager( 1022): Killing 5867:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #31
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/libprocessgroup( 1022): failed to open /acct/uid_10152/pid_5867/cgroup.procs: No such file or directory
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6497): Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,I/LibraryLoader( 6497): Time to load native libraries: 2 ms (timestamps 987-989)
I/LibraryLoader( 6497): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6497): Binding Chromium to main looper Looper (main, tid 1) {195c202}
I/LibraryLoader( 6497): Expected native library version number "",actual native library version number ""
I/chromium( 6497): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6497): Initializing chromium process, singleProcess=true
,W/art     ( 6497): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6497): ApplicationContext is null in ApplicationStatus
,W/chromium( 6497): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6497): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6497): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6497): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6497): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6497): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6497): Local Branch: 
I/Adreno-EGL( 6497): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6497): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6497):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6497): Requires BLUETOOTH permission
,I/NSApplication( 6497): Starting up...
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6555): MountEmulatedStorage(),
E/Zygote  ( 6555): v2
I/libpersona( 6555): KNOX_SDCARD checking this for 10077
I/libpersona( 6555): KNOX_SDCARD not a persona
,I/SELinux ( 6555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1022): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6555 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/SELinux ( 6555): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Killing 4895:com.google.android.gms.wearable/u0a11 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6555): TimaSignature is unavailable
,D/ActivityThread( 6555): Added TimaKeyStore provider
,W/libprocessgroup( 1022): failed to open /acct/uid_10011/pid_4895/cgroup.procs: No such file or directory
,D/WaitQueueForNetworkActivate( 6078): notifyNetworkActivated
,W/ContextImpl( 6078): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager( 1022): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 6078): AutoUpdateManager:IDLE:execute
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/InitializeManagerStateMachine( 6078): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6078): exit::IDLE
D/InitializeManagerStateMachine( 6078): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6078): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6078): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6078): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6078): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6078): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6078): entry::SUCCESS
D/hcjo    ( 6078): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/Hs20UtilService( 1664): Starting #10
,I/Hs20UtilService( 1664): Message received 5007
,D/hcjo    ( 6078): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6078): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6078): exit::SUCCESS
D/InitializeManagerStateMachine( 6078): entry::IDLE
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/ActivityManager( 1022): Killing 5722:com.android.mms/u0a41 (adj 15): empty #31
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #11
,I/Hs20UtilService( 1664): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #12
,I/Hs20UtilService( 1664): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1304): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1304): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1664): Starting #13
,I/Hs20UtilService( 1664): Message received 5007
,D/NearbySettings( 1304): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1304): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1022): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1022): mCursor = null
,D/SecContentProvider2( 1022): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1022): mCursor = null
,I/PCWCLIENTTRACE_PushUtil( 5778): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5778): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5778): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5778): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/splitIntent( 1022): intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=20
I/splitIntent( 1022): base  index=20, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
I/splitIntent( 1022): other index=22, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,D/CountryDetector( 1022): No listener is left
,V/MusicLeanback( 6286): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/SurfaceFlinger(  259): id=14 createSurf (1x1),1 flag=4, Uoast
,I/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,D/PowerManagerService( 1022): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022
I/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6338): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6338): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/libprocessgroup( 1022): failed to open /acct/uid_10041/pid_5722/cgroup.procs: No such file or directory
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true,
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,I/DBG_POLICYDM( 5802): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,I/FOTA_Client( 6375): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/FOTA_Client( 6375): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:05:57 GMT+01:00 2016
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.5.123: ( 2756): NetworkChangeOperations(): uploadRequestLog().END 
,I/DBG_POLICYDM( 5802): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.123: ( 2756): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
,I/SA      ( 5850): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/DBG_POLICYDM( 5802): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/DBG_POLICYDM( 5802): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,I/SA      ( 5850): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5850): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5850): [OR] == isSIMCardReady false ==
I/SA      ( 5850): [SCU] == networkStateCheck == true
,I/SA      ( 5850): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5850): isChinaCountryCode : false
I/SA      ( 5850): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5850): [OR] == networkStateCheck true ==
I/SA      ( 5850): [OR] GetMyCountryZoneTask
I/SA      ( 5850): [OR] onReceive END
,I/SA      ( 5850): [SRS] prepareGetMyCountryZone
,V/DownloadManager( 1229): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5850): [SSP] query invoked
,D/accuweather( 1580): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SA      ( 5850): [TPMU] GetMccFromDB : null
,I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [TPM] isNoProxy(default) : true
,I/SA      ( 5850): [RC New] Execute method=[GET] start
,D/SecContentProvider2( 1022): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1022): mCursor = null
,D/daemonapp( 1623): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1580): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1580): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1580): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1580): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1580): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1580): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/QuickConnect( 6415): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6415): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6415): PeriphStartReceiver.onReceive - no need to start
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/RCPManagerService( 1022): exchangeData() failure , invalid userId
,D/SecurityLogAgent( 6455): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6455): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6455): StateMachine : Current State = 1
,D/SecurityLogAgent( 6455): StateMachine : Changed Current State = 1
,I/SA      ( 5850): [RC New] Security=[true]
,I/System.out( 5850): Thread-1002(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5850): Thread-1002(ApacheHTTPLog):isShipBuild true
I/System.out( 5850): Thread-1002(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5850): Thread-1002(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10036
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2072): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2072): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/SPPClientService( 6477): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 6477): [SystemStateMoniter] Current Time : 162185
,E/SPPClientService( 6477): [SystemStateMoniter] No Connect : false
,I/System.out( 6242): (HTTPLog)-Static: isSBSettingEnabled false
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
D/hcjo    ( 6078): AutoUpdateManager:IDLE:execute
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/InitializeManagerStateMachine( 6078): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6078): exit::IDLE
D/InitializeManagerStateMachine( 6078): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6078): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6078): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6078): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6078): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6078): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6078): entry::SUCCESS
D/hcjo    ( 6078): AutoUpdateManager:INITCHECK:onInitializeSuccess
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/hcjo    ( 6078): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6078): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6078): exit::SUCCESS
D/InitializeManagerStateMachine( 6078): entry::IDLE
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
W/Kids    ( 2072): [AccountUtils] Account not ready
W/Kids    ( 2072): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2072): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2072): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2072): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2072): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2072): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2072): 	at java.lang.Thread.run(Thread.java:818)
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6308): wlan0: sendmsg: Cannot assign requested address
,D/SSRM:n  ( 1022): SIOP:: AP = 310
,I/SA      ( 5850): [RC New] [v2liruge] api execute + 570
,I/SA      ( 5850): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5850): AsyncTask #2 calls detatch()
,I/SA      ( 5850): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5850): [OCP] update openData : PL
,I/SA      ( 5850): [TPMU] getNetworkMcc : 
,I/SA      ( 5850): [SCU] saveMccToPreferece Start
I/SA      ( 5850): [SCU] RegionMCC : 260
I/SA      ( 5850): [SSP] query invoked
,I/SA      ( 5850): [TPMU] GetMccFromDB : null
,I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [SCU] saveMccToPreferece End
,I/SA      ( 5850): [RC New] executeRequest [v2liruge] end. 627
I/SA      ( 5850): [RC New] Execute end
,I/SA      ( 5850): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5850): [OR] GetMyCountryZoneTask Success
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/ConnectivityService( 1022): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,fe80::aec:a9ff:fe50:7542/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.132/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1022): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1022): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6596): MountEmulatedStorage()
I/libpersona( 6596): KNOX_SDCARD checking this for 10011
E/Zygote  ( 6596): v2
I/libpersona( 6596): KNOX_SDCARD not a persona
I/SELinux ( 6596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,I/ActivityManager( 1022): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=6596 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux ( 6596): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/MusicLeanback( 6286): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6286): Stop autocaching.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/TimaKeyStoreProvider( 6596): TimaSignature is unavailable
,D/ActivityThread( 6596): Added TimaKeyStore provider
,W/ResourcesManager( 6596): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6596): VM with version 2.1.0 has multidex support
,I/MultiDex( 6596): install
I/MultiDex( 6596): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6596): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ActivityThread( 6596): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6596): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1371cb11: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6596): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1022): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1022): base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
I/splitIntent( 1022): other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,D/GCM     ( 1704): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1704): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GmsCoreStatsServiceLauncher( 2072): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 6596): callingUid 10011, callindPid: 6596
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1849): [206] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,E/GmsUtils( 6286): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/GmsUtils( 6286): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2072): Restart initialization of location
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,V/AlarmManager( 1022): waitForAlarm result :4
,V/AlarmManager( 1022): waitForAlarm result :8
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5473): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5473): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 5473): [1] 5.onFinished: Scheduling replication attempt 5.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SurfaceFlinger(  259): id=14 Removed Uoast (8/9)
,I/SurfaceFlinger(  259): id=14 Removed Uoast (-2/9)
,D/PowerManagerService( 1022): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1022) eventTime = 165331
,D/PowerManagerService( 1022): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1022 (0x0)
,D/PowerManagerService( 1022): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1022, ws=WorkSource{10049}) (elapsedTime=3478)
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5778): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5778): [hasSamungAccount] - No Samsung Account
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SViewCoverWidget( 1178): initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5778): [GetString-S]
,I/ReactiveServiceManager( 5778): Supported : 1
,D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 11
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/QSEECOMAPI: ( 1022): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1022): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1022): handleString: Failed to handle string(-4)
E/terrier ( 1022): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5778): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5778): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5778): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5778): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5778): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5778): [ensureRegistration] - No Samsung account
,D/GCM     ( 1704): Connected
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,D/GCM     ( 1704): Message class com.google.f.a.a.p
,I/PowerManagerService( 1022): [PWL] Off : 105s ago
,I/jxcore-log( 6185): Test app app.js loaded
I/jxcore-log( 6185): 
,I/Choreographer( 6185): Skipped 664 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6185): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/Watchdog( 1022): !@Sync 5
,I/ActivityManager( 1022): Killing 5155:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/libprocessgroup( 1022): failed to open /acct/uid_10039/pid_5155/cgroup.procs: No such file or directory
,E/SMD     (  290): DCD OFF
,I/dhcpcd  ( 6308): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6308): wlan0: no IPv6 Routers available
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6078): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6078): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6078): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6078): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6078): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6078): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6078): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6078): entry::IDLE
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 6078): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6078): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6078): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6078): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 6078): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6078): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 6078): entry::IDLE
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 300
,V/AlarmManager( 1022): waitForAlarm result :4
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 34196(1822KB) AllocSpace objects, 10(168KB) LOS objects, 33% free, 23MB/35MB, paused 2.464ms total 166.821ms
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/VacuumService( 1704): Vacuum at: now=1452294369367 tag=VacuumService
,I/GoogleURLConnFactory( 1704): Using platform SSLCertificateSocketFactory
,W/Uploader( 1704): No account for auth token provided
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/System.out( 1704): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1704): (HTTPLog)-Static: isShipBuild true
I/System.out( 1704): (HTTPLog)-Thread-204-242215678: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  280): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  280): getNetworkForDns: using netid 503 for uid 10011
,I/System.out( 1704): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,I/qtaguid ( 1704): Tagging socket 62 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/Uploader( 1704): No account for auth token provided
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/Uploader( 1704):  no longer exists, so no auth token.
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,E/Uploader( 1704): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1704): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1704): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1704): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1704): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1704): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/System.out( 1704): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 1704): Tagging socket 58 with tag 120100000000{4609,0} for uid -1, pid: 1704, getuid(): 10011
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only,
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
D/PersonaManager( 1178): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,E/SQLiteLog( 1704): (10) POSIX Error : 11 SQLite Error : 3850
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
,I/MotionRecognitionService( 1022): mGripSensorEnabled= false
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,D/SSRM:n  ( 1022): SIOP:: AP = 290
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 5473): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 5473): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 5473): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged,
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :4
,I/BooksSync( 6112): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6112): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
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
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6112): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6112): Soft error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
E/BooksSync( 6112): Sync error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,I/BooksSync( 6112): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 192016, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,D/SSRM:n  ( 1022): SIOP:: AP = 270
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1022): !@Sync 6,
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,E/SMD     (  290): DCD OFF
,I/PowerManagerService( 1022): [PWL] Off : 140s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1022): waitForAlarm result :4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/Atfwd_Sendcmd(  331): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  331): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,V/AlarmManager( 1022): waitForAlarm result :4
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,V/AlarmManager( 1022): waitForAlarm result :8
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/Watchdog( 1022): !@Sync 7
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,I/PowerManagerService( 1022): [PWL] Off : 180s ago
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 3
,V/AlarmManager( 1022): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
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
,I/BooksSync( 6112): Starting books sync for 61035162, extras: ade
,I/BooksConfig( 6112): GmsCore Version = 7.8.99 (2134222-434)
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1022): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/NotificationService( 1022): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found,
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/GLSUser ( 1704): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,I/GLSUser ( 1704): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1704): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1704): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1704): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/BooksAccountManager( 6112): auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,E/BooksSync( 6112): Soft error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,E/BooksSync( 6112): Sync error
E/BooksSync( 6112): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/BooksSync( 6112): com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
I/BooksSync( 6112): Finished books sync
,D/SyncManager( 1022): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 255977, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1022): mCursor = null
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1022): stay LED for fully charged
D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/Watchdog( 1022): !@Sync 8
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.,
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1022): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
D/BatteryService( 1022): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1022): stay LED for fully charged
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/BatteryService( 1022): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1022): Plugged
I/MotionRecognitionService( 1022): mGripSensorEnabled= false
,V/EmergencyMode( 1419): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1419): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 3141): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3141): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1178): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1178): level :100 plugged : 2
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...,
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  290): DCD OFF
,V/AlarmManager( 1022): waitForAlarm result :8
,V/AlarmManager( 1022): waitForAlarm result :4
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
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1022): [PWL] Off : 225s ago
,E/Watchdog( 1022): !@Sync 9
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  331): Waiting for service AtCmdFwd...
,E/SMD     (  290): DCD OFF
,W/Atfwd_Sendcmd(  331): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  290): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1022): Do not check CP during LCD off.,
,D/SSRM:n  ( 1022): SIOP:: AP = 260,
,W/ContextImpl( 1022): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,E/SMD     (  290): DCD OFF
,E/SMD     (  290): DCD OFF
,D/BatteryService( 1022): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  290): DCD OFF
,D/SSRM:n  ( 1022): SIOP:: AP = 260
,E/SMD     (  290): DCD OFF
,I/jxcore-log( 6185): --= Surplus to requirements =--
I/jxcore-log( 6185): 
,I/jxcore-log( 6185): ****TEST TOOK:  ms ****
I/jxcore-log( 6185): 
I/jxcore-log( 6185): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6185): 
,D/AndroidRuntime( 6709): 
D/AndroidRuntime( 6709): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6709): CheckJNI is OFF
,D/AndroidRuntime( 6709): readGMSProperty: start
D/AndroidRuntime( 6709): readGMSProperty: already setted!!
D/AndroidRuntime( 6709): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6709): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6709): readGMSProperty: end
D/AndroidRuntime( 6709): addProductProperty: start
,E/AffinityControl( 6709): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6709): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1022): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1022): START PACKAGE DELETE: observer{176381212},
D/PackageManager( 1022): pkg{<packageName>}
D/PackageManager( 1022): user{0}
D/PackageManager( 1022): caller{2000}
D/PackageManager( 1022): flags{3}
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1022): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1022): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1022): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1022): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1022): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 1022): !@killApplicatoin: 10338, uninstall pkg
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=-1: uninstall pkg
,I/ActivityManager( 1022): Killing 6185:com.test.thalitest/u0a338 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1022): Skipping PackageSetting{14e6bf33 com.example.hello/10346} due to missing metadata
,I/ActivityManager( 1022):   Force finishing activity ActivityRecord{f22ca32 u0 com.test.thalitest/.MainActivity t20}
,E/JavaBinder( 1022): !!! FAILED BINDER TRANSACTION !!!
,D/InputDispatcher( 1022): Focus left window: 6185
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (6/8)
I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1022): Focused application released
,D/PointerIcon( 1022): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1022): setMouseCustomIcon IconType is same.101
,I/SurfaceFlinger(  259): id=13 Removed NainActivit (-2/8)
,I/ActivityManager( 1022): Force stopping com.test.thalitest appid=10338 user=0: pkg removed
,W/ActivityManager( 1022): CustomStartingWindow se packge removed so remove capture also
,I/art     ( 2772): Explicit concurrent mark sweep GC freed 22085(1219KB) AllocSpace objects, 4(64KB) LOS objects, 50% free, 3MB/7MB, paused 823us total 36.165ms
,I/InputReader( 1022): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 6062): Explicit concurrent mark sweep GC freed 100(15KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 5MB/7MB, paused 779us total 30.863ms
,E/SamsungIME( 1869): mOCRHelper is null
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Sat Jan 09 00:08:30 GMT+01:00 2016
,W/GeofencerStateMachine( 1849): Ignoring removeGeofence because network location is disabled.
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/ResourcesManager( 1453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/KLMS-2.5.123: ( 2756): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1022): intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,I/splitIntent( 1022): base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
I/splitIntent( 1022): other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
I/splitIntent( 1022): arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onCreate()
,I/KLMS-2.5.123: ( 2756): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.123: ( 2756): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6722): MountEmulatedStorage()
E/Zygote  ( 6722): v2
,I/libpersona( 6722): KNOX_SDCARD checking this for 10090,
,I/ActivityManager( 1022): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6722 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): PACKAGE_REMOVED
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1022): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1022): mCursor = null
,I/libpersona( 6722): KNOX_SDCARD not a persona
,I/SELinux ( 6722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 6722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 6722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.123: ( 2756): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/RegisteredServicesCache( 1442): empty dynamic service
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 43362(3MB) AllocSpace objects, 65(1053KB) LOS objects, 33% free, 24MB/36MB, paused 2.781ms total 181.858ms
,I/art     ( 1022): WaitForGcToComplete blocked for 180.198ms for cause Explicit
,D/TimaKeyStoreProvider( 6722): TimaSignature is unavailable
,D/ActivityThread( 6722): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): listeningToPackageRemoved().END
,I/KLMS-2.5.123: ( 2756): KLMSIntentService(): onDestroy()
,D/RCPManagerService( 1022): PackageReceiver onReceive()
,I/HarmonyEASService( 1022): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1022): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService( 1022): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1022): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1022): no available spell checker services found
,D/elm:15121( 6722): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:15121( 6722): ELMEngine.ELMEngine( context ).
,D/elm:15121( 6722): MDMBridge.setEnterpriseBridge()
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6722): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15121( 6722): ElmAgentService : onCreate()
,D/elm:15121( 6722): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15121( 6722): MainReceiver.listeningToPackageRemoved()
D/elm:15121( 6722): MDMBridge.getInstance()
D/elm:15121( 6722): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6722): MDMBridge.getAllLicenseInfoFromSDK()
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15121( 6722): ElmAgentService : onDestroy().
,I/ActivityManager( 1022): Killing 5900:com.sec.android.app.myfiles/u0a42 (adj 15): empty #31
,I/art     ( 1022): Explicit concurrent mark sweep GC freed 11880(572KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.362ms total 181.569ms
,W/ResourceType( 1022): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 1022): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1022): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 1022): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1022): Receieved: android.intent.action.PACKAGE_REMOVED
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,D/PackageManager( 1022): delete codoeFile: 
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,V/ApplicationPolicy( 1022): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,I/AASA_removePackage( 1022): UID=10338 Target=com.test.thalitest
D/AASAuninstall( 1022): userId = 0, info.removedAppID = -1, info.uid = 10338, packageName = com.test.thalitest
,D/PackageManager( 1022): result of delete: 1{176381212}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TaskPersister( 1022): removeObsoleteFile: deleting file=20_task.xml
,V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
D/SSRM:aZ ( 1022): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1022): uID is 10338
V/EnterpriseBillingPolicy( 1022): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - enter
D/AndroidRuntime( 6709): Shutting down VM
V/EnterpriseBillingPolicyStorage( 1022): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1022): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1022): getBillingProfileForVpnEngine - end - null
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1022): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1022): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1022): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1022): failed to open /acct/uid_10042/pid_5900/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 5778): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5778): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5778): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5778): [onReceive] - android.intent.action.PACKAGE_REMOVED
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6739): MountEmulatedStorage(),
E/Zygote  ( 6739): v2
I/libpersona( 6739): KNOX_SDCARD checking this for 10029
I/libpersona( 6739): KNOX_SDCARD not a persona,
,I/SELinux ( 6739): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 6739): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1022): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6739 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 6739): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6739): TimaSignature is unavailable
,D/ActivityThread( 6739): Added TimaKeyStore provider
,I/FeatureConfig( 6739): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/SA      ( 5850): [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 5850): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10338 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1022): Killing 5920:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,W/ActivityManager( 1022): userId = 0, bbcId = -10000
,W/ActivityManager( 1022): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1022): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,W/ResourcesManager( 6739): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1022): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6739): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  ( 6757): MountEmulatedStorage()
E/Zygote  ( 6757): v2
I/libpersona( 6757): KNOX_SDCARD checking this for 10039
I/libpersona( 6757): KNOX_SDCARD not a persona
,I/SELinux ( 6757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 6757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 6757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1022): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6757 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6739): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/art     ( 6709): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/TimaKeyStoreProvider( 6757): TimaSignature is unavailable
W/ResourcesManager( 6739): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread( 6757): Added TimaKeyStore provider
,W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/libprocessgroup( 1022): failed to open /acct/uid_10068/pid_5920/cgroup.procs: No such file or directory
,W/ResourcesManager( 6739): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6739): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/GalaxyFinderApplication( 6739): system/finder_cp/cpdata.xml file not found
,D/TimaService( 1022): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 1022): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 1022): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 1022): initializing...
,I/TLC_TIMA_PKM_initialize( 1022): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1022): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1022): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1022): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication( 1022): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1022): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1022): App is not loaded in QSEE
,E/SQLiteLog( 6757): (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 6757): Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.
E/SQLiteDatabase( 6757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6757): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
E/SQLiteDatabase( 6757): 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6757): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6757): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6757): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6757): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/QSEECOMAPI: ( 1022): Loaded image: APP id = 12
I/TZ: qc_tlc_communication( 1022): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
I/TLC_TIMA_PKM_initialize( 1022): Trustlet response is completed

```
