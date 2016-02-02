#### Test 57924002d5e0b14_thali04_samsung-SM-G900F Logs


```
--------- beginning of main
E/SMD     (  293): DCD ON
,D/AndroidRuntime( 7652): 
D/AndroidRuntime( 7652): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7652): CheckJNI is OFF
D/AndroidRuntime( 7652): setted country_code = Poland
D/AndroidRuntime( 7652): setted countryiso_code = PL
D/AndroidRuntime( 7652): setted sales_code = XEO
D/AndroidRuntime( 7652): readGMSProperty: start
D/AndroidRuntime( 7652): readGMSProperty: already setted!!
D/AndroidRuntime( 7652): readGMSProperty: end
D/AndroidRuntime( 7652): addProductProperty: start
E/AffinityControl( 7652): AffinityControl: registerfunction enter
D/AndroidRuntime( 7652): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  890): inState():  stateMachine is null !!
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  890): mDVFSHelper.acquire()
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  890): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7667 uid=10191 gids={50191, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
E/Zygote  ( 7667): MountEmulatedStorage()
E/Zygote  ( 7667): v2
I/libpersona( 7667): KNOX_SDCARD checking this for 10191
I/libpersona( 7667): KNOX_SDCARD not a persona
D/AndroidRuntime( 7652): Shutting down VM
I/SELinux ( 7667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7667): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/TimaKeyStoreProvider( 7667): TimaSignature is unavailable
D/ActivityThread( 7667): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (5/8)
I/SurfaceFlinger(  257): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SQLiteSecureOpenHelper( 3533): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3533): getDatabaseLocked(b,b,pwd)...
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager( 7667): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
F/libc    ( 7652): Fatal signal 11 (SIGSEGV), code 1, fault addr 0xb4baa05e in tid 7665 (Binder_1)
E/        (  289): tid 7665 does not exist in pid 7652. ignoring debug request
I/WebViewFactory( 7667): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 7667): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7667): Loading: webviewchromium
I/LibraryLoader( 7667): Time to load native libraries: 2 ms (timestamps 7227-7229)
I/LibraryLoader( 7667): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7667): Binding Chromium to main looper Looper (main, tid 1) {2cbd20eb}
I/LibraryLoader( 7667): Expected native library version number "",actual native library version number ""
I/chromium( 7667): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7667): Initializing chromium process, renderers=0
W/art     ( 7667): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7667): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7667): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 7667): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
I/Adreno-EGL( 7667): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7667): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7667): Build Date: 03/03/15 Tue
I/Adreno-EGL( 7667): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 7667): Remote Branch: 
I/Adreno-EGL( 7667): Local Patches: 
I/Adreno-EGL( 7667): Reconstruct Branch: 
W/chromium( 7667): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7667): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 7667): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7667): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7667): CordovaWebView is running on device made by: samsung
W/art     ( 7667): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7667): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7667): performCreate Call secproduct feature valuefalse
D/Activity( 7667): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7667): Render dirty regions requested: true
D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
I/SurfaceFlinger(  257): id=15 createSurf (1x1),1 flag=404, com.test.thalitest/com.test.thalitest.MainActivity
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/OpenGLRenderer( 7667): Initialized EGL, version 1.4
I/OpenGLRenderer( 7667): HWUI protection enabled for context ,  &this =0xa1653060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7667): Enabling debug mode 0
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{5cec506 u0 com.test.thalitest/.MainActivity t11} time:207675
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/art     (  890): Explicit concurrent mark sweep GC freed 40899(2MB) AllocSpace objects, 34(544KB) LOS objects, 31% free, 35MB/51MB, paused 1.606ms total 88.235ms
I/Timeline( 7667): Timeline: Activity_idle id: android.os.BinderProxy@306847ea time:207763
W/IInputConnectionWrapper( 7667): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 7667): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 7667): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361757184
,I/chromium( 7667): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 7667): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7667): 
,E/SMD     (  293): DCD ON
,W/jxcore-log( 7667): Initializing JXcore engine
W/jxcore-log( 7667): JXcore engine is ready
,E/auditd  ( 2202): In denial and Property audit_ondenial is set to 1 
,W/jxcore-log( 7667): Starting JXcore engine
,D/SecurityLogAgent:SEDenialService(  890): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/SecurityLogAgent:SEDenialService(  890): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,E/Zygote  ( 7745): MountEmulatedStorage()
I/libpersona( 7745): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7745): v2
I/libpersona( 7745): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7745 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7745): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7745): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7745): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7745): TimaSignature is unavailable
,D/ActivityThread( 7745): Added TimaKeyStore provider
,W/jxcore-log( 7667): Platform android
W/jxcore-log( 7667): 
W/jxcore-log( 7667): Process ARCH arm
W/jxcore-log( 7667): 
,D/ResourcesManager( 7745): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,D/SecurityLogAgent( 7745):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7745):  SeDenialReceiver : File path = null
,I/ActivityManager(  890): Killing 5872:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5872/cgroup.procs: No such file or directory
,I/jxcore-log( 7667): JXcore Cordova bridge is ready!
I/jxcore-log( 7667): 
,W/jxcore-log( 7667): JXcore engine is started
,I/jxcore-log( 7667): Toggling radios to true
I/jxcore-log( 7667): 
,D/BluetoothAdapter( 7667): enable()
,D/BluetoothAdapter( 7667): enable(): BT is already enabled..!
,D/WifiService(  890): New client listening to asynchronous messages
,I/WifiManager( 7667): packageName : com.test.thalitest
,D/SecContentProvider(  890): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  890): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  890): mCursor = null
,D/WifiService(  890): setWifiEnabled: true pid=7667, uid=10191
,E/WifiService(  890): Invoking mWifiStateMachine.setWifiEnabled
W/ActivityManager(  890): Permission Denial: getCurrentUser() from pid=7667, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  890): Failed getting userId using ActivityManagerNative
W/WifiService(  890): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7667, uid=10191 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  890): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:22619)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2122)
W/WifiService(  890): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2110)
W/WifiService(  890): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  890): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  890): name = wifi_on
,I/WifiService(  890): disconnect: pid=7667, uid=10191
,I/wpa_supplicant( 1308): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7667): Radios toggled
I/jxcore-log( 7667): 
,I/jxcore-log( 7667): My device name is: samsung-SM-G900F
I/jxcore-log( 7667): 
,I/wpa_supplicant( 1308): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1308): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1308): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1308): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1308): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 1308): Disconnected - do not scan
I/wpa_supplicant( 1308): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
,E/WifiStateMachine(  890): handleNetworkDisconnect c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,E/native  (  890): do suspend true
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,V/NativeCrypto( 2256): Read error: ssl=0xaf01ba00: I/O error during system call, Connection timed out
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
,V/NativeCrypto( 2256): SSL shutdown failed: ssl=0xaf01ba00: I/O error during system call, Broken pipe
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): ignoring duplicate network state non-change
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,E/WifiStateMachine(  890): Start Disconnecting Watchdog 1
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,I/wpa_supplicant( 1308): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1308): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1308): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1308): First Scan Start
,I/wpa_supplicant( 1308): Scan requested (ret=0) - scan timeout 30 seconds
,D/StatusBar.NetworkController( 1185): applyOpen
D/ConnectivityService(  890): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
E/WifiStateMachine(  890): ConnectModeState: Network connection lost 
E/WifiStateMachine(  890): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - processMessage - processMsg
E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/native  (  890): do suspend true
,D/WifiP2pService(  890): InactiveState{ what=143375 }
,D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1313): Starting #6
I/Hs20UtilService( 1313): Message received 5007
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/CommandListener(  288): Clearing all IP addresses on wlan0
D/ConnectivityService(  890): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  890): Not allowed due to - mEnabled false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524292
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - currTime: 1454440864407
D/WifiStateMachine(  890): updateConfiguredNetworkExpiration - AP, "NG700", is not shared AP.
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
D/ConnectivityService(  890): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=DISCONNECTED -> state= DISCONNECTED debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  890): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Disconnected - quitting
D/TelephonyNetworkFactory( 1478): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  890): NetworkAgent: NetworkAgent channel lost
D/CSLegacyTypeTracker(  890): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker(  890): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityManager.CallbackHandler( 2487): CM callback handler got msg 524292
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=SCANNING -> state= SCANNING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =DISCONNECTED and new state=SCANNING hidden=false
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ConnectivityService(  890): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked() took 7ms
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/Hs20UtilService( 1313): Starting #7
I/Hs20UtilService( 1313): Message received 5007
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1313): MountReceiver.mPrefHandler - 7002
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1478): FileWriteThread : threadType = 3
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/SmartBondingService(  890): getSBEnabled() enabled =false
,I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLoinfo wifi false
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,I/ApplicationPolicy(  890): updateDataUsageMap
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCWCLIENTTRACE_PushUtil( 7093): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7093): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7093): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7093): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/SLocation(  890): No Active Data Connection
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7093): noConnectivity : true
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6281): type=WIFI subType= reason=null isConnected=false
,I/SystemBroadcastReceiver( 6311): [#DCM#] [DCM_Performance] onReceive completed in time  970 microsec. 
,I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/accuweather( 2183): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/SystemBroadcastReceiver( 6311): [#DCM#] Calling notifyListeners. 
,I/DCMController( 6311): [#DCM#] onIntentReceived eventid = EVENT_NETWORK_CHANGED
,I/DCMController( 6311): [#DCM#] setIsConnectedForExtractors 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,E/Zygote  ( 7806): MountEmulatedStorage()
,E/Zygote  ( 7806): v2
I/libpersona( 7806): KNOX_SDCARD checking this for 10002
I/libpersona( 7806): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7806 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7806): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7806): TimaSignature is unavailable
,D/ActivityThread( 7806): Added TimaKeyStore provider
,D/ResourcesManager( 7806): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,I/ActivityManager(  890): Killing 6136:com.sec.providers.settingsearch/u0a167 (adj 15): bgCount ##41
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7832): MountEmulatedStorage()
E/Zygote  ( 7832): v2
I/libpersona( 7832): KNOX_SDCARD checking this for 1000
I/libpersona( 7832): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7832 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7832): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7832): TimaSignature is unavailable
,D/ActivityThread( 7832): Added TimaKeyStore provider
,D/ResourcesManager( 7832): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10167/pid_6136/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 7832): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 7832): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/DIAGMON_AGENT( 7832): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 7832): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 7832): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7832): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  890): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7851 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 7851): MountEmulatedStorage()
E/Zygote  ( 7851): v2
I/libpersona( 7851): KNOX_SDCARD checking this for 10010
I/libpersona( 7851): KNOX_SDCARD not a persona
,I/wpa_supplicant( 1308): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 1308): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1308): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 1308): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/WifiStateMachine(  890): [1,454,440,865,455 ms] noteScanEnd no scan source
,E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$DisconnectedState@3b0c1c77 sup_state=SCANNING debouncing=false
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATING -> state= CONNECTING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =SCANNING and new state=CONNECTING hidden=false
,E/WifiStateMachine(  890): setDetailed state send new extra info0x
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,I/SELinux ( 7851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
I/SELinux ( 7851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7851): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7851): TimaSignature is unavailable
,D/ActivityThread( 7851): Added TimaKeyStore provider
,D/ResourcesManager( 7851): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/wpa_supplicant( 1308): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 1308): Associated with C0.AA.48
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=ASSOCIATED -> state= CONNECTING debouncing=false
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=CONNECTING hidden=false
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,I/wpa_supplicant( 1308): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=FOUR_WAY_HANDSHAKE -> state= AUTHENTICATING debouncing=false
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=AUTHENTICATING hidden=false
E/WifiStateMachine(  890): setDetailed state send new extra info"NG700"
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,I/wpa_supplicant( 1308): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 1308): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,E/WifiStateMachine(  890): SUPPLICANT_STATE_CHANGE_EVENT state=GROUP_HANDSHAKE -> state= AUTHENTICATING debouncing=false
E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING hidden=false
I/wpa_supplicant( 1308): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1308): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1308): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1308): Blacklist: Clear (temp) 
I/wpa_supplicant( 1308): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  890): mCursor = null
,E/WifiStateMachine(  890): Network connection established
,D/WifiNative-HAL(  890): callSECApiVoid - ID [50]
,E/WifiStateMachine(  890): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR hidden=false
,I/ActivityManager(  890): Killing 6053:com.google.android.gm/u0a113 (adj 15): bgCount ##41
,E/WifiStateMachine(  890): setDetailed state, old =OBTAINING_IPADDR and new state=CONNECTING hidden=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  890): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,E/WifiStateMachine(  890): L2ConnectedState c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): L2ConnectedState "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/ConnectivityService(  890): Got NetworkAgent Messenger
D/ConnectivityService(  890): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): NetworkAgent connected
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/FOTA_Client( 7851): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,E/WifiStateMachine(  890): enter ObtainingIpState netId=0 "NG700"WPA_PSK  roam=0 static=false watchdog= 1
E/WifiStateMachine(  890): ObtainingIpAddress c0:ff:d4:d3:aa:48 config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  890): ObtainingIpAddress "NG700" nid=0
E/WifiConfigStore(  890): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  288): Setting iface cfg
E/WifiStateMachine(  890): Start Dhcp Watchdog 2
,I/FOTA_Client( 7851): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7851): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7879): MountEmulatedStorage()
E/Zygote  ( 7879): v2
I/libpersona( 7879): KNOX_SDCARD checking this for 10018
I/libpersona( 7879): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7879 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6311:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/art     (  319): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 266us total 13.154ms
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.869ms
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 false -want true stack:setSuspendOptimizationsNative - handlePreDhcpSetup - processMessage - processMsg
E/native  (  890): do suspend false
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 246us total 8.264ms
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES
D/SecContentProvider2(  890): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  890): mCursor = null
,I/SELinux ( 7879): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  890): failed to open /acct/uid_10113/pid_6053/cgroup.procs: No such file or directory
,I/SELinux ( 7879): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7879): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7879): TimaSignature is unavailable
,D/ActivityThread( 7879): Added TimaKeyStore provider
,D/ResourcesManager( 7879): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/KLMS-2.4.503: ( 7879): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.503: ( 7879): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454440865749
,I/KLMS-2.4.503: ( 7879): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.503: ( 7879): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,I/KLMS-2.4.503: ( 7879): StateImplV2(): networkChangeListener().END
,I/ActivityManager(  890): Killing 6376:com.sec.android.app.music:service/u0a43 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_10004/pid_6311/cgroup.procs: No such file or directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7895): MountEmulatedStorage()
I/libpersona( 7895): KNOX_SDCARD checking this for 10036
E/Zygote  ( 7895): v2
I/libpersona( 7895): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7895 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7895): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7895): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7895): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7895): TimaSignature is unavailable
,D/ActivityThread( 7895): Added TimaKeyStore provider
,D/ResourcesManager( 7895): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10043/pid_6376/cgroup.procs: No such file or directory
,I/SO_AGENT( 7895): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5199): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 7135): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7135): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 7135): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7135): [SLFUCHKMGR] constructor called
,I/SA      ( 7135): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 7135): [OR] == isSIMCardReady false ==
,I/SA      ( 7135): [SCU] == networkStateCheck == false
I/SA      ( 7135): [OR] onReceive END
,E/SPPClientService( 5199): [[SystemStateMonitorService]] No Active Internet
,E/dhcpcd  ( 7915): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/dhcpcd  ( 7915): version 5.5.6 starting
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/dhcpcd  ( 7915): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/PowerManagerService(  890): [PWL] Off : 140s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=890, ws=null) (elapsedTime=1496)
,E/Zygote  ( 7918): MountEmulatedStorage()
E/Zygote  ( 7918): v2
,I/libpersona( 7918): KNOX_SDCARD checking this for 10070
I/libpersona( 7918): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.widgetapp.ap.hero.accuweather for broadcast com.sec.android.widgetapp.ap.hero.accuweather/.easy.widget.WeatherClock: pid=7918 uid=10070 gids={50070, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7918): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7918): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7918): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  890): Killing 6780:com.google.android.gms:car/u0a11 (adj 15): bgCount ##41
,I/dhcpcd  ( 7915): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7915): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7915): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7915): bssid match
,I/dhcpcd  ( 7915): wlan0: rebinding lease of 192.168.1.136
,D/TimaKeyStoreProvider( 7918): TimaSignature is unavailable
,D/ActivityThread( 7918): Added TimaKeyStore provider
,D/ResourcesManager( 7918): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 7918): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7918): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7918): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/dhcpcd  ( 7915): wlan0: acknowledged 192.168.1.136 from 192.168.1.1
,W/libprocessgroup(  890): failed to open /acct/uid_10011/pid_6780/cgroup.procs: No such file or directory
,D/comsamsunglog( 7918): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7918): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7918): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7918): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7918): [KK AccuPhone]>>> ==============================================================================================
D/comsamsunglog( 7918): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7918): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7918): [KK AccuPhone]>>> ==============================================================================================
I/dhcpcd  ( 7915): wlan0: leased 192.168.1.136 for 86400 seconds
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: CMD_UPDATE_LINKPROPERTIES v4
,D/SettingsProvider(  890): name = aw_daemon_service_key_agree_popup_check
D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10070
,D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7918): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7918): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 7918): [KK AccuPhone]>>> UIMEM:90 [0:0] getInstance
D/accuweather( 7918): [KK AccuPhone]>>> UIMEM:78 [0:0] UIManager : create ui manager
,D/accuweather( 7918): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 7918): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 7918): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 7918): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,D/daemonapp( 1336): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/accuweather( 7918): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,D/accuweather( 7918): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7955): MountEmulatedStorage()
,E/Zygote  ( 7955): v2
I/libpersona( 7955): KNOX_SDCARD checking this for 1000
I/libpersona( 7955): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7955 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7058:com.google.android.partnersetup/u0a14 (adj 15): bgCount ##41
,I/SELinux ( 7955): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7955): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7955): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7955): TimaSignature is unavailable
,D/ActivityThread( 7955): Added TimaKeyStore provider
,D/ResourcesManager( 7955): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7955): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SMD     (  293): DCD ON
,I/KnoxUsageLogPro( 7955): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7955): premStatus:2
,I/KnoxUsageLogPro( 7955): isEulaShown : false
,I/KnoxUsageLogPro( 7955): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7982): MountEmulatedStorage()
E/Zygote  ( 7982): v2
I/libpersona( 7982): KNOX_SDCARD checking this for 10087
I/libpersona( 7982): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7982 uid=10087 gids={50087, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 7076:com.samsung.groupcast/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 7982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  890): failed to open /acct/uid_10014/pid_7058/cgroup.procs: No such file or directory
,E/SELinux ( 7982): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7982): TimaSignature is unavailable
,D/ActivityThread( 7982): Added TimaKeyStore provider
,D/ResourcesManager( 7982): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 1 true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - processMessage - processMsg
E/native  (  890): do suspend true
,D/WifiP2pService(  890): InactiveState{ what=143375 }
D/WifiP2pService(  890): P2pEnabledState{ what=143375 }
,E/WifiStateMachine(  890): WifiStateMachine DHCP successful
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTING reason: DHCP_SUCCESS v4 v4r v4dns isprov
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/WifiStateMachine(  890): Not connected state, yet.
E/WifiStateMachine(  890): VerifyingLinkState enter
,W/libprocessgroup(  890): failed to open /acct/uid_10015/pid_7076/cgroup.procs: No such file or directory
,D/WifiStateMachine(  890): updatePoorNetworkAvoidance - Poor Network Test Enabled / !mIsFmcNetwork : false / true - mPoorNetworkAvoidanceEnabled:disabled
D/WifiStateMachine(  890): updatePoorNetworkDetection - Airplane Mode Off / Mobile Data Enabled / SIM State-Ready / MobilePolicyDataDisabled / !mIsFmcNetwork : 
D/WifiStateMachine(  890): false / true / false / true / true - mPoorNetworkDetectionEnabled: disabled
D/WifiNative-HAL(  890): callSECApiInt - ID [210]
,E/WifiStateMachine(  890): setDetailed state, old =CONNECTING and new state=VERIFYING_POOR_LINK hidden=false
,E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/ConnectivityService(  890): Adding iface wlan0 to network 503
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/WifiWatchdogStateMachine(  890): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.DnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.SingDnsChecker(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  890): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
,E/WifiStateMachine(  890): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/WifiStateMachine(  890): Now, connected state.
E/WifiStateMachine(  890): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK hidden=false
,I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
,I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/StatusBar.NetworkController( 1185): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,E/WifiStateMachine(  890): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED hidden=false
,E/WifiStateMachine(  890): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/WifiTrafficPoller(  890): evaluateTrafficStatsPolling
I/WifiTrafficPoller(  890): mBoosterFLAG : 0
I/WifiTrafficPoller(  890): current booster mode : FullMode
,D/WifiNative-HAL(  890): callSECApiVoid - ID [212]
I/CLocInfoService(  890): External Intent Received android.net.wifi.STATE_CHANGE
,D/ConnectivityService(  890): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  890): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine(  890): ConnectedState Enter  mScreenOn=false scanperiod=20000
D/ConnectivityService(  890): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService(  890): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:192.168.1.136
,V/        (  288): QcRouteController
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,I/ActivityManager(  890): Killing 6449:com.samsung.android.app.galaxyfinder/u0a33 (adj 15): bgCount ##41
D/SSRM:m  (  890): SIOP:: AP = 300, PST = 287, CUR = 450
,D/Headlines( 5443): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5443): getCountryCode(): countryCode = PL
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  890): Setting Dns servers for network 503 to [/192.168.1.1]
,D/Headlines( 5443): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,E/Zygote  ( 8016): MountEmulatedStorage()
E/Zygote  ( 8016): v2
I/libpersona( 8016): KNOX_SDCARD checking this for 10127
I/libpersona( 8016): KNOX_SDCARD not a persona
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5443): queryCategory.  mRequest is not initialized.
I/ActivityManager(  890): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8016 uid=10127 gids={50127, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Nat464Xlat(  890): requiresClat: netType=1, connected=false, hasIPv4Address=true
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5443): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5443): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890): ignoring duplicate network state non-change
E/ConnectivityService(  890): updateNetworkInfo()
,D/ConnectivityService(  890): ignoring duplicate network state non-change
E/ConnectivityService(  890): updateNetworkInfo()
D/ConnectivityService(  890): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
,D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  890): Validated
,D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager(  890): Failed to clear dns cache for: com.samsung.android.app.galaxyfinder
,I/SELinux ( 8016): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  890): currentScore = 0, newScore = 60
I/SELinux ( 8016): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  890):    accepting network in place of null
E/SELinux ( 8016): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  890): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1478): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/CSLegacyTypeTracker(  890): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  890): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  890): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  890): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkStats(  890): updateIfacesLocked()
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked(flags=0x1)
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
D/NetworkStatsFactory(  890): UpdateStatsForKnox
D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  890): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): performPollLocked() took 3ms
D/ConnectivityService(  890): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524290
,D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
V/NetworkStats(  890): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/ConnectivityManager.CallbackHandler( 2487): CM callback handler got msg 524290
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/NtpTrustedTime(  890): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/StatusBar.NetworkController( 1185): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1185): applyOpen
,D/ConnectivityManager.CallbackHandler( 2487): CM callback handler got msg 524290
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1185): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1185): updateDataNetType()
D/StatusBar.NetworkController( 1185): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1185): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1185): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1185): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1185): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/TimaKeyStoreProvider( 8016): TimaSignature is unavailable
,D/ActivityThread( 8016): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10033/pid_6449/cgroup.procs: No such file or directory
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  256): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  256): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 8016): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/WebViewFactory( 8016): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/ResourcesManager( 8016): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 8016): Loading: webviewchromium
,I/LibraryLoader( 8016): Time to load native libraries: 4 ms (timestamps 2327-2331)
I/LibraryLoader( 8016): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 8016): Binding Chromium to main looper Looper (main, tid 1) {2b322c87}
,I/LibraryLoader( 8016): Expected native library version number "",actual native library version number ""
,I/chromium( 8016): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 8016): Initializing chromium process, renderers=0
,W/art     ( 8016): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 8016): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 8016): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46768 len=2953
,I/chromium( 8016): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229524 len:643667
W/AudioManagerAndroid( 8016): Requires BLUETOOTH permission
,I/Adreno-EGL( 8016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 8016): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 8016): Build Date: 03/03/15 Tue
I/Adreno-EGL( 8016): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 8016): Remote Branch: 
I/Adreno-EGL( 8016): Local Patches: 
I/Adreno-EGL( 8016): Reconstruct Branch: 
,I/NSApplication( 8016): Starting up...
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  890): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/Zygote  ( 8070): MountEmulatedStorage()
E/Zygote  ( 8070): v2
I/libpersona( 8070): KNOX_SDCARD checking this for 10137
I/libpersona( 8070): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8070 uid=10137 gids={50137, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 4883:com.sec.android.app.shealth/u0a34 (adj 15): bgCount ##41
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Tethering(  890): MasterInitialState.processMessage what=3
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  890): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  890): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
I/CLocInfoService(  890): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  890): CLocinfo wifi true 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 8070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/accuweather( 2183): [KK AccuPhone]>>> SWW:66 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SELinux ( 8070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 8070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SmartBondingService(  890): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2240): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 2240): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 6281): type=WIFI subType= reason=null isConnected=true
I/DBG_DM  ( 3748): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3748): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/TimaKeyStoreProvider( 8070): TimaSignature is unavailable
,D/ActivityThread( 8070): Added TimaKeyStore provider
,D/ResourcesManager( 8070): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 8070): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8070): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 8070): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,W/libprocessgroup(  890): failed to open /acct/uid_10034/pid_4883/cgroup.procs: No such file or directory
,D/QuickConnect( 8070): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8070): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8070): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8088): MountEmulatedStorage()
E/Zygote  ( 8088): v2
I/libpersona( 8088): KNOX_SDCARD checking this for 10162
I/libpersona( 8088): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8088 uid=10162 gids={50162, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5979:com.samsung.android.sdk.samsunglink/u0a41 (adj 15): bgCount ##41
,I/SELinux ( 8088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8088): TimaSignature is unavailable
,D/ActivityThread( 8088): Added TimaKeyStore provider
,D/ResourcesManager( 8088): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 8088): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 8088): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8088): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8088): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10041/pid_5979/cgroup.procs: No such file or directory
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/BadgeProvider( 7198): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,D/BadgeProvider( 7198): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7198): sendNotify, [notify] : null
D/BadgeProvider( 7198): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7198): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7198): update, [UpdateCount] : 1
D/Launcher.Model( 1500): reloadBadges entered.
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7745): KnoxConfiguration : Current State = 1
V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
D/SecurityLogAgent( 7745): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7745): StateMachine : Current State = 1
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
D/SecurityLogAgent( 7745): StateMachine : Changed Current State = 1
,I/ActivityManager(  890): Killing 5948:com.sec.android.gallery3d/u0a47 (adj 15): bgCount ##41
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,E/Zygote  ( 8112): MountEmulatedStorage()
V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,E/Zygote  ( 8112): v2
I/libpersona( 8112): KNOX_SDCARD checking this for 10177
I/libpersona( 8112): KNOX_SDCARD not a persona
V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
,I/ActivityManager(  890): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8112 uid=10177 gids={50177, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,V/BitmapFactory( 8088): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/ConnectivityService(  890): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/SELinux ( 8112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  890): failed to open /acct/uid_10047/pid_5948/cgroup.procs: No such file or directory
I/SELinux ( 8112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8112): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8112): TimaSignature is unavailable
,D/ActivityThread( 8112): Added TimaKeyStore provider
,D/ResourcesManager( 8112): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/ActivityManager(  890): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager(  890): Killing 7214:com.wsomacp/u0a24 (adj 15): bgCount ##41
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WaitQueueForNetworkActivate( 7538): notifyNetworkActivated
,W/ContextImpl( 7538): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/libprocessgroup(  890): failed to open /acct/uid_10024/pid_7214/cgroup.procs: No such file or directory
,D/hcjo    ( 7538): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7538): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 7538): exit::IDLE
D/InitializeManagerStateMachine( 7538): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Hs20UtilService( 1313): Starting #8
,I/Hs20UtilService( 1313): Message received 5007
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7538): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7538): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7538): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7538): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7538): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7538): entry::SUCCESS
D/hcjo    ( 7538): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,D/hcjo    ( 7538): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 7538): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7538): exit::SUCCESS
D/InitializeManagerStateMachine( 7538): entry::IDLE
,I/Hs20UtilService( 1313): Starting #9
,I/Hs20UtilService( 1313): Message received 5007
D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #10
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1313): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1313): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 1313): Starting #11
,I/Hs20UtilService( 1313): Message received 5007
,D/NearbySettings( 1313): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1313): MountReceiver.onReceive - Keep current state
,I/WifiStateMachine(  890): callSECApi what=220
D/WifiStateMachine(  890): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/PCWCLIENTTRACE_PushUtil( 7093): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 7093): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7093): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7093): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7832): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7832): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/SurfaceFlinger(  257): id=16 createSurf (1x1),1 flag=4, Toast
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/PowerManagerService(  890): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1185): value : false
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,I/FOTA_Client( 7851): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7851): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7851): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.503: ( 7879): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1185): value : false
,I/KLMS-2.4.503: ( 7879): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454440867874
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/KLMS-2.4.503: ( 7879): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,I/KLMS-2.4.503: ( 7879): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.503: ( 7879): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.503: ( 7879): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.503: ( 7879): StateImplV2(): networkChangeListener().END
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1185): value : false
,I/SO_AGENT( 7895): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5199): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 7135): [OR] onReceive log=[SA = 2.1.0172 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOE5 PSS = 5.219788042639568  ]
,I/SA      ( 7135): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 7135): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 7135): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7135): [OR] == isSIMCardReady false ==
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 7135): [SCU] == networkStateCheck == true
I/SA      ( 7135): [DM] getCountryCodeFromCSC : PL
I/SA      ( 7135): isChinaCountryCode : false
I/SA      ( 7135): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 7135): [OR] == networkStateCheck true ==
,I/SA      ( 7135): [OR] GetMyCountryZoneTask
,I/SA      ( 7135): [OR] onReceive END
,I/SA      ( 7135): [SRS] prepareGetMyCountryZone
,I/SA      ( 7135): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 7135): [SSP] query invoked
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 7135): [TPMU] GetMccFromDB : null
I/SA      ( 7135): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 7135): [TPM] isNoProxy(default) : true
,D/accuweather( 7918): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 7918): [KK AccuPhone]>>> UIMEM:106 [0:0] The widget does not exist in idle!!
,I/KnoxUsageLogPro( 7955): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
I/KnoxUsageLogPro( 7955): premStatus:2
,I/KnoxUsageLogPro( 7955): isEulaShown : false
I/KnoxUsageLogPro( 7955): KnoxUsageReceiver onReceive : not Processible, just return
,E/File    ( 7135): fail readDirectory() errno=2
,D/Headlines( 5443): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5443): getCountryCode(): countryCode = PL
,D/Headlines( 5443): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/Headlines( 5443): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5443): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5443): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5443): requestUpdateNewsWelcomeCard !!! no welcome card
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 8070): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 8070): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 8070): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  890): exchangeData() failure , invalid userId
D/RCPManagerService(  890): exchangeData() failure , invalid userId
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7745): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7745): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7745): StateMachine : Current State = 1
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7745): StateMachine : Changed Current State = 1
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 7538): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 7538): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 7538): exit::IDLE
D/InitializeManagerStateMachine( 7538): entry::NETWORK_CHECK
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 7538): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 7538): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 7538): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 7538): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 7538): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 7538): entry::SUCCESS
D/hcjo    ( 7538): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 7538): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 7538): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 7538): exit::SUCCESS
D/InitializeManagerStateMachine( 7538): entry::IDLE
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/SA      ( 7135): [RC New] Execute method=[GET] start
,I/SA      ( 7135): [RC New] Security=[true]
,I/System.out( 7135): Thread-1100(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7135): Thread-1100(ApacheHTTPLog):isShipBuild true
,I/System.out( 7135): Thread-1100(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/jxcore-log( 7667): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7667): 
,E/SMD     (  293): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7667): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7667): 
,I/SA      ( 7135): [RC New] [v2liruge] api execute + 986
I/SA      ( 7135): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 7135): AsyncTask #1 calls detatch()
,I/SA      ( 7135): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 7135): [OCP] update openData : PL
,I/SA      ( 7135): [TPMU] getNetworkMcc : 
,I/SA      ( 7135): [SCU] saveMccToPreferece Start
I/SA      ( 7135): [SCU] RegionMCC : 260
I/SA      ( 7135): [SSP] query invoked
,I/SA      ( 7135): [TPMU] GetMccFromDB : null
I/SA      ( 7135): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 7135): [SCU] saveMccToPreferece End
I/SA      ( 7135): [RC New] executeRequest [v2liruge] end. 1038
I/SA      ( 7135): [RC New] Execute end
,I/SA      ( 7135): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 7135): [OR] GetMyCountryZoneTask Success
,I/jxcore-log( 7667): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7667): 
,I/jxcore-log( 7667): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 7667): 
,I/jxcore-log( 7667): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7667): 
,I/WifiStateMachine(  890): REQUEST_POWER_SAVE_ON
,E/WifiStateMachine(  890): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/dhcpcd  ( 7915): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 7915): wlan0: sendmsg: Cannot assign requested address
,E/WifiStateMachine(  890): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,D/ConnectivityService(  890): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  890): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.136/24,fe80::ee1f:72ff:fe63:1186/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}
D/ConnectivityService(  890): identical MTU - not setting
D/ConnectivityService(  890): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  890): updateSourceRoutes : add src route for:fe80::ee1f:72ff:fe63:1186
,V/        (  288): QcRouteController
E/WifiStateMachine(  890): updateLinkProperties nid: 0 state: CONNECTED reason: CMD_UPDATE_LINKPROPERTIES v4 v4r v4dns isprov
,D/SmartBondingService(  890): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  890): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
D/SmartBondingService(  890): getSBEnabled() enabled =false
,V/        (  288): QcRouteController
,W/NetworkManagementService(  890): route cmd failed: 
W/NetworkManagementService(  890): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '72 route replace src v6 wlan0 fe80::ee1f:72ff:fe63:1186 2 ::' failed with '400 72 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  890): '
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:438)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:371)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:336)
W/NetworkManagementService(  890): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:321)
W/NetworkManagementService(  890): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5478)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5305)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService.access$1900(ConnectivityService.java:230)
W/NetworkManagementService(  890): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2324)
W/NetworkManagementService(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  890): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Nat464Xlat(  890): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  890): calling update connectivity
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  890): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  890): calling update connectivity
D/ConnectivityManager.CallbackHandler( 2487): CM callback handler got msg 524295
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  890):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1185): CM callback handler got msg 524295
D/ConnectivityService(  890): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 2487): CM callback handler got msg 524295
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  257): id=16 Removed Toast (8/9)
I/SurfaceFlinger(  257): id=16 Removed Toast (-2/9)
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,D/PowerManagerService(  890): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 890) eventTime = 216788
,D/PowerManagerService(  890): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=890 (0x0)
,D/PowerManagerService(  890): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=890, ws=WorkSource{10058}) (elapsedTime=3478)
,D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
,I/GAV4    ( 8016): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  293): DCD ON
,I/PCWCLIENTTRACE_SYSTEMReceiver( 7093): mConnectivityHandler : connected
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 7093): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7093): [GetString-S]
,I/ReactiveServiceManager( 7093): Supported : 1
,D/QSEECOMAPI: (  890): QSEECom_get_handle sb_length = 0x2040
D/QSEECOMAPI: (  890): App is not loaded in QSEE
,D/QSEECOMAPI: (  890): Loaded image: APP id = 3
,D/QSEECOMAPI: (  890): QSEECom_dealloc_memory 
,D/QSEECOMAPI: (  890): QSEECom_shutdown_app, app_id = 3
E/terrier (  890): handleString: Failed to handle string(-4)
E/terrier (  890): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 7093): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 7093): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 7093): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7093): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 7093): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 7093): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7667): Test app app.js loaded
I/jxcore-log( 7667): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 7667): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32aed863 added. We now have 1 listener(s)
,I/jxcore-log( 7667): BLE advertisement is supported
I/jxcore-log( 7667): 
,I/chromium( 7667): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/dhcpcd  ( 7915): wlan0: sending IPv6 Router Solicitation
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 288, CUR = 450
,D/PreloadUpdateManagerStateMachine( 7538): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7538): exit::IDLE
D/PreloadUpdateManagerStateMachine( 7538): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7538): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 7538): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7538): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7538): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7538): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 7538): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 7538): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 7538): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 7538): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 7538): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 7538): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 7538): entry::IDLE
,I/dhcpcd  ( 7915): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7915): wlan0: no IPv6 Routers available
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/Watchdog(  890): !@Sync 7
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON,
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 180s ago
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 288, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  890): !@Sync 8
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  293): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 270, PST = 285, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 270, PST = 285, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 9
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 284, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  890): [PWL] Off : 225s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 284, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  890): initializing...
,I/TLC_TIMA_PKM_initialize(  890): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  890): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  890): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  890): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  890): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  890): App is not loaded in QSEE
,D/QSEECOMAPI: (  890): Loaded image: APP id = 3
,I/TZ: qc_tlc_communication(  890): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  890): Trustlet response is completed
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 274, CUR = 450
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  890): waitForAlarm result :4
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 8193): MountEmulatedStorage()
,E/Zygote  ( 8193): v2
,I/libpersona( 8193): KNOX_SDCARD checking this for 10080
I/libpersona( 8193): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=8193 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 8193): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 8193): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 8193): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 8193): TimaSignature is unavailable
,D/ActivityThread( 8193): Added TimaKeyStore provider
,D/ResourcesManager( 8193): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  890): Killing 7160:com.android.mms/u0a49 (adj 15): bgCount ##41
,D/CountryDetector(  890): No listener is left
,W/libprocessgroup(  890): failed to open /acct/uid_10049/pid_7160/cgroup.procs: No such file or directory
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 270, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 267, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  890): !@Sync 11
,I/PowerManagerService(  890): [PWL] Off : 275s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 264, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 262, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 261, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 12
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 330s ago
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 13
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 14
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 390s ago
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 1
,E/Watchdog(  890): !@Sync 15
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/bootchecker(  322): bootchecker wake up!!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 16
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 4
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 17
,I/PowerManagerService(  890): [PWL] Off : 455s ago
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  326): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,W/Atfwd_Sendcmd(  326): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 18
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  326): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  326): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/Atfwd_Daemon(  326): Stop the daemon....
,E/Watchdog(  890): !@Sync 19
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 525s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/Watchdog(  890): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,I/ActivityManager(  890): Killing 7230:com.sec.android.app.myfiles/u0a50 (adj 15): bgCount ##41,
,W/libprocessgroup(  890): failed to open /acct/uid_10050/pid_7230/cgroup.procs: No such file or directory
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 21
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 600s ago
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 22
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 23
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 24
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 680s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 25
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 26
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  890): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1185): handleTimeUpdate
,D/KeyguardEffectViewController( 1185): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1185): *** don't update sliding image ***
,D/LightsService(  890): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,E/LightSensor(  890): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1185): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/LightSensor(  890): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  890): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  890): unregisterListener ::   
,D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 27
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 765s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 28
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 29
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  293): DCD ON
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 855s ago
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 31
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 32
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 33
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 950s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 34
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 35
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 36
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 1050s ago
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 37
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 38
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 39
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  890): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  890): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  890): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService(  890): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  890): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  890): Updating Usage Statistics in DB @ 1454441866656
,I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
,W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
,W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
,W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
,W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  890): ::getAppControlDB: Exception to create DB
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  890): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  890): Done Updating Usage Statistics in DB @ 1454441866931
,E/SMD     (  293): DCD ON,
,E/Watchdog(  890): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  890): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  890): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 1155s ago
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 41
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 42
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 43
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 44
,I/PowerManagerService(  890): [PWL] Off : 1265s ago
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 45
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  890): !@Sync 46
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,D/BatteryService(  890): stay LED for fully charged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3241): Disconnected process message: 10
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 260, PST = 260, CUR = 450
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  293): DCD ON
E/SMD     (  293): DCD ON
D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
D/BatteryService(  890): stay LED for fully charged
D/KeyguardUpdateMonitor( 1185): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1185): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 1185):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3241): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3241): Disconnected process message: 10
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1185): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 8294): 
D/AndroidRuntime( 8294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8294): CheckJNI is OFF
D/AndroidRuntime( 8294): setted country_code = Poland
D/AndroidRuntime( 8294): setted countryiso_code = PL
D/AndroidRuntime( 8294): setted sales_code = XEO
D/AndroidRuntime( 8294): readGMSProperty: start
D/AndroidRuntime( 8294): readGMSProperty: already setted!!
D/AndroidRuntime( 8294): readGMSProperty: end
D/AndroidRuntime( 8294): addProductProperty: start
E/AffinityControl( 8294): AffinityControl: registerfunction enter
D/AndroidRuntime( 8294): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  890): START PACKAGE DELETE: observer{899858726}
D/PackageManager(  890): pkg{<packageName>}
D/PackageManager(  890): user{0}
D/PackageManager(  890): caller{2000}
D/PackageManager(  890): flags{3}
D/PersonaManagerService(  890): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  890): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  890): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  890): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  890): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  890): getApplicationUninstallationEnabled
D/ApplicationPolicy(  890): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  890): !@killApplicatoin: 10191, uninstall pkg
I/ActivityManager(  890): Force stopping com.test.thalitest appid=10191 user=-1: uninstall pkg
I/ActivityManager(  890): Killing 7667:com.test.thalitest/u0a191 (adj 0): stop com.test.thalitest
I/ActivityManager(  890):   Force finishing activity ActivityRecord{5cec506 u0 com.test.thalitest/.MainActivity t11}
W/ActivityManager(  890): mDVFSHelper.acquire()
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/WifiService(  890): Client connection lost with reason: 4
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/WindowState(  890): WIN DEATH: Window{16897fbc u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (5/8)
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1185): value : false
I/SurfaceFlinger(  257): id=15 Removed com.test.thalitest/com.test.thalitest.MainActivity (-2/8)
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/SQLiteSecureOpenHelper( 3533): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3533): getDatabaseLocked(b,b,pwd)...
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/FocusedStackFrame(  890): Set to : 0
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3748): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/ActivityManager(  890): Force stopping com.test.thalitest appid=10191 user=0: pkg removed
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 48
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3748): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 48
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3748): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
I/art     ( 6353): Explicit concurrent mark sweep GC freed 27864(1556KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 378us total 38.061ms
I/art     ( 2487): Explicit concurrent mark sweep GC freed 37076(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 21MB/28MB, paused 664us total 61.002ms
E/SamsungIME( 1872): mOCRHelper is null
I/art     ( 1576): Explicit concurrent mark sweep GC freed 33780(2014KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 16MB/27MB, paused 438us total 53.933ms
W/GeofencerStateMachine( 2256): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 48
I/KLMS-2.4.503: ( 7879): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/libprocessgroup(  890): failed to kill 1 processes for processgroup 7667
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3748): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3748): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
I/DBG_DM  ( 3748): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3748): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
I/DBG_DM  ( 3748): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/SurfaceFlinger(  257): id=17 createSurf (1080x1920),2 flag=404, com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/art     (  890): Explicit concurrent mark sweep GC freed 27010(2MB) AllocSpace objects, 67(1072KB) LOS objects, 30% free, 35MB/51MB, paused 1.597ms total 134.897ms
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/art     (  890): WaitForGcToComplete blocked for 85.842ms for cause Explicit
I/KLMS-2.4.503: ( 7879): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1454442077112
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/KLMS-2.4.503: ( 7879): MainReciver(): PACKAGE_REMOVED
D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
D/SurfaceWidgetView( 1500): destroyHardwareResources():548993207
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager(  890): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  890): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/KLMS-2.4.503: ( 7879): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/Launcher( 1500): onRestart, Launcher: 121110045
D/Launcher( 1500): onStart, Launcher: 121110045
D/Launcher.HomeView( 1500): onStart
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2183): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/Launcher.HomeView( 1500): onStop
D/SurfaceWidget.Renderer( 2183): [237392/6] SurfaceWidget drawing first frame
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/SurfaceFlinger(  257): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (4/8)
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
I/SurfaceFlinger(  257): id=17 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
I/SurfaceFlinger(  257): id=18 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/LockPatternUtilsCache( 1185): value : false
D/StatusBarManagerService(  890): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/Timeline( 3748): Timeline: Activity_idle id: android.os.BinderProxy@2eabf31f time:1422702
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/RegisteredServicesCache( 1472): empty dynamic service
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  890): Got RemoteException sending setActive(false) notification to pid 7667 uid 10191
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{370364e7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t7} time:1422781
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
E/Zygote  ( 8325): MountEmulatedStorage()
I/libpersona( 8325): KNOX_SDCARD checking this for 10103
E/Zygote  ( 8325): v2
I/libpersona( 8325): KNOX_SDCARD not a persona
D/RCPManagerService(  890): PackageReceiver onReceive()
I/HarmonyEASService(  890): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  890): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8325 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/art     (  890): Explicit concurrent mark sweep GC freed 10429(522KB) AllocSpace objects, 0(0B) LOS objects, 30% free, 35MB/51MB, paused 3.896ms total 201.320ms
D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  890): uID is 10191
V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
I/SELinux ( 8325): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TaskPersister(  890): removeObsoleteFile: deleting file=11_task.xml
D/TaskPersister(  890): removeObsoleteFile: deleting file=9_task.xml
I/SELinux ( 8325): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8325): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/StatusBar( 1185): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1185): Icon Only
D/LockPatternUtilsCache( 1185): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1185): value : false
D/PanelView( 1185): There is/are notification(s) 
D/PanelView( 1185): There is/are notification(s) 
D/PackageManager(  890): delete codoeFile: 
D/PackageManager(  890): result of delete: 1{899858726}
D/TimaKeyStoreProvider( 8325): TimaSignature is unavailable
D/ActivityThread( 8325): Added TimaKeyStore provider
D/AndroidRuntime( 8294): Shutting down VM
D/ResourcesManager( 8325): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/elm:14451( 8325): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8325): ELMEngine.ELMEngine( context ).
D/elm:14451( 8325): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8325): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/elm:14451( 8325): ElmAgentService : onCreate()
D/elm:14451( 8325): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14451( 8325): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8325): MDMBridge.getInstance()
D/elm:14451( 8325): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14451( 8325): MDMBridge.getAllLicenseInfoFromSDK()
E/Zygote  ( 8343): MountEmulatedStorage()
E/Zygote  ( 8343): v2
I/libpersona( 8343): KNOX_SDCARD checking this for 10016
I/libpersona( 8343): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8343 uid=10016 gids={50016, 9997} abi=armeabi-v7a
I/art     (  319): Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 274us total 12.836ms
I/SELinux ( 8343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.980ms
I/SELinux ( 8343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8343): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 257us total 7.817ms
D/elm:14451( 8325): ElmAgentService : onDestroy().
I/ActivityManager(  890): Killing 7252:com.sec.android.app.soundalive/u0a57 (adj 15): bgCount ##41
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/TimaKeyStoreProvider( 8343): TimaSignature is unavailable
D/ActivityThread( 8343): Added TimaKeyStore provider
D/ResourcesManager( 8343): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8343): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8343): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8343): onReceive() : package name is not s health. Return !!!
I/PCWCLIENTTRACE_PushUtil( 7093): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 7093): sales region : global
I/PCWCLIENTTRACE_PushUtil( 7093): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 7093): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8361): MountEmulatedStorage()
E/Zygote  ( 8361): v2
I/libpersona( 8361): KNOX_SDCARD checking this for 10033
I/libpersona( 8361): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8361 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  890): Killing 6156:com.samsung.android.app.assistantmenu/1000 (adj 15): bgCount ##41
I/SELinux ( 8361): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  890): failed to open /acct/uid_10057/pid_7252/cgroup.procs: No such file or directory
I/SELinux ( 8361): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8361): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8361): TimaSignature is unavailable
D/ActivityThread( 8361): Added TimaKeyStore provider
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
I/FeatureConfig( 8361): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6156/cgroup.procs: No such file or directory
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/ResourcesManager( 8361): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 8361): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 8361): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 8361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 8361): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/ResourcesManager( 8361): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 8361): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8361): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 8361): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk

```
