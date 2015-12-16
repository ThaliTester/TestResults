#### Test 506502783fcf234_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
D/AndroidRuntime( 7154): 
D/AndroidRuntime( 7154): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7154): CheckJNI is OFF
D/AndroidRuntime( 7154): readGMSProperty: start
D/AndroidRuntime( 7154): readGMSProperty: already setted!!
D/AndroidRuntime( 7154): readGMSProperty: end
D/AndroidRuntime( 7154): addProductProperty: start
E/AffinityControl( 7154): AffinityControl: registerfunction enter
D/AndroidRuntime( 7154): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  904): inState():  stateMachine is null !!
I/PersonaManagerService(  904): PersonaId don't exist
I/ActivityManager(  904): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy(  904): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  904): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ActivityManager(  904): mDVFSHelper.acquire()
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
I/ActivityManager(  904): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7169 uid=10295 gids={50295, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7154): Shutting down VM
E/Zygote  ( 7169): MountEmulatedStorage()
E/Zygote  ( 7169): v2
I/libpersona( 7169): KNOX_SDCARD checking this for 10295
I/libpersona( 7169): KNOX_SDCARD not a persona
I/SELinux ( 7169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7169): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7169): TimaSignature is unavailable
D/ActivityThread( 7169): Added TimaKeyStore provider
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (5/8)
I/SurfaceFlinger(  254): id=11 Removed YUIInstallC (-2/8)
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ResourcesManager( 7169): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
V/ActivityThread( 3687): updateVisibility : ActivityRecord{ebf68ff token=android.os.BinderProxy@cf05cd4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
,I/WebViewFactory( 7169): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
D/ResourcesManager( 7169): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
I/LibraryLoader( 7169): Loading: webviewchromium
I/LibraryLoader( 7169): Time to load native libraries: 6 ms (timestamps 3549-3555)
I/LibraryLoader( 7169): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7169): Binding Chromium to main looper Looper (main, tid 1) {41a2ccb}
I/LibraryLoader( 7169): Expected native library version number "",actual native library version number ""
I/chromium( 7169): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7169): Initializing chromium process, renderers=0
W/art     ( 7169): Attempt to remove local handle scope entry from IRT, ignoring
W/chromium( 7169): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 7169): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46780 len=2953
I/chromium( 7169): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229536 len:643667
I/Adreno-EGL( 7169): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7169): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7169): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7169): Local Branch: mybranch5813579
I/Adreno-EGL( 7169): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7169): Local Patches: NONE
I/Adreno-EGL( 7169): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
W/chromium( 7169): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 7169): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/ActivityManager(  904): Activity pause timeout for ActivityRecord{145450e8 u0 com.test.thalitest/.MainActivity t4}
W/art     ( 7169): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 7169): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 7169): CordovaWebView is running on device made by: samsung
W/art     ( 7169): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 7169): Attempt to remove local handle scope entry from IRT, ignoring
D/Activity( 7169): performCreate Call secproduct feature valuefalse
D/Activity( 7169): performCreate Call debug elastic valuetrue
D/OpenGLRenderer( 7169): Render dirty regions requested: true
D/Atlas   ( 7169): Validating map...
D/ActivityManager(  904): post active user change for 0
D/KnoxTimeoutHandler(  904): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  904): handleActiveUserChange for user 0
V/ActivityThread( 7169): updateVisibility : ActivityRecord{3dd4ffd8 token=android.os.BinderProxy@3dc72f4a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
I/SurfaceFlinger(  254): id=15 createSurf (1x1),1 flag=404, NainActivit
D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
I/OpenGLRenderer( 7169): Initialized EGL, version 1.4
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
I/OpenGLRenderer( 7169): HWUI protection enabled for context ,  &this =0xb3a5eab0 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 7169): Enabling debug mode 0
D/InputMethodManagerService(  904): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/ActivityManager(  904): mDVFSHelper.release()
I/Timeline(  904): Timeline: Activity_windows_visible id: ActivityRecord{145450e8 u0 com.test.thalitest/.MainActivity t4} time:154097
W/IInputConnectionWrapper( 7169): showStatusIcon on inactive InputConnection
I/Timeline( 7169): Timeline: Activity_idle id: android.os.BinderProxy@3dc72f4a time:154103
I/chromium( 7169): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 7169): 
D/JsMessageQueue( 7169): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 7169): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1357820800
,D/JX-Cordova( 7169): jxcore cordova android initializing
,E/SMD     (  293): DCD ON
,W/jxcore-log( 7169): Initializing JXcore engine
W/jxcore-log( 7169): JXcore engine is ready
,W/jxcore-log( 7169): Starting JXcore engine
,E/auditd  ( 1814): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  904): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  904): audit.ondenial set to 0 after sending android.intent.action.DENIAL_NOTIFICATION intent
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7248 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 7248): MountEmulatedStorage()
E/Zygote  ( 7248): v2
I/libpersona( 7248): KNOX_SDCARD checking this for 1000
I/libpersona( 7248): KNOX_SDCARD not a persona
,I/SELinux ( 7248): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7248): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7248): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7248): TimaSignature is unavailable
,D/ActivityThread( 7248): Added TimaKeyStore provider
,D/ResourcesManager( 7248): creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,W/jxcore-log( 7169): Platform android
W/jxcore-log( 7169): 
W/jxcore-log( 7169): Process ARCH arm
W/jxcore-log( 7169): 
,D/SecurityLogAgent( 7248):  SeDenialReceiver : Intent Received : android.intent.action.DENIAL_NOTIFICATION
,D/SecurityLogAgent( 7248):  SeDenialReceiver : File path = null
,I/ActivityManager(  904): Killing 5691:com.sec.providers.settingsearch/u0a191 (adj 15): bgCount ##41
,I/jxcore-log( 7169): JXcore Cordova bridge is ready!
I/jxcore-log( 7169): 
W/jxcore-log( 7169): JXcore engine is started
,I/Choreographer( 7169): Skipped 144 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 7169): Toggling radios to true
I/jxcore-log( 7169): 
,D/BluetoothAdapter( 7169): enable()
,D/BluetoothAdapter( 7169): enable(): BT is already enabled..!
,I/WifiManager( 7169): packageName : com.test.thalitest
,D/SecContentProvider(  904): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  904): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  904): mCursor = null
,D/WifiService(  904): setWifiEnabled: true pid=7169, uid=10295
,W/ActivityManager(  904): Permission Denial: getCurrentUser() from pid=7169, uid=10295 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService(  904): Failed getting userId using ActivityManagerNative
W/WifiService(  904): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7169, uid=10295 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService(  904): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23057)
W/WifiService(  904): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2181)
W/WifiService(  904): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2169)
W/WifiService(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService(  904): 	at android.os.Binder.execTransact(Binder.java:446)
,D/SettingsProvider(  904): name = wifi_on
,I/WifiService(  904): disconnect: pid=7169, uid=10295
,I/wpa_supplicant( 1278): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7169): Radios toggled
I/jxcore-log( 7169): 
,I/jxcore-log( 7169): Got Device Bluetooth address: E0:DB:10:1F:C9:5E
I/jxcore-log( 7169): 
,I/wpa_supplicant( 1278): CTRL-EVENT-DISCONNECTED bssid=C0.AA.4A reason=3 locally_generated=1
,I/jxcore-log( 7169): Perf Test app loaded loaded
I/jxcore-log( 7169): 
,I/wpa_supplicant( 1278): wlan0: State: COMPLETED -> DISCONNECTED
,I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  904): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1278): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): Disconnected - do not scan
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,I/chromium( 7169): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7169): check test folder
I/jxcore-log( 7169): 
,I/jxcore-log( 7169): found test : ./testFindPeers.js
I/jxcore-log( 7169): 
,E/native  (  904): do suspend true
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,D/CommandListener(  288): Clearing all IP addresses on wlan0
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,I/jxcore-log( 7169): found test : ./testSendData.js
I/jxcore-log( 7169): 
,V/NativeCrypto( 1902): Read error: ssl=0x9b64ae00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1902): SSL shutdown failed: ssl=0x9b64ae00: I/O error during system call, Broken pipe
,E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetUtils(  904): android_net_utils_resetConnections in env=0xa93ac320 clazz=0x9be1198c iface=wlan0 mask=0x3
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
,E/WifiStateMachine(  904): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 1278): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1278): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1278): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1278): First Scan Start
,E/native  (  904): do suspend true
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Checking http://clients3.google.com/generate_204 on <unknown ssid>
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid (  904): Tagging socket 387 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 904, getuid(): 1000
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Validated
,E/Zygote  ( 7283): MountEmulatedStorage()
E/Zygote  ( 7283): v2
I/libpersona( 7283): KNOX_SDCARD checking this for 10038
I/libpersona( 7283): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7283 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/wpa_supplicant( 1278): Scan requested (ret=0) - scan timeout 30 seconds
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,I/SELinux ( 7283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
D/CommandListener(  288): Clearing all IP addresses on wlan0
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,I/SELinux ( 7283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7283): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/WifiNetworkAgent(  904): NetworkAgent: NetworkAgent channel lost
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  904): mCursor = null
,D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  904): mCursor = null
,D/TimaKeyStoreProvider( 7283): TimaSignature is unavailable
,D/ActivityThread( 7283): Added TimaKeyStore provider
,E/SMD     (  293): DCD ON
,D/ResourcesManager( 7283): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7283): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ConnectivityService(  904): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  904): calling update connectivity
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/EntConnectivity(  904): Not allowed due to - mEnabled false
D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524292
,V/Nat464Xlat(  904): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  904): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1423): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  904): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 2177): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  904): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Disconnected - quitting
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  904): MasterInitialState.processMessage what=3
,V/NetworkStats(  904): updateIfacesLocked()
,V/NetworkStats(  904): performPollLocked(flags=0x1)
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  904): UpdateStatsForKnox
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): performPollLocked() took 4ms
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
E/ConnectivityService(  904): EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,I/chromium( 7169): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1423): FileWriteThread : threadType = 3
,I/VlingoApplication( 7283): VlingoApplication appVersion ='11.2.2.0.37649', ro.csc.sales_code=XEO
,E/BluetoothHeadset( 7283): BTStateChangeCB is registed
,E/BluetoothHeadset( 7283): BluetoothHeadset service is binded
,I/ActivityManager(  904): Killing 5496:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): bgCount ##41
,I/Hs20UtilService( 1319): Starting #6
,I/Hs20UtilService( 1319): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SettingsProvider(  904): name = driving_mode_on
D/SettingsProvider(  904): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  904): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  904): selectionArgs: false
D/SettingsProvider(  904): selectionArgs: 10038
,D/SecContentProvider(  904): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  904): ret = -1
,D/BluetoothManager( 7283): [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,I/Hs20UtilService( 1319): Starting #7
,I/Hs20UtilService( 1319): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1319): MountReceiver.mPrefHandler - 7002
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  904): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE,
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ApplicationPolicy(  904): updateDataUsageMap
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5877): type=WIFI subType= reason=null isConnected=false
,I/DBG_DM  ( 3687): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3687): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,I/PCWCLIENTTRACE_PushUtil( 6631): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6631): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6631): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): noConnectivity : true
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7332): MountEmulatedStorage()
E/Zygote  ( 7332): v2
I/libpersona( 7332): KNOX_SDCARD checking this for 10004
I/libpersona( 7332): KNOX_SDCARD not a persona
,I/SELinux ( 7332): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7332): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7332): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  904): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7332 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PowerManagerService(  904): [PWL] Off : 50s ago
,I/PowerManagerService(  904): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  904): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  904): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=904, ws=null) (elapsedTime=689)
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7332): TimaSignature is unavailable
D/ActivityThread( 7332): Added TimaKeyStore provider
,D/ResourcesManager( 7332): creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,D/SSRM:n  (  904): SIOP:: AP = 340, PST = 336, CUR = 450
,I/ActivityManager(  904): Killing 4720:com.android.calendar/u0a172 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7349): MountEmulatedStorage()
E/Zygote  ( 7349): v2
I/libpersona( 7349): KNOX_SDCARD checking this for 1000
I/libpersona( 7349): KNOX_SDCARD not a persona
I/ActivityManager(  904): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7349 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 7349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7349): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7349): TimaSignature is unavailable
D/ActivityThread( 7349): Added TimaKeyStore provider
D/ResourcesManager( 7349): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
I/DIAGMON_AGENT( 7349): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
I/DIAGMON_AGENT( 7349): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
I/wpa_supplicant( 1278): nl80211: Received scan results (11 BSSes)
I/wpa_supplicant( 1278): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1278): Trying to associate with C0.AA.4A (SSID='4E473730303567' freq=5220 MHz)
I/wpa_supplicant( 1278): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E473730303567
I/ServiceManager(  333): Waiting for service AtCmdFwd...
D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
I/wpa_supplicant( 1278): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E473730303567
I/wpa_supplicant( 1278): Associated with C0.AA.4A
I/DIAGMON_AGENT( 7349): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
I/DIAGMON_AGENT( 7349): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 7349): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
I/DIAGMON_AGENT( 7349): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/wpa_supplicant( 1278): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.4A SSID=4E473730303567
D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1278): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.4A SSID=4E473730303567
I/wpa_supplicant( 1278): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:4a [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 1278): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1278): CTRL-EVENT-CONNECTED - Connection to C0.AA.4A completed (auth) [id=0 id_str=]
I/wpa_supplicant( 1278): Blacklist: Clear (temp) 
I/wpa_supplicant( 1278): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.4A SSID=4E473730303567
D/WifiNative-HAL(  904): callSECApiVoid - ID [50]
D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService(  904): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/ConnectivityService(  904): Got NetworkAgent Messenger
D/ConnectivityService(  904): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904): NetworkAgent connected
E/WifiConfigStore(  904): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  288): Setting iface cfg
E/WifiStateMachine(  904): Start Dhcp Watchdog 2
D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2(  904): mCursor = null
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 7367): MountEmulatedStorage()
E/Zygote  ( 7367): v2
I/libpersona( 7367): KNOX_SDCARD checking this for 10014
I/libpersona( 7367): KNOX_SDCARD not a persona
I/SELinux ( 7367): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
E/native  (  904): do suspend false
I/SELinux ( 7367): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7367): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  904): uri = 20 selection = getPromptCredentialsEnabled
D/WifiP2pService(  904): InactiveState{ what=143375 }
D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
D/SecContentProvider2(  904): mCursor = null
I/ActivityManager(  904): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7367 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 7367): TimaSignature is unavailable
D/ActivityThread( 7367): Added TimaKeyStore provider
D/ResourcesManager( 7367): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/ActivityManager(  904): Killing 5727:com.google.android.talk/u0a131 (adj 15): bgCount ##41
,I/FOTA_Client( 7367): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7367): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7367): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,I/ActivityManager(  904): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7383 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 5795:com.android.providers.calendar/u0a51 (adj 15): bgCount ##41
,E/Zygote  ( 7383): MountEmulatedStorage()
,E/Zygote  ( 7383): v2
,I/libpersona( 7383): KNOX_SDCARD checking this for 10023
I/libpersona( 7383): KNOX_SDCARD not a persona
,E/dhcpcd  ( 7382): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/dhcpcd  ( 7382): version 5.5.6 starting
,E/dhcpcd  ( 7382): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/SELinux ( 7383): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7383): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7383): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7383): TimaSignature is unavailable
,D/ActivityThread( 7383): Added TimaKeyStore provider
,D/ResourcesManager( 7383): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
,I/dhcpcd  ( 7382): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 7382): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 7382): if(wlan0) info get Success. (MAC : C0.AA.4A)
I/dhcpcd  ( 7382): bssid match
,I/dhcpcd  ( 7382): wlan0: rebinding lease of 192.168.1.128
,I/KLMS-2.4.511: ( 7383): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.4.511: ( 7383): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238318083
I/KLMS-2.4.511: ( 7383): MainReciver(): NETWORK_STATE_CHANGED_ACTION
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/KLMS-2.4.511: ( 7383): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
I/KLMS-2.4.511: ( 7383): StateImplV2(): networkChangeListener().END
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7409): MountEmulatedStorage()
E/Zygote  ( 7409): v2
I/libpersona( 7409): KNOX_SDCARD checking this for 10036
I/libpersona( 7409): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7409 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 5656:com.google.android.gm/u0a128 (adj 15): bgCount ##41
,I/SELinux ( 7409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7409): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7409): TimaSignature is unavailable
,D/ActivityThread( 7409): Added TimaKeyStore provider
,D/ResourcesManager( 7409): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,W/ResourcesManager( 7409): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7409): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Minikin ( 7409): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  904): Killing 5926:com.sec.android.app.music:service/u0a49 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7427): MountEmulatedStorage()
E/Zygote  ( 7427): v2
I/libpersona( 7427): KNOX_SDCARD checking this for 10042
I/libpersona( 7427): KNOX_SDCARD not a persona
,I/SELinux ( 7427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ActivityManager(  904): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7427 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 7427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  326): Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 4.726ms total 22.957ms
,D/TimaKeyStoreProvider( 7427): TimaSignature is unavailable
,D/ActivityThread( 7427): Added TimaKeyStore provider
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 394us total 13.680ms
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/art     (  326): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 396us total 13.386ms
,D/ResourcesManager( 7427): creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,I/SO_AGENT( 7427): [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5110): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6717): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6717): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,I/SA      ( 6717): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6717): [SLFUCHKMGR] constructor called
,E/SPPClientService( 5110): [[SystemStateMonitorService]] No Active Internet
,I/SA      ( 6717): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6717): [OR] == isSIMCardReady false ==
,I/SA      ( 6717): [SCU] == networkStateCheck == false
I/SA      ( 6717): [OR] onReceive END
,I/ActivityManager(  904): Killing 5997:com.sec.android.app.myfiles/u0a56 (adj 15): bgCount ##41
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7444): MountEmulatedStorage()
I/libpersona( 7444): KNOX_SDCARD checking this for 10074
E/Zygote  ( 7444): v2
I/libpersona( 7444): KNOX_SDCARD not a persona
,I/SELinux ( 7444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7444): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  904): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7444 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7444): TimaSignature is unavailable
,D/ActivityThread( 7444): Added TimaKeyStore provider
,D/ResourcesManager( 7444): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,I/sCloudBackupApp( 7444): sCloudBackupApp Version Info : 3.13.7.KK_APP
I/SCloudBackupReceiver( 7444): Other Intent
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7460): MountEmulatedStorage()
E/Zygote  ( 7460): v2
I/libpersona( 7460): KNOX_SDCARD checking this for 1000
I/libpersona( 7460): KNOX_SDCARD not a persona
,I/SELinux ( 7460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  904): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.knoxusage.KnoxUsageReceiver: pid=7460 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6357:flipboard.app/u0a125 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7460): TimaSignature is unavailable
,D/ActivityThread( 7460): Added TimaKeyStore provider
,D/ResourcesManager( 7460): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 7460): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KnoxUsageLogPro( 7460): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7460): premStatus:2
,I/KnoxUsageLogPro( 7460): isEulaShown : false
I/KnoxUsageLogPro( 7460): KnoxUsageReceiver onReceive : not Processible, just return
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7476): MountEmulatedStorage()
E/Zygote  ( 7476): v2
I/libpersona( 7476): KNOX_SDCARD checking this for 10104
I/libpersona( 7476): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7476 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7476): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7476): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7476): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  904): Killing 6497:com.google.android.gms:car/u0a15 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7476): TimaSignature is unavailable
,D/ActivityThread( 7476): Added TimaKeyStore provider
,E/SMD     (  293): DCD ON
,D/ResourcesManager( 7476): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/dhcpcd  ( 7382): wlan0: acknowledged 192.168.1.128 from 192.168.1.1
,I/dhcpcd  ( 7382): wlan0: leased 192.168.1.128 for 86400 seconds
,D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7497): MountEmulatedStorage()
,E/Zygote  ( 7497): v2
I/ActivityManager(  904): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7497 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 7497): KNOX_SDCARD checking this for 10146
I/libpersona( 7497): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Killing 6478:com.android.defcontainer/u0a7 (adj 15): bgCount ##41
,I/SELinux ( 7497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7497): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7497): TimaSignature is unavailable
,D/ActivityThread( 7497): Added TimaKeyStore provider
,D/ResourcesManager( 7497): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  253): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  253): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7497): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/native  (  904): do suspend true
,D/WifiP2pService(  904): InactiveState{ what=143375 }
,D/WifiP2pService(  904): P2pEnabledState{ what=143375 }
,D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,E/WifiStateMachine(  904): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG7005g"WPA_PSK
E/WifiStateMachine(  904): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,D/WifiNative-HAL(  904): callSECApiInt - ID [210]
,E/ConnectivityService(  904): updateNetworkInfo()
,D/ConnectivityService(  904): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/ConnectivityService(  904): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine(  904): updateDnsLinkProperty: enter
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/WifiWatchdogStateMachine.DnsPinger(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver(  904): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,E/WifiStateMachine(  904): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1183): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020535/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020152/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:null
,I/WifiTrafficPoller(  904): evaluateTrafficStatsPolling
,I/WifiTrafficPoller(  904): mBoosterFLAG : 0
I/WifiTrafficPoller(  904): current booster mode : FullMode
D/WifiNative-HAL(  904): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,E/WifiStateMachine(  904): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/StatusBar.NetworkController( 1183): applyOpen
,D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1183): applyOpen
,D/ConnectivityService(  904): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService(  904): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService(  904): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 503
,E/ConnectivityService(  904): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  904): updateSourceRoutes : add source routing for type : 1
D/ConnectivityService(  904): updateSourceRoutes : add src route for:192.168.1.128
,V/        (  288): QcRouteController
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,I/WebViewFactory( 7497): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,D/ResourcesManager( 7497): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/LibraryLoader( 7497): Loading: webviewchromium
,I/LibraryLoader( 7497): Time to load native libraries: 6 ms (timestamps 1941-1947)
,V/        (  288): QcRouteController
I/LibraryLoader( 7497): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7497): Binding Chromium to main looper Looper (main, tid 1) {f195369}
,I/LibraryLoader( 7497): Expected native library version number "",actual native library version number ""
,I/chromium( 7497): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,V/        (  288): QcRouteController
,V/        (  288): QcRouteController
,I/BrowserStartupController( 7497): Initializing chromium process, renderers=0
,W/art     ( 7497): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 7497): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 7497): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=41 off=46780 len=2953
,I/chromium( 7497): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:42 off:229536 len:643667
,V/        (  288): QcRouteController
,W/AudioManagerAndroid( 7497): Requires BLUETOOTH permission
,I/Adreno-EGL( 7497): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
I/Adreno-EGL( 7497): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 7497): Build Date: 11/19/14 Wed
I/Adreno-EGL( 7497): Local Branch: mybranch5813579
I/Adreno-EGL( 7497): Remote Branch: quic/LA.BF.1.1_rb1.11
I/Adreno-EGL( 7497): Local Patches: NONE
I/Adreno-EGL( 7497): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,D/ConnectivityService(  904): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService(  904): LTETest block dns file not exists
,V/Nat464Xlat(  904): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
,E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = CONNECTING
E/ConnectivityService(  904): updateNetworkInfo()
D/ConnectivityService(  904): ignoring duplicate network state non-change. WIFI, state = CONNECTING
D/ConnectivityService(  904): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
,D/EntConnectivity(  904): Not allowed due to - mEnabled false
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Checking http://clients3.google.com/generate_204 on "NG7005g"
,I/System.out(  904): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  904): currentScore = 0, newScore = 60
D/ConnectivityService(  904):    accepting network in place of null
D/ConnectivityService(  904): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory( 1423): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker(  904): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  904): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  904): MasterInitialState.processMessage what=3
D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): updateIfacesLocked()
V/NetworkStats(  904): performPollLocked(flags=0x1)
,D/NetworkStatsFactory(  904): UpdateStatsForKnox
D/ConnectivityService(  904): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/ConnectivityService(  904): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
V/NetworkStats(  904): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,V/NetworkStats(  904): performPollLocked() took 6ms
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
,D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/EntConnectivity(  904): Not allowed due to - mEnabled false
,D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/ConnectivityService(  904): Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=true
D/ConnectivityService(  904): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.128/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService(  904): identical MTU - not setting
D/ConnectivityService(  904): updateSourceRoutes : add source routing for type : 1
D/ConnectivityManager.CallbackHandler( 2177): CM callback handler got msg 524290
D/ConnectivityService(  904): updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,V/        (  288): QcRouteController
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
D/StatusBar.NetworkController( 1183): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1183): applyOpen
,V/        (  288): QcRouteController
W/NetworkManagementService(  904): route cmd failed: 
W/NetworkManagementService(  904): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '73 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 73 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
W/NetworkManagementService(  904): '
W/NetworkManagementService(  904): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
W/NetworkManagementService(  904): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
W/NetworkManagementService(  904): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
W/NetworkManagementService(  904): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
W/NetworkManagementService(  904): 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2812)
W/NetworkManagementService(  904): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5625)
W/NetworkManagementService(  904): 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5437)
W/NetworkManagementService(  904): 	at com.android.server.ConnectivityService.access$2300(ConnectivityService.java:229)
W/NetworkManagementService(  904): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2382)
W/NetworkManagementService(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  904): 	at android.os.Looper.loop(Looper.java:145)
W/NetworkManagementService(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/Nat464Xlat(  904): requiresClat: netType=1, connected=true, hasIPv4Address=true
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/NtpTrustedTime(  904): currentTimeMillis() cache hit
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 2177): CM callback handler got msg 524295
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524295
D/ConnectivityService(  904): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2177): CM callback handler got msg 524295
,I/System.out(  904): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/NSApplication( 7497): Starting up...
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 16 Dec 2015 03:58:40 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1450238320166], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1450238320148]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  904): Validated
D/ConnectivityService(  904): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService(  904): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService(  904): calling update connectivity
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  904):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1183): CM callback handler got msg 524290
D/ConnectivityService(  904): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2177): CM callback handler got msg 524290
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1183): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1183): updateDataNetType()
D/StatusBar.NetworkController( 1183): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1183): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1183): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1183): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1183): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG7005g"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG7005g"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020532/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014a/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020501/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1183): onWifiSignalChanged enabled=true enabledDesc:"NG7005g"
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  904): Killing 6596:com.google.android.partnersetup/u0a19 (adj 15): bgCount ##41
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7593): MountEmulatedStorage()
E/Zygote  ( 7593): v2
I/libpersona( 7593): KNOX_SDCARD checking this for 10158
I/libpersona( 7593): KNOX_SDCARD not a persona
,I/SELinux ( 7593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,I/ActivityManager(  904): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7593 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 7593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7593): TimaSignature is unavailable
,D/ActivityThread( 7593): Added TimaKeyStore provider
,D/ResourcesManager( 7593): creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,W/ResourcesManager( 7593): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7593): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 7593): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 7593): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7593): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 7593): PeriphStartReceiver.onReceive - no need to start
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7608): MountEmulatedStorage()
,E/Zygote  ( 7608): v2
I/libpersona( 7608): KNOX_SDCARD checking this for 10186
I/libpersona( 7608): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7608 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/ActivityManager(  904): Killing 6614:com.samsung.groupcast/u0a20 (adj 15): bgCount ##41
,I/SELinux ( 7608): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
I/SELinux ( 7608): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7608): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7608): TimaSignature is unavailable
,D/ActivityThread( 7608): Added TimaKeyStore provider
,D/ResourcesManager( 7608): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 7608): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7608): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7608): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7608): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ConnectivityService(  904): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  904): SmartBondingReceiver: wifi is connected
D/SmartBondingService(  904): SmartBondingReceiver: wifi ap is not changed
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
D/SmartBondingService(  904): getSBEnabled() enabled =false
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  904): getNetworkEnabled : wifi : true mobile : true
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl( 1883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 com.samsung.SMT.ai.onReceive:-1 
W/ContextImpl( 1883): Implicit intents with startService are not safe: Intent { act=com.samsung.SMT.UpdateManager.UPDATE_DATA } android.content.ContextWrapper.startService:533 com.samsung.SMT.SamsungTTSService.d:-1 com.samsung.SMT.SamsungTTSService.a:-1 
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  904): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3687): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3687): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NetworkMonitor( 5877): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  904): Explicit concurrent mark sweep GC freed 106851(6MB) AllocSpace objects, 29(512KB) LOS objects, 17% free, 37MB/45MB, paused 1.471ms total 120.956ms
D/SecContentProvider2(  904): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  904): mCursor = null
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 6761): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,I/jxcore-log( 7169): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7169): 
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BadgeProvider( 6761): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 1442): reloadBadges entered.
,D/BadgeProvider( 6761): sendNotify, [notify] : null
D/BadgeProvider( 6761): update, [uri] : content://com.sec.badge/apps/1
D/SecurityLogAgent( 7248): KnoxConfiguration : Current State = 1
D/BadgeProvider( 6761): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6761): update, [UpdateCount] : 1
,D/SecurityLogAgent( 7248): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7248): StateMachine : Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7248): StateMachine : Changed Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7643): MountEmulatedStorage()
E/Zygote  ( 7643): v2
I/libpersona( 7643): KNOX_SDCARD checking this for 10200
I/libpersona( 7643): KNOX_SDCARD not a persona
,I/ActivityManager(  904): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=7643 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ConnectivityService(  904): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/ActivityManager(  904): Killing 6112:sstream.app/u0a25 (adj 15): bgCount ##41
,I/SELinux ( 7643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
,I/SELinux ( 7643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7643): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7643): TimaSignature is unavailable
,D/ActivityThread( 7643): Added TimaKeyStore provider
,D/ResourcesManager( 7643): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,W/ActivityManager(  904): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/PackageManager(  904): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/ActivityManager(  904): Killing 6155:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): bgCount ##41
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5473): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5473): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5473): exit::IDLE
D/InitializeManagerStateMachine( 5473): entry::NETWORK_CHECK
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5473): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5473): exit::NETWORK_CHECK
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5473): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5473): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5473): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5473): entry::SUCCESS
D/hcjo    ( 5473): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5473): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5473): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5473): exit::SUCCESS
D/InitializeManagerStateMachine( 5473): entry::IDLE
,I/Hs20UtilService( 1319): Starting #8
,I/Hs20UtilService( 1319): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1319): Starting #9
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 1319): Message received 5007
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1319): Starting #10
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1319): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 1319): Message received 5007
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1319): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,I/Hs20UtilService( 1319): Starting #11
,I/Hs20UtilService( 1319): Message received 5007
,D/NearbySettings( 1319): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1319): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine(  904): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SignOutReceiver( 6936): NETWORK_STATE_CHANGED_ACTION
,I/PCWCLIENTTRACE_PushUtil( 6631): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6631): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6631): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/SurfaceFlinger(  254): id=16 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService(  904): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=904
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,I/DIAGMON_AGENT( 7349): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 7349): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/FOTA_Client( 7367): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,I/FOTA_Client( 7367): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,I/FOTA_Client( 7367): [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,I/KLMS-2.4.511: ( 7383): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.4.511: ( 7383): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450238321689
,I/KLMS-2.4.511: ( 7383): MainReciver(): NETWORK_STATE_CHANGED_ACTION
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/KLMS-2.4.511: ( 7383): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,I/KLMS-2.4.511: ( 7383): StateImplV2(): networkChangeListener().START
,I/KLMS-2.4.511: ( 7383): NetworkChangeOperations(): uploadRequestLog().START 
,I/KLMS-2.4.511: ( 7383): StateImplV2(): networkChangeListener().END
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SO_AGENT( 7427): [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SPPClientService( 5110): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6717): [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOB6 PSS = 5.701607447389803  ]
,I/SA      ( 6717): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,I/SA      ( 6717): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6717): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 6717): [OR] == isSIMCardReady false ==
I/SA      ( 6717): [SCU] == networkStateCheck == true
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SA      ( 6717): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6717): isChinaCountryCode : false
I/SA      ( 6717): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6717): [OR] == networkStateCheck true ==
,I/SA      ( 6717): [OR] GetMyCountryZoneTask
,I/SA      ( 6717): [OR] onReceive END
,I/SA      ( 6717): [SRS] prepareGetMyCountryZone
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6717): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6717): [SSP] query invoked
,I/SCloudBackupReceiver( 7444): Other Intent
,I/KnoxUsageLogPro( 7460): KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,I/KnoxUsageLogPro( 7460): premStatus:2
,I/KnoxUsageLogPro( 7460): isEulaShown : false
,I/KnoxUsageLogPro( 7460): KnoxUsageReceiver onReceive : not Processible, just return
,I/SA      ( 6717): [TPMU] GetMccFromDB : null
I/SA      ( 6717): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6717): [TPM] isNoProxy(default) : true
,E/File    ( 6717): fail readDirectory() errno=2
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/QuickConnect( 7593): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 7593): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 7593): PeriphStartReceiver.onReceive - no need to start
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/RCPManagerService(  904): exchangeData() failure , invalid userId
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7248): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 7248): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 7248): StateMachine : Current State = 1
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecurityLogAgent( 7248): StateMachine : Changed Current State = 1
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/hcjo    ( 5473): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5473): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5473): exit::IDLE
D/InitializeManagerStateMachine( 5473): entry::NETWORK_CHECK
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/InitializeManagerStateMachine( 5473): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5473): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5473): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5473): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5473): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5473): entry::SUCCESS
D/hcjo    ( 5473): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5473): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5473): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/InitializeManagerStateMachine( 5473): exit::SUCCESS
D/InitializeManagerStateMachine( 5473): entry::IDLE
,E/SMD     (  293): DCD ON
,I/dhcpcd  ( 7382): wlan0: sending IPv6 Router Solicitation
,I/SA      ( 6717): [RC New] Execute method=[GET] start
,I/SA      ( 6717): [RC New] Security=[true]
,I/System.out( 6717): Thread-1120(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6717): Thread-1120(ApacheHTTPLog):isShipBuild true
,I/System.out( 6717): Thread-1120(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,E/WifiStateMachine(  904): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 6717): [RC New] [v2liruge] api execute + 722
,I/SA      ( 6717): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6717): AsyncTask #1 calls detatch()
,I/SA      ( 6717): [TPMU] getNetworkMcc : 
,I/SA      ( 6717): [SCU] saveMccToPreferece Start
,I/SA      ( 6717): [SCU] RegionMCC : 260
,I/SA      ( 6717): [SSP] query invoked
,I/SA      ( 6717): [TPMU] GetMccFromDB : null
,I/SA      ( 6717): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6717): [SCU] saveMccToPreferece End
,I/SA      ( 6717): [RC New] executeRequest [v2liruge] end. 840
,I/SA      ( 6717): [RC New] Execute end
,I/SA      ( 6717): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6717): [OR] GetMyCountryZoneTask Success
,E/Watchdog(  904): !@Sync 5
,I/GAV4    ( 7497): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  254): id=16 Removed Uoast (8/9)
,D/PowerManagerService(  904): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 904) eventTime = 166966
,D/PowerManagerService(  904): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=904 (0x0)
D/PowerManagerService(  904): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=904, ws=WorkSource{10067}) (elapsedTime=3472)
,E/SMD     (  293): DCD ON
,I/dhcpcd  ( 7382): wlan0: sending IPv6 Router Solicitation
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6631): mConnectivityHandler : connected
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PCWCLIENTTRACE_AccountUtil( 6631): [hasSamungAccount] - No Samsung Account
,I/CSTORAGE( 6631): ================================================
,I/CSTORAGE( 6631):  CSTORAGE_SKM_LIB v1.0.6
I/CSTORAGE( 6631): ================================================
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6631): [GetString-S]
E/art     ( 6631): No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6631): GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6631): [GetString-E]
I/PCWCLIENTTRACE_PushUtil( 6631): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6631): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6631): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 6631): [ensureRegistration] - No Samsung account
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 330, PST = 331, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/dhcpcd  ( 7382): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 7382): wlan0: no IPv6 Routers available
,E/SMD     (  293): DCD ON
,D/PreloadUpdateManagerStateMachine( 5473): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5473): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5473): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5473): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5473): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5473): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5473): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5473): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5473): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5473): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5473): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5473): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5473): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5473): entry::IDLE
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 310, PST = 323, CUR = 450
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/PowerManagerService(  904): [PWL] Off : 75s ago
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 318, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 6
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 315, CUR = 450
,E/SMD     (  293): DCD ON
,I/ClearcutLoggerApiImpl( 1902): disconnect managed GoogleApiClient
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON,
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 312, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  904): [PWL] Off : 105s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 310, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/Watchdog(  904): !@Sync 7
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 1
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 309, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 300, PST = 308, CUR = 450
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  904): [PWL] Off : 140s ago
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 307, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 8
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 302, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 298, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 296, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 9
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 180s ago
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 295, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 294, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 293, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize(  904): initializing...
,I/TLC_TIMA_PKM_initialize(  904): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  904): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  904): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication(  904): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  904): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  904): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication(  904): max_message_size = 524416 = 0x80080
,D/QSEECOMAPI: (  904): QSEECom_get_handle sb_length = 0x80080
,D/QSEECOMAPI: (  904): App is not loaded in QSEE
,D/QSEECOMAPI: (  904): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  904): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  904): Trustlet response is completed
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/jxcore-log( 7169): Connected to the server!
I/jxcore-log( 7169): 
,I/chromium( 7169): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,E/SMD     (  293): DCD ON,
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 292, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 291, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  904): [PWL] Off : 225s ago
,V/AlarmManager(  904): waitForAlarm result :4
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,I/ActivityManager(  904): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7724 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,E/Zygote  ( 7724): MountEmulatedStorage()
D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,E/Zygote  ( 7724): v2
I/libpersona( 7724): KNOX_SDCARD checking this for 10096
I/libpersona( 7724): KNOX_SDCARD not a persona
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,I/SELinux ( 7724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
,E/SELinux ( 7724): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7724): TimaSignature is unavailable
,D/ActivityThread( 7724): Added TimaKeyStore provider
,D/ResourcesManager( 7724): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ActivityManager(  904): Killing 4577:com.sec.android.app.shealth/u0a40 (adj 15): bgCount ##41
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 11
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  904): !@Sync 12
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/PowerManagerService(  904): [PWL] Off : 275s ago
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog(  904): !@Sync 13
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 14
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService(  904): [PWL] Off : 330s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED,
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 15
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 290, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 2
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 289, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/bootchecker(  329): bootchecker wake up!!
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 288, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  904): !@Sync 16
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 390s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 287, CUR = 450
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 286, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,E/SMD     (  293): DCD ON
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 285, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate,
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 17
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 284, CUR = 450
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  333): Waiting for service AtCmdFwd...
,E/SMD     (  293): DCD ON
,W/Atfwd_Sendcmd(  333): AtCmdFwd service not published, waiting... retryCnt : 5
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog(  904): !@Sync 18
,E/SMD     (  293): DCD ON
,I/Atfwd_Sendcmd(  333): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  333): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 455s ago
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/Atfwd_Daemon(  333): Stop the daemon....
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 19
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 20
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 282, CUR = 450
,E/SMD     (  293): DCD ON
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  904): [PWL] Off : 525s ago
,E/SMD     (  293): DCD ON
,I/ActivityManager(  904): Killing 6687:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): bgCount ##41
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 290, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 21
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 22
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 23
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 600s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 283, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 282, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 281, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 24
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 25
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 680s ago
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 26
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): stay LED for fully charged
D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/LightsService(  904): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  904): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  904): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2177): Aggregate from 1450236750060 (log), 1450236750060 (data)
,D/LightsService(  904): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  904): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  904): unregisterListener ::   
D/LightsService(  904): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 27
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 28
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  904): [PWL] Off : 765s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 29
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged,
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/ConnectivityService(  904): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 31
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,I/PowerManagerService(  904): [PWL] Off : 855s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 32
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 33
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 34
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 950s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 35
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 36
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 37
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 38
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1050s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 39
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/UsageStatsService(  904): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  904): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  904): Updating Usage Statistics in DB @ 1450239371720
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
,W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  904): ::getAppControlDB: Exception to create DB
W/System.err(  904): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  904): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  904): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  904): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsage(  904): Done Updating Usage Statistics in DB @ 1450239371915
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  904): !@Sync 40
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 41
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService(  904): [PWL] Off : 1155s ago
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 42
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 43
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 44
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 45
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1265s ago
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 46
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 47
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 48
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true,
,D/BatteryService(  904): stay LED for fully charged
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/Watchdog(  904): !@Sync 49
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1380s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  904): !@Sync 50
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,D/LightsService(  904): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  904): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager(  904): registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/LightsService(  904): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  904): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager(  904): unregisterListener ::   
,D/LightsService(  904): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 51
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/Watchdog(  904): !@Sync 52
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 53
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1500s ago
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 54
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 55
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 56
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 57
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1625s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 58
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 59
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,D/NetworkStatsFactory(  904): UpdateStatsForKnox
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/TimaService(  904): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  904): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  904): TimaServiceHandler.handleMessage what =1
,E/SMD     (  293): DCD ON
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  904): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  904): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog(  904): !@Sync 60
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  904): Plugged
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :4
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,I/ProcessStatsService(  904): Prepared write state in 29ms
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1183): handleTimeUpdate
,D/KeyguardEffectViewController( 1183): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1183): *** don't update sliding image ***
,V/AlarmManager(  904): OOI=Alarm{207068fe type 0 when 1450241794681 com.google.android.gms}
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1183): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/ProcessStatsService(  904): Pruning old procstats: /data/system/procstats/state-2015-12-15-17-27-52.bin
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 61
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,V/AlarmManager(  904): waitForAlarm result :8
,E/SMD     (  293): DCD ON
,I/PowerManagerService(  904): [PWL] Off : 1755s ago
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 62
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,I/MotionRecognitionService(  904): Plugged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/MotionRecognitionService(  904): setPowerConnected  = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 63
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
D/BatteryService(  904): stay LED for fully charged
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 64
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,I/MotionRecognitionService(  904): Plugged
I/MotionRecognitionService(  904): setPowerConnected  = true
,D/BatteryService(  904): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryService(  904): stay LED for fully charged
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/SMD     (  293): DCD ON
,E/Watchdog(  904): !@Sync 65
,D/BatteryService(  904): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService(  904): level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,D/BatteryService(  904): online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,D/BatteryService(  904): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService(  904): Plugged
,I/MotionRecognitionService(  904): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1183): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3139): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3139): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1183):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1183): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/KeyguardUpdateMonitor( 1183): handleBatteryUpdate
,D/BatteryService(  904): stay LED for fully charged
,E/SMD     (  293): DCD ON
,D/SSRM:n  (  904): SIOP:: AP = 280, PST = 280, CUR = 450
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 7914): 
D/AndroidRuntime( 7914): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7914): CheckJNI is OFF
D/AndroidRuntime( 7914): readGMSProperty: start
D/AndroidRuntime( 7914): readGMSProperty: already setted!!
D/AndroidRuntime( 7914): readGMSProperty: end
D/AndroidRuntime( 7914): addProductProperty: start
E/AffinityControl( 7914): AffinityControl: registerfunction enter
D/AndroidRuntime( 7914): Calling main entry com.android.commands.pm.Pm
D/PackageManager(  904): START PACKAGE DELETE: observer{38684767}
D/PackageManager(  904): pkg{<packageName>}
D/PackageManager(  904): user{0}
D/PackageManager(  904): caller{2000}
D/PackageManager(  904): flags{3}
D/PersonaManagerService(  904): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  904): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  904): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  904): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  904): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  904): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  904): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  904): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  904): getApplicationUninstallationEnabled
D/ApplicationPolicy(  904): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  904): !@killApplicatoin: 10295, uninstall pkg
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10295 user=-1: uninstall pkg
I/ActivityManager(  904): Killing 7169:com.test.thalitest/u0a295 (adj 0): stop com.test.thalitest
W/PackageSettings(  904): Skipping PackageSetting{3ce81198 com.example.hello/10292} due to missing metadata
I/WindowState(  904): WIN DEATH: Window{9d382e u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  254): id=15 Removed NainActivit (5/8)
I/SurfaceFlinger(  254): id=15 Removed NainActivit (-2/8)
I/SurfaceFlinger(  254): id=15 Removed NainActivit (-2/8)
D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager(  904): Killing 7476:com.android.chrome/u0a104 (adj 11): empty for 1806s
E/SMD     (  293): DCD ON
I/ActivityManager(  904): Killing 6222:com.sec.chaton/u0a102 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7460:com.sec.knox.bridge/1000 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7444:com.samsung.android.scloud.backup/u0a74 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 6717:com.osp.app.signin/u0a50 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 6667:com.policydm/1000 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7427:com.sec.android.soagent/u0a42 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7283:com.vlingo.midas/u0a38 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7409:com.samsung.android.app.pinboard:tagService/u0a36 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7383:com.samsung.klmsagent/u0a23 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7367:com.sec.android.fotaclient/u0a14 (adj 11): empty for 1806s
I/ActivityManager(  904): Killing 7349:com.sec.android.diagmonagent/1000 (adj 13): empty for 1807s
I/ActivityManager(  904): Killing 7332:com.sec.android.cloudagent/u0a4 (adj 13): empty for 1807s
I/ActivityManager(  904): Killing 6631:com.sec.pcw.device/1000 (adj 13): empty for 1807s
I/ActivityManager(  904): Killing 6936:com.samsung.android.snote/u0a168 (adj 13): empty for 1807s
I/ActivityManager(  904): Killing 6761:com.sec.android.provider.badge/u0a92 (adj 13): empty for 1807s
I/ActivityManager(  904): Killing 6275:com.android.vending/u0a33 (adj 13): empty for 1875s
I/ActivityManager(  904): Killing 6975:com.sec.kidsplat.installer/u0a189 (adj 13): empty for 1890s
I/ActivityManager(  904): Killing 6954:com.samsung.android.snote:provider/u0a168 (adj 13): empty for 1890s
I/ActivityManager(  904): Killing 6241:com.sec.android.app.controlpanel/u0a134 (adj 13): empty for 1890s
I/ActivityManager(  904): Killing 6913:com.samsung.helphub/1000 (adj 15): empty for 1890s
I/ActivityManager(  904): Killing 6898:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): empty for 1890s
I/ActivityManager(  904): Killing 6874:com.samsung.android.app.filterinstaller/1000 (adj 15): empty for 1890s
I/ActivityManager(  904): Killing 6806:com.google.android.apps.docs/u0a112 (adj 15): empty for 1891s
I/ActivityManager(  904): Killing 6813:com.wsomacp/u0a29 (adj 15): empty for 1892s
I/ActivityManager(  904): Killing 5711:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1892s
I/ActivityManager(  904): Killing 6777:com.sec.android.app.soundalive/u0a64 (adj 15): empty for 1892s
I/ActivityManager(  904): Killing 6737:com.android.mms/u0a55 (adj 15): empty for 1892s
I/ActivityManager(  904): Killing 5943:com.sec.android.gallery3d/u0a53 (adj 15): empty for 1893s
I/ActivityManager(  904):   Force finishing activity ActivityRecord{145450e8 u0 com.test.thalitest/.MainActivity t4}
W/ActivityManager(  904): mDVFSHelper.acquire()
W/libprocessgroup(  904): failed to open /acct/uid_10104/pid_7476/cgroup.procs: No such file or directory
D/ConnectivityService(  904): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG7005g", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/libprocessgroup(  904): failed to open /acct/uid_10102/pid_6222/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_7460/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10074/pid_7444/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10050/pid_6717/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_6667/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10042/pid_7427/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10038/pid_7283/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10036/pid_7409/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10023/pid_7383/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10014/pid_7367/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_7349/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10004/pid_7332/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_6631/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10168/pid_6936/cgroup.procs: No such file or directory
W/ActivityManager(  904): Spurious death for ProcessRecord{2ddbf2ac 7169:com.test.thalitest/u0a295}, curProc for 7169: null
W/libprocessgroup(  904): failed to open /acct/uid_10134/pid_6241/cgroup.procs: No such file or directory
D/CountryDetector(  904): No listener is left
W/libprocessgroup(  904): failed to open /acct/uid_10168/pid_6954/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_6913/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10126/pid_6898/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_6874/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10112/pid_6806/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10029/pid_6813/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_1000/pid_5711/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10064/pid_6777/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10055/pid_6737/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10053/pid_5943/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10189/pid_6975/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10033/pid_6275/cgroup.procs: No such file or directory
W/libprocessgroup(  904): failed to open /acct/uid_10092/pid_6761/cgroup.procs: No such file or directory
I/DBG_DM  ( 3687): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
I/ActivityManager(  904): Force stopping com.test.thalitest appid=10295 user=0: pkg removed
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
I/DBG_DM  ( 3687): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 18
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
I/DBG_DM  ( 3687): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
I/art     ( 4482): Explicit concurrent mark sweep GC freed 35223(1951KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 15MB/26MB, paused 533us total 24.890ms
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 1509): Explicit concurrent mark sweep GC freed 36656(2MB) AllocSpace objects, 0(0B) LOS objects, 25% free, 19MB/25MB, paused 614us total 74.594ms
E/SamsungIME( 1724): mOCRHelper is null
I/InputReader(  904): Reconfiguring input devices.  changes=0x00000010
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
W/GeofencerStateMachine( 1902): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager( 1442): creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
W/ResourcesManager( 1442): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/ResourcesManager( 1442): creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
W/ResourcesManager( 1442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
I/art     ( 2177): Explicit concurrent mark sweep GC freed 40323(2MB) AllocSpace objects, 9(144KB) LOS objects, 25% free, 22MB/30MB, paused 886us total 71.302ms
D/ResourcesManager( 1442): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
I/ActivityManager(  904): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=7950 uid=10023 gids={50023, 9997, 3003} abi=armeabi-v7a
E/Zygote  ( 7950): MountEmulatedStorage()
E/Zygote  ( 7950): v2
I/libpersona( 7950): KNOX_SDCARD checking this for 10023
I/libpersona( 7950): KNOX_SDCARD not a persona
W/ResourcesManager( 1442): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1442): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
W/SQLiteConnectionPool( 2177): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
I/SELinux ( 7950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7950): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/SecContentProvider2(  904): uri = 14 selection = getSealedState
D/SecContentProvider2(  904): mCursor = null
D/ApplicationPolicy(  904): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  904): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
I/art     (  904): Explicit concurrent mark sweep GC freed 20219(1762KB) AllocSpace objects, 8(128KB) LOS objects, 17% free, 37MB/45MB, paused 1.762ms total 144.220ms
D/ResourcesManager(  904): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     (  904): WaitForGcToComplete blocked for 126.855ms for cause Explicit
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 18
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
I/DBG_DM  ( 3687): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
D/TimaKeyStoreProvider( 7950): TimaSignature is unavailable
I/DBG_DM  ( 3687): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
D/ActivityThread( 7950): Added TimaKeyStore provider
I/DBG_DM  ( 3687): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
I/DBG_DM  ( 3687): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/ActivityManager(  904): post active user change for 0
D/KnoxTimeoutHandler(  904): postActiveUserChange for user 0
I/DBG_DM  ( 3687): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/SurfaceFlinger(  254): id=17 createSurf (1080x1920),2 flag=404, YUIInstallC
D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  904): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon(  904): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon(  904): setMouseCustomIcon IconType is same.101
D/PointerIcon(  904): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon(  904): setHoveringSpenCustomIcon IconType is same.1
V/ActivityThread( 3687): updateVisibility : ActivityRecord{ebf68ff token=android.os.BinderProxy@cf05cd4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/InputMethodManagerService(  904): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/ResourcesManager( 7950): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
D/SecContentProvider2(  904): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  904): mCursor = null
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/KLMS-2.4.511: ( 7950): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Evernote_H/Evernote_H.apk
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 7169 uid 10295
I/KLMS-2.4.511: ( 7950): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1450240130523
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
I/KLMS-2.4.511: ( 7950): MainReciver(): PACKAGE_REMOVED
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.511: ( 7950): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/RegisteredServicesCache( 1411): empty dynamic service
I/Timeline( 3687): Timeline: Activity_idle id: android.os.BinderProxy@cf05cd4 time:1972600
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
W/ActivityManager(  904): mDVFSHelper.release()
I/Timeline(  904): Timeline: Activity_windows_visible id: ActivityRecord{1d6440c8 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:1972622
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  904): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
E/Zygote  ( 7969): MountEmulatedStorage()
E/Zygote  ( 7969): v2
I/libpersona( 7969): KNOX_SDCARD checking this for 10116
I/libpersona( 7969): KNOX_SDCARD not a persona
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager(  904): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7969 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  904): Killing 7497:com.google.android.apps.magazines/u0a146 (adj 15): empty for 1808s
I/SELinux ( 7969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0 ver=27
I/SELinux ( 7969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N9005_5.0_0027
E/SELinux ( 7969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/RCPManagerService(  904): PackageReceiver onReceive()
I/HarmonyEASService(  904): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/EnterpriseDeviceManagerService(  904): Package has changed for user 0
D/EnterpriseDeviceManagerService(  904): Admin package name: com.google.android.gms
D/KnoxMUMContainerPolicy(  904): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/TimaKeyStoreProvider( 7969): TimaSignature is unavailable
D/ActivityThread( 7969): Added TimaKeyStore provider
D/BackupManagerService(  904): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  904): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  904): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  904): uID is 10295
V/EnterpriseBillingPolicy(  904): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  904): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  904): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  904): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  904): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  904): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  904): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Books/Books.apk
I/art     (  904): Explicit concurrent mark sweep GC freed 12134(604KB) AllocSpace objects, 0(0B) LOS objects, 17% free, 37MB/45MB, paused 3.088ms total 310.219ms
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/PackageManager(  904): delete codoeFile: 
I/AASAUninstall(  904):  com.test.thalitest not target!
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/PackageManager(  904): result of delete: 1{38684767}
D/AndroidRuntime( 7914): Shutting down VM
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
W/libprocessgroup(  904): failed to open /acct/uid_10146/pid_7497/cgroup.procs: No such file or directory
D/KnoxTimeoutHandler(  904): handleActiveUserChange for user 0
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager( 7969): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
W/ResourcesManager(  904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  904): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  904): creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/elm:14491( 7969): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491( 7969): ELMEngine.ELMEngine( context ).
D/ResourcesManager(  904): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk

```
